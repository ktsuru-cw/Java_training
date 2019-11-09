## if

```java
int num = 5;
if (num == 5) {
     System.out.println("numは5です");
}
```

if文は処理の分岐を作る事ができます。`if()`の`()`の中に条件を書いて、条件の結果を`boolean`で判定します。
つまり`true`か`false`かを判定することで、`if(){}`の`{}`内に書かれた処理を実行するかしないかを条件判定します。
例として書いているif文だと、if文の前にint型の変数`num`に5を代入しています。
`if (num == 5)` で、numが5かどうかを判定しています。
`num == 5`を判定した結果、`true`を受け取った場合は、`{}`内に書いた処理である文字出力を実行します。
`num == 5`を判定した結果、`false`を受け取った場合は、`{}`内の処理は行わず、次の処理へ移っていきます。

if文にはセットで使われる、`else`という条件文があるのであわせて学びましょう。

```java
int num = 5;
if (num == 5) {
     System.out.println("numは5です");
} else {
     System.out.println("numは5ではありません");
}
```

if文の`else`は、`if`の条件式を判定した結果が`false`だった場合に、`else{}`へ処理が移り`else{}`の`{}`ブロックの中に書かれた処理を実行します。

もう一つif文の書き方として学んでもらいたいのが、`else if`です。
`if`の条件も少し変えてみましょう。

```java
int num = 3
if (num == 1) {
    System.out.println("numは1です");
} else if (num == 2) {
    System.out.println("numは2です");
} else {
    System.out.println("numは1でも2でもありません");
}
```

`int num`変数を作成して、値を代入しています。  
numの値によって処理内容の分岐を決めています。

---
