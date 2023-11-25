# HTMLを表示する
```
public class Main {
    public static void main(String[] args) {
        System.out.print("<h1>hello world</h1>");
        System.out.print("<p>世界の皆さん、");
        System.out.print("<b>こんにちは</b></p>"); ※<b>は太字
    }
}
※println ⇒ printにすると、textでは改行されず続けて表示される
```

# 型変換(データのキャスト)
```
public class Main {
	public static void main(String[] args) {
		double rand = Math.random() *3 + 5; //5-7（5から3つ分）までのランダムな数字
		int number = (int)rand; //double型からint型へ変換
		System.out.println(number);

		double number1 = 3.14;
		System.out.println(number); //3.14
    		System.out.println((int) number1); //3 実数を整数データに変換

		int number2 = 3;
		System.out.println(number2); //3
    		System.out.println((double) number2); //3.0 整数を実数データに変換

		String text = "123";
		System.out.println(text); //123
		System.out.println(Integer.parseInt(text)); //123 文字列をint型に変換するメソッド
		System.out.println(Double.parseDouble(text)); //123.0
	}
}
```
# 計算
```
public class Main {
	public static void main(String[] args) {
		int number = (97 + 3) * 2 ; ※200 :*%がある場合、()があればのその中を優先的に計算する
		System.out.println(number + 30); //230
		System.out.println(number + number); //400

		System.out.println(10/3); //3
		System.out.println(10/3.0) //3.3333333335
	}
}
```
# データの種類
```
public class Main {
	public static void main(String[] args) {
		int number = 100 + 30;	// 数値
		String text = "hello" + "java";	// 文字列
		System.out.println(number);
		System.out.println(text);
		System.out.println(number + text); ※130hellojava：130が文字列として自動的に変換される
		System.out.println(number + 20); ※150
	}
}
```
