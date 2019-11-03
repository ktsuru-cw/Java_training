# Java_training

## 研修予定一覧

<!-- toc -->

## HelloWorld

### プログラミングファイル作成

まずはファイルを作成しよう。
コーディング用に用意したフォルダをエクスプローラで開いて、ファイルの新規作成で拡張子.javaファイルを作成する。

`HelloWorld.java`

作成したファイルをVSC等のエディタで開いて、プログラムを記述。

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}
```

### コマンド実行手順

- コマンドプロンプトを起動する。

【起動方法例】

1. windowsキー＋rキーで「ファイル名を指定して実行」を起動する。
1. `cmd`と入力してOKボタン または、 Enterキーを押下する。

`cd` コマンドでカレントディレクトリを移動する。

```cmd
cd c:¥java
```

javacコマンドで実行したいjavaファイルをコンパイルする。

```java
javac HelloWorld.java
```

コンパイルが完了すると、拡張子`.class`ファイルが作成される。
`.class`を省いたファイル名をjavaコマンドで実行する。

```java
java HelloWorld
```

[Question01](/questions/01_question.html)