# answer_08

①メインメソッドから引数を渡し、戻り値で三角形の面積を返すプログラムを作成してください。
```java
public class Main {
 
    public static void main(String[] args) {
        int buttom = 7;
	int hight = 5;
	float menseki = 0;
	
        menseki = calculate(buttom, hight);
  
	System.out.println(menseki);
    }

    public static float calculate(int x, int y) {
        float result = (x * y) / 2;
	
	return result;
    }
}
```


②引数で渡した値を判定し、偶数か奇数かを表示するプログラムを作成してください。  

 (例１)
 ```java
public class Main {
 
    public static void main(String[] args) {
        int num = 5;
        String result = "";
	
        result = oddEven(num);
	
        System.out.println(result);
    }

    public static String oddEven(int num) {
        String result = "";
	
        if(num % 2 == 0){
                result = num + "は偶数です。";
        } else {
                result = num + "は奇数です。";
        }
	
        return result;
    }
}
```

 (例２)
 ```java
public class Main {
 
    public static void main(String[] args) {
        int num = 5;
	
        oddEven(num);
    }

    public static void oddEven(int num) {
        int result = 0;
	
        result = num % 2;
	
        if(result == 0){
                System.out.println(num + "は偶数です。")
        } else {
                System.out.println(num + "は奇数です。")
        }
    }
}
```
