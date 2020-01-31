# answer_09

コマンドラインから引数として任意の数値を1つ指定し、その数値が偶数なら「/*任意の数値*/ は偶数です」、  
奇数なら「/*任意の数値*/ は奇数です」と表示するoddEvenクラスを作成してください。  
```java
public class Main {
 
    public static void main(String[] args) {
      if(args.length != 1){
        System.out.println("引数を一つ指定してください。");
        System.out.println("Main 値1");
        System.exit(1);
      }
      
    }
}
```
