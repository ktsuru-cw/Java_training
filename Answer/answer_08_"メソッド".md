# answer_08

メインメソッドから引数を渡し、戻り値で三角形の面積を返すプログラムを作成してください。
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
