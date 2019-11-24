# Answer

## for文_①
●”Hello”を5回出力するfor文を完成させてください。    
● /* TODO */ の部分を埋めてください。  

```java
for (int i = 0; i < 5; i++) {
    System.out.println("Hello");
}
```

## for文_②
●1から100まで出力するfor文を完成させてください。    
● /* TODO */ の部分を埋めてください。  

```java
for (int i = 1; i <= 100; i++) {
    System.out.println(i);
}
```

## for文_③
●100から1まで出力するfor文を作成してください。    

```java
for (int i = 100; i >= 1; i--) {
    System.out.println(i);
}
```

## for文_④
●1から10までの合計値を出力するfor文を完成させてください。    
● /* TODO */ の部分を埋めてください。  

```java
int total = 0;

for (int i = 1; i <= 10; i++) {
    total += i;
}
System.out.println(total);
```

## for文&if文_①
●1から100まで出力するfor文を完成させてください。  
●1から100の中でも偶数のみを出力してください。      
● /* TODO */ の部分を埋めてください。  

```java
for (int i = 1; i <= 100; i++) {
    if (i % 2 == 0) {
        System.out.println(i);
    }
}
```

## for文&if文_②
●100から1まで出力するfor文を完成させてください。  
●100から1の中でも奇数のみを出力してください。  

```java
for (int i = 100; i >= 1; i--) {
    if (i % 2 == 1) {
        System.out.println(i);
    }  
}
```

## fizzbuzz問題
●1から１００未満を順番に出力してください。ただし以下の条件も満たしてください。    
　・3の倍数の時にfizz    
　・5の倍数の時にbuzz    
　・3と5の倍数の時にfizzbuzz    

```java
for (int i = 1; i < 100; i++) {
    if (i % 15 == 0) {
    //if(number % 3 == 0 && number % 5 == 0) でもOK！
        System.out.println("fizzbuzz");
    } else if (i % 3 == 0) {
        System.out.println("fizz");
    } else if (i % 5 == 0) {
        System.out.println("buzz");
    } 
}
```
