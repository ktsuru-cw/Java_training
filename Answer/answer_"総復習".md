# answer

01.以下の文章を出力しましょう
```java
public class Main {

	public static void main(String[] args) {
		
		System.out.println("Javaプログラミングを始めましょう！");

	}

}
```

02.三角形の幅、高さの整数を変数宣言し、以下を表示させましょう
```java
public class Main {

	public static void main(String[] args) {

		int width = 100; 	//幅
		int height =  70;	//高さ

		int result = (width * height)/2;

		System.out.println("幅:    " + width);
		System.out.println("高さ:  " + height);
		System.out.println("面積:  " + result );

		//連結
		//System.out.println( "幅:\t" + width + "\n"+
		//		"高さ:\t" + height + "\n"+
		//		"面積:\t" + result );
		}
}
```

03.10と3の2つの整数を変数宣言し、算術演算子を使用して以下のように表示させましょう
```java
public class Main {

	public static void main(String args[]) {

		int num1 = 10;
		int num2 = 3;

		System.out.println( "足し算:\t" + (num1 + num2) );
		System.out.println( "引き算:\t" + (num1 - num2) );
		System.out.println( "掛け算:\t" + (num1 * num2) );
		System.out.println( "割り算:\t" + (num1 / num2) );
		System.out.println( "余　り:\t" + (num1 % num2) );
	}
}
```

04.繰返し処理で以下を表示させましょう
```java
public class Main {
	
	public static void main(String args[]) {
		
		for( int i=1; i<11; i++ ){
			System.out.print( i +" " );
		}

	}

}
```

05.掛け算九九を 表示させましょう
```java
public class Main{

	public static void main(String args[]) {

		for(int i =1; i<10; i++){
			for(int j=1; j<10; j++){
				System.out.print(i*j + "\t");
			}
			System.out.println();
		}
	}
}
```

06.西暦(任意を変数宣言し、うるう年かどうか判別し、以下を表示させましょう（うるう年は、4で割切れ、かつ、100で割切ることができません）
```java
public class Main {
	public static void main(String args[]) {

		int year = 2015;

		if(year%4==0 && year%100!=0){
			System.out.println( year +"年はうるう年です。" );
		}else{
			System.out.println( year +"年はうるう年ではありません。" );
		}
	}
}
```

07.5人分の点数の配列を宣言し、以下を表示させましょう(for文を使用)
```java
public class Main {
    public static void main(String args[]) {

			int points[] = { 60, 70, 80, 90, 100 };
						//↓pointsの配列の長さ
				for( int i=0;i<points.length;i++){

					System.out.println( (i+1)+"人目は、"+points[i]+"点です。");

				}
		}
}
```

08.同数の氏名の配列を宣言し、以下を表示させましょう
```java
public class Main {
	public static void main(String args[]) {

			char[] names={'A','B','C','D','E'};
			int[] points = { 60, 70, 80, 90, 100 };
								//↓pointsの配列の長さ
				for( int i=0;i<names.length;i++){
					String msg ="";
					if(points[i] >= 80){
					 	msg= "[合格]";
					}
					System.out.println( names[i]+"さんは、"+points[i]+"点です。"+msg);
				}
		}
}
```

09.5つの文字型の配列をカンマ区切りで表示しましょう(拡張for文を使用)
```java
public class Main {
	public static void main(String[] args) {

		String[] names = { "名前1", "名前2", "名前3", "名前4", "名前5" };

		int i = 0;
		for( String name : names ){
			if( i<names.length-1 ){
				name += ",";
			}
			System.out.print( name );
			i++;
		}

	}
}
```

10.メインメソッドから引数を渡して、氏名と年齢を出力するプログラムを作成しましょう
```java
public class Main {
	public static void main(String[] args) {

		String name = "花子さん";
    		int age = 15;

    		output(name, age);
	}
  
	public static void output(String name, int age) {
  
		System.out.println(name + "は" + age + "歳です。");
    
	}
}
```

11.引数で渡した動物の鳴き声を表示するプログラムを作成しましょう
```java
public class Main {
	public static void main(String[] args) {

		String animal = "猫"

    		animalCry(animal);
	}
  
	public static void animalCry(String animal) {
  
		int i = 0;
		String[] animals = {"猫", "犬", "鳥"};
		String[] cries = {"にゃー", "ワンワン", "ピーピー"};
		
		for (i == 0; i < animals.length; i++){
			if(animals[i].equals(animal)){
				System.out.println(cries[i]);
			}
		} 
	}
}
```
