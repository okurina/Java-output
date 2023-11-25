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

# 型変換
```
public class Main {
	public static void main(String[] args) {
		double rand = Math.random() *3 + 5; ※5-7（5から3つ分）までのランダムな数字
		int number = (int)rand; ※double型からint型へ変換
		System.out.println(number);
	}
}
```
# 計算
```
public class Main {
	public static void main(String[] args) {
		int number = (97 + 3) * 2 ; ※200 :*%がある場合、()があればのその中を優先的に計算する
		System.out.println(number + 30); ※230
		System.out.println(number + number); ※400
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
# データの計算
```
```
