# answer_08

①メインメソッドから引数を渡し、戻り値で三角形の面積を返すプログラムを作成してください。
```java
public class Main {
 
    public static void main(String[] args) {
        int buttom = 7;
	int hight = 5;
	int menseki = 0;
	
        menseki = Calculate(buttom, hight);
  
	System.out.println(menseki);
    }

    public static float Calculate(int x, int y) {
        int result = (x * y) / 2;
	
	return result;
    }
}
```

②引数で渡した値を判定し、偶数か奇数かを表示するプログラムを作成してください。  

 - メインクラスに奇数と偶数を判定するOddEvenメソッドを作成  
 
 (例１)
 ```java
public class Main {
 
    public static void main(String[] args) {
        int num = 5;
	String result = "";
	
	result = OddEven(num);
	
	System.out.println(result);
    }

    public static String OddEven(int num) {
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
	
	OddEven(num);
    }

    public static void OddEven(int num) {
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
