## 例外処理

### 例外処理とは

実行停止してはいけないプログラムの途中で  
なんらかの問題が発生した場合、その後の処理を自分でコントロールしたいときに使用します。  
Javaで例外処理を実装するには、try-catch処理の中でExceptionクラスを指定する必要があります。

### try-catch

try-catch文とは、例外が発生する可能性がある処理に使うものです。  
try-catch文を使うことで、例外が発生しない場合の処理と、例外が発生したときの処理を分けることができます。  
さらに、finallyを使って例外の有無に関わらず、最後に必ず実行される処理を記述することができます。

```java
try {
    例外が発生する可能性のある処理
} catch (例外の型 引数) {
    例外が発生した場合の処理(例外が発生しなければ行われない処理)
} finally {
    例外の有無に関わらず、最後に必ず実行される処理
}
```

下記の例文は、0で除算すると異常終了します。
```java
public static void main(String args[]){
    int num = 10 / 0;
    System.out.println("num = " + num):
}
```
上記を実行すると、以下のエラーメッセージが表示されプログラムは異常終了してしまいます。
```java
Exception in thread "main" java.lang.ArithmeticException: / by zero
```
このエラーメッセージにある「Exception」というのが例外をあらわしており、  
「in thread "main"」がスレッドをあらわしています。  
(スレッドとは"処理を実行する流れの単位"のこと)  
その後の「java.lang.ArithmeticException: / by zero」が例外の内容をあらわしていて、
ここではゼロで割った例外だという意味になります。  

例外が起きた場合にアプリケーションが終了してしまっては困ります。  
そこで例外を予想して、例外が起きた場合に適当な処理をさせる必要があります。  
```java
public static void main(String args[]){
    try{
        int num = 10 / 0;
        System.out.println("num = " + num):
    }catch(ArithmeticException e){
        System.out.println("0除算エラーです。"):
    }finally{
        System.out.println("終了"):
    }
}
```
ちなみに、例外の変数名はプログラマーの好きにできますが、単に“e”とするのが広く見られるスタイルです。  
eの他にはexも良く見ますが、exceptionのような長い変数名はほとんど見かけません。  
明確なものへは単純なものにするのがプログラマーの共通見解です。  

＜Exception例＞  

|例外|内容|
|:--|:--|
|EOFException|入力の途中で、予想外のファイルの終了、または予想外のストリームの終了があったことを表すシグナル|
|FileNotFoundException|指定されたパス名で示されるファイルが開けなかったことを通知する|
|IOException|なんらかの入出力例外の発生を通知するシグナルを発生させる|
|ArithmeticException|算術計算で例外的条件が発生した場合にスローされる|
|NullPointerException|オブジェクトが必要な場合に、アプリケーションが null を使おうとするとスローされる|
