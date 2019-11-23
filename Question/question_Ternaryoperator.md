# Question

## Ternaryoperator_①
●以下のif文を三項演算子に直してください。  
●変数ageが20以上の場合は「20歳以上です」、それ以外の場合は「20歳未満です」を出力するプログラムを完成させてください。  
●三項演算子の /* TODO */ を埋めてください。  
```java
// if文
int age = 20;
if (age >= 20) {
    System.out.println("20歳以上です");
} else {
    System.out.println("20歳未満です");
}
```
```java
// 三項演算子
int age = 20;
System.out.println( /* TODO */ ? "20歳以上です" : "20歳未満です");
```

## Ternaryoperator_②
●変数ageが20以上もしくはstudentがtrueの場合は「OK」、  
 変数ageが20未満かつstudentがfalseの場合は「NG」を出力するプログラムを完成させてください。  
●三項演算子の /* TODO */ を埋めてください。  

```java
// if文
int age = 20;
boolean student = true;
if (age >= 20 || student == true) {
    System.out.println("OK");
} else {
    System.out.println("NG");
}
```
```java
// 三項演算子
int age = 20;
boolean student = true;
System.out.println( /* TODO */ == true ? "OK" : "NG");
```

## Ternaryoperator_③
●変数drinkの中身を判定するif文を完成させてください。  
●変数drinkに”お茶”が代入されている場合は「これはお茶です」、変数drinkに”コーヒー”が代入されている場合は「これはコーヒーです」、  
 変数drinkに”ジュース”が代入されている場合は「これはジュースです」、変数drinkに”お茶””コーヒー””ジュース”以外が代入されている場合は「これは飲み物です」を出力してください。  
●三項演算子の /* TODO */ を埋めてください。

```java
// if文
String drink = "";
if (drink.equals("お茶")) {
  System.out.println("これはお茶です");
} else if (drink.equals("コーヒー")) {
  System.out.println("これはコーヒーです");
} else if (drink.equals("ジュース")) {
  System.out.println("これはジュースです");
} else {
  System.out.println("これは飲み物です");
}
```
```java
// 三項演算子
String drink = "";
System.out.println(
    drink.equals(/* TODO */) : 
    drink.equals(/* TODO */) : 
    drink.equals(/* TODO */) : 
    "これは飲み物です"
);
```
