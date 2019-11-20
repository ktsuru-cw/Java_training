# Java研修

## HelloWorld

### プログラミングファイル作成

まずはファイルを作成しましょう。
コーディング用に用意したフォルダをエクスプローラで開いて、ファイルの新規作成で拡張子.javaファイルを作成します。

`HelloWorld.java`

作成したファイルをVSC等のエディタで開いて、プログラムを記述します。

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}
```

### コマンド実行手順

- コマンドプロンプトを起動しましょう。

【起動方法例】

1. windowsキー＋rキーで「ファイル名を指定して実行」を起動。
1. `cmd`と入力してOKボタン または、 Enterキーを押下。

`cd` コマンドでカレントディレクトリを移動します。

```cmd
cd c:¥java
```

javacコマンドで実行したいjavaファイルをコンパイルします。

```java
javac HelloWorld.java
```

コンパイルが完了すると、拡張子`.class`ファイルが作成されます。
`.class`を省いたファイル名をjavaコマンドで実行します。

```java
java HelloWorld
```

## プログラムの書き方

### インデント

①
```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}
```

②
```java
class HelloWorld {
public static void main(String[] args) {
System.out.println("Hello world");
}
}
```

読みやすい綺麗なプログラムはどちらでしょうか？
正解は①です。
インデントとはプログラミングにおいてプログラムの構造を明らかにするため、
空白、もしくはタブなどで「字下げ」をすることです。
これによりどの処理がどこで終了しているのかが一目で分かります。


### 基本構造

example.01を例にJavaプログラミングの基本構造を説明します。
```java
// Javaプログラミング
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}
```
 - 1行目： //の行はコメントです。コメントが複数行になる場合は/*～*/で囲むことでコメントになります。
 - 2行目： `class HelloWorld{` HelloWorldというクラスの始まりを表します。
 - 3行目： `public static void main(String[] args) {` メインメソッドの始まりを表します。Javaプログラムには必ず必要です。
 - 4行目： メインメソッドの実行文です。`System.out.println()` ()の中のメッセージを出力し、改行するメソッドです。


### プログラミングを書く時の決まり事

- Java言語に予約されている用語のスペルミスはエラーとなります。
- 大文字と小文字のミス。予約語や定義した識別子は大文字と小文字を区別します。
- { }、( )、" "、' '等のカッコは全部ペアでなければいけません。
- 文の終わりの";"を忘れてはいけません。
- " "の中を除き、全角文字を使ってはいけません。
