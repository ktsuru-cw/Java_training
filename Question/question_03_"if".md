# Question3

## if_①
●変数ageが20以上の場合は「20歳以上です」、それ以外の場合は「20歳未満です」を出力するプログラムを完成させてください。  
●if文の /* TODO */ を埋めてください。

```java
int age = 20;
if ( /* TODO */ ) {
    System.out.println("20歳以上です");
} else {
    System.out.println("20歳未満です");
}
```

## if_②
●変数ageが20以上もしくは変数studentがtrueの場合は「OK」、  
 変数ageが20未満かつ変数studentがfalseの場合は「NG」を出力するプログラムを完成させてください。  
●if文の /* TODO */ を埋めてください。

```java
int age = 20;
boolean student = true;
if ( /* TODO */ ) {
    System.out.println("OK");
} else {
    System.out.println("NG");
}
```

## if_③
●変数drinkの中身を判定するif文を完成させてください。  
●変数drinkに”お茶”が代入されている場合は「これはお茶です」、変数drinkに”コーヒー”が代入されている場合は「これはコーヒーです」、  
 変数drinkに”ジュース”が代入されている場合は「これはジュースです」、変数drinkに”お茶””コーヒー””ジュース”以外が代入されている場合は「これは飲み物です」を出力してください。  
●if文の /* TODO */ を埋めてください。

```java
String drink = "";
if (drink.equals("お茶")) {
  System.out.println("これはお茶です");
} /* TODO */ (drink.equals("コーヒー")) {
  System.out.println("これはコーヒーです");
} /* TODO */ (drink.equals("ジュース")) {
  System.out.println("これはジュースです");
} else {
  System.out.println("これは飲み物です");
}
```

## if_④
次の手順に従ってプログラムを作成してください。

●int型のhightを宣言してください。  
●変数hightに180を代入してください。  
●hightの内容を比較し以下の内容が出力されるようにしてください。  
　・hightが180以上の場合は、”Large”と出力します。  
　・hightが170～179の場合は、”Medium”と出力しています。  
　・hightが169以下の場合は、”Small”と出力します。  

### hight=180の場合の実行結果
```java
Large
```
### hight=170～179の場合の実行結果
```java
Medium
```
### hight=169以下の場合の実行結果
```java
Small
```

[answer_03 Example_"if"](https://github.com/ktsuru-cw/Java_training/blob/master/Answer/answer_03_%22if%22.md)
