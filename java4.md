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
		double rand = Math.random() *100 + 1
		int number = (int)rand; ※double型からint型へ変換
		System.out.println(number);
	}
}
```
