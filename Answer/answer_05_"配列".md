# Answer

## 配列_①
●以下の配列scoresに「90、45、72、85、64」の値を代入してください。※for文は使わないこと    
● /* TODO */ の部分を埋めてください。  

```java
int[] scores = new int[5];

scores[0] = 90;
scores[1] = 45;
scores[2] = 72;
scores[3] = 85;
scores[4] = 64;
```

## 配列_②
●配列scoresの3番目の値を出力してください。※for文は使わないこと    
● /* TODO */ の部分を埋めてください。  

```java
int[] scores = new int[5];

scores[0] = 90;
scores[1] = 45;
scores[2] = 72;
scores[3] = 85;
scores[4] = 64;

System.out.println(scores[2]);
```

## 配列&for文
●配列scoresの値すべてをfor文で出力してください。    
● /* TODO */ の部分を埋めてください。  

```java
int[] scores = {90, 45, 72, 85, 64};

for (int i = 0; i < scores.length; i++) {
// for (int i = 0; i < 5; i++) でもOK！
    System.out.println(scores[i]);
}
```

## 配列&if文
●配列scoresの値をfor文で出力してください。  
●配列scoresの値の中でも偶数のものだけを出力してください。  
● /* TODO */ の部分を埋めてください。  

```java
int[] scores = {90, 45, 72, 85, 64};

for (int i = 0; i < scores.length; i++) {
// for (int i = 0; i < 5; i++) でもOK！
    if (scores[i] % 2 == 0) {
        System.out.println(scores[i]);
    }
}
```
