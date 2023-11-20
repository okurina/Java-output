# 買い物アプリ（値段の計算）
```
public class Main {
	public static void main(String[] args) {
		int apple_price = (int)(Math.random() * 3 + 1) * 100; ※1-3をランダムに選択、その値に100をかけて整数に変換
		int apple_num = (int)(Math.random() * 10 + 1); ※ランダムな個数を1-10に設定、個数を計算した後整数に変換
		System.out.println("リンゴの単価：" + apple_price + "円");
    		System.out.println("リンゴを買う数：" + apple_num + "個");

    		int total = apple_price * apple_num;
    		System.out.println("合計金額：" + total + "円");

	}
}
```

# 「スキ/キライ」占い（IF文の条件分岐）
```
public class Main {
	public static void main(String[] args) {
          int number = (int)(Math.random() * 2 + 1);
          if (number == 1) {
		System.out.println("スキ！"); ※条件式が成立
	  } else if (number == 2) {
		System.out.println("どちらでもない");
          } else {
		System.out.println ("キライ");
          }
      }
}
```

# おみくじプログラム
```
public class Main {
	public static void main(String[] args) {
	  int omikuji = (int)(Math.random() * 10 + 1);
	  //System.out.println(omikuji); ※デバック
	  if (omikuji == 1) {
		System.out.println("大吉");
	  } else if (omikuji == 2) {
		System.out.println("中吉");
	　} else if (omikuji <= 4) {
		System.out.println("小吉"); ※3.4
	  } else if (omikuji <= 7) {
		System.out.println("凶"); ※5.6.7 
	  } else {
		System.out.println("大凶"); ※上記以外
　　　　　}
	}
}
```
