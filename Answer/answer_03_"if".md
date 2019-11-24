# Answer3

## if_①
```java
int age = 20;
if (age >= 20) {
    System.out.println("20歳以上です");
} else {
    System.out.println("20歳未満です");
}
```

## if_②
```java
int age = 20;
boolean student = true;
if (age >= 20 || student == true) {
    System.out.println("OK");
} else {
    System.out.println("NG");
}
```

## if_③
```java
String drink = "";
if (drink == "お茶") {
  System.out.println("これはお茶です");
} else if (drink.equals("コーヒー")) {
  System.out.println("これはコーヒーです");
} else if (drink == "ジュース") {
  System.out.println("これはジュースです");
} else {
  System.out.println("これは飲み物です");
}
```

## if_④
```java
int hight;
hight = 180;

// int hight = 180; でもOK！

if (hight >= 180) {
    System.out.println("Large");
} else if (hight >= 170) {
    System.out.println("Medium");
} else {
    System.out.println("Small");
}
