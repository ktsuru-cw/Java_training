# answer_09

コマンドラインから引数として任意の数値を1つ指定し、その数値が偶数なら「/*任意の数値*/ は偶数です」、  
奇数なら「/*任意の数値*/ は奇数です」と表示するoddEvenクラスを作成してください。  
```java
public class oddEven {
 
    public static void main(String[] args) {
	    if(args.length != 1){
	      System.out.println("引数を一つ指定してください。");
	      System.exit(1);
	    }
	    int num = 0;
	    num = Integer.parseInt(args[0]);

	    if(num % 2 == 0) {
	    	System.out.println(args[0] + "は偶数です。");
	    } else {
	    	System.out.println(args[0] + "は奇数です。");
	    }
    }
}
```
