# 買い物アプリ（値段の計算）
```
public class Main {
	public static void main(String[] args) {
		int apple_price = (int)(Math.random() * 3 + 1) * 100; //1-3をランダムに選択、その値に100をかけて整数に変換
		int apple_num = (int)(Math.random() * 10 + 1); //ランダムな個数を1-10に設定、個数を計算した後整数に変換
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

# おみくじプログラム（IF文の条件分岐・比較演算子）
```
public class Main {
	public static void main(String[] args) {
	  int omikuji = (int)(Math.random() * 10 + 1);
	  //System.out.println(omikuji); //デバック
	  if (omikuji == 1) {
		System.out.println("大吉");
	  } else if (omikuji == 2) {
		System.out.println("中吉");
	　} else if (omikuji <= 4) {
		System.out.println("小吉"); //3.4
	  } else if (omikuji <= 7) {
		System.out.println("凶"); //5.6.7 
	  } else {
		System.out.println("大凶"); //上記以外
　　　　　}
	}
}
```

# RPGの戦闘シーン
```
public class Main {
	public static void main(String[] args) {
	    int hit = (int)(Math.random() * 10 + 1);
	    //System.put.println(hit);
	    if (hit < 6) {
	        System.out.println("スライムに、" + hit "のダメージを与えた！");
	    } else {
	        System.out.println("クリティカルヒット！スライムに、100のダメージを与えた！");
	    }
	}
}
```

# 西暦から平成何年か求める
```
import java.util.Calender; //現在の年月日
public class Main {
	public static void main(String[] args) {
	    Calender calender = Calender.getInstance();
        int seireki = calender.get(Calender.YEAR);
        System.out.print("西暦" +seireki + "年は、"); //改行しなくなる
        
        //西暦年から平成年を計算する
        int heisei = seireki - 1988;
        System.out.println("平成" + heisei + "です");
	}
}
```
