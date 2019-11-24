## メソッド

### メソッドとは

メソッドとは、いくつかの処理をひとまとめにしたものです。処理をメソッドにしてまとめておくことで、同じ処理を繰り返し行う場合に同じコードを記述するのではなく、メソッドを繰り返し使用するだけでよくなります。

メソッドを使うことで、コードが読みやすくなったり、変更が容易になるというメリットがあります。

### メソッドを定義する

メソッドは以下のように定義します。

```java
修飾子　戻り値の型　メソッド名(引数の型){
    メソッドの処理
}
```

戻り値を返すメソッド
```java
public int increment(int num){
    num++;
    return num;
}
```

戻り値を返さないメソッド
```java
public void increment(int num){
    num++;
}
```

### メソッドの呼び出し方

メソッドの呼び出し方は戻り値を返すかどうかで変わってきます。

→戻り値を返さない場合
```java
メソッド名(引数)
```
```java
int num = 5;

increment(num);
```


→戻り値を返す場合
```java
戻り値を格納する変数名 = メソッド名(引数)
```
```java
int Status = 0;
int num = 5;

Status = increment(num);
```

### メソッドに引数を使って値を渡す方法

メソッドに引数を使って値を渡すためには、メソッド名の後の括弧の中に渡したい値を指定します。
```java
public class Main {
 
    public static void main(String[] args) {
        add(1, 2);
        add(4, 6);
    }
 
    public static void add(int num1, int num2) {
        System.out.println(num1 + num2);
    }
}
```

実行結果：
```java
3
10
```

このプログラムではメソッドの引数に2つの値を指定して、メソッドの中で足し算をした値を表示する処理をしています。

### メソッドの戻り値(return)の使い方

メソッドの戻り値を使うことで、メソッドの処理の結果を呼び出し元で使用することができます。
戻り値は「return」を使用して指定します。

```java
public class Main {
 
    public static void main(String[] args) {
        int result = add(1, 2);
        System.out.println(result);
    }
 
    public static int add(int num1, int num2) {
        return num1 + num2;
    }
}
```

実行結果：
```java
3
```

このプログラムでは戻り値を使って、メソッドで足し算した結果を呼び出し元に返して表示しています。

[question_08_"メソッド"](https://github.com/ktsuru-cw/Java_training/blob/master/Question/question_08_%22%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89%22.md)
