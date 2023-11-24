# 複数のデータを分類する(ループ+if)
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int count = scan.nextInt(); //入力タブから最初の整数を受け取る
        
        for (int i = 0; i < count; i++) {
            int number = scan.nextInt(); //入力タブから二列目以降の（表示する）整数を受け取る
            System.out.println(number);

            if (number == 10) { //受け取ったデータをifで条件分岐する
                System.out.println(number + "は10に等しい");
            } else if (number > 10) {
                System.out.println(number + "は10より大きい");
            } else {
                System.out.println(number + "は10未満");
            }
       }
    }
}
```
# 複数の条件を組み合わせる（AND）
```
public class Main {
	public static void main(String[] args) {
		double rand = (Math.random() * 100) + 1; //1-100までのランダムな数字
		int number3 = (int) rand;
		System.out.println(number);

		if (number >= 30 && number <= 60) { //30以下、かつ60以上の時
    			System.out.println("当たり");
		} else {
    			System.out.println("残念！");
		}
      }
}
```
# 複数の条件を組み合わせる（OR）
```
public class Main {
	public static void main(String[] args) {
		double rand = (Math.random() * 100) + 1; //1-100までのランダムな数字
		int number3 = (int) rand;
		System.out.println(number);

		if (number >= 30 || number <= 60) { //30以下、または60以上の時
    			System.out.println("当たり");
		} else {
    			System.out.println("残念！");
		}
      }
}
```
# 条件の評価結果(論理型)
*論理演算は、評価の結果として、trueかfalseを返す
*trueかfalseかという条件の評価結果もデータなので、変数に代入することができる
```
public class Main {
    public static void main(String[] args) {
        int number = 1;
        boolean flag = number == 1;　//「number == 1」の評価結果を、flag変数に代入
        if (flag) {
            System.out.println("スキ！");   //条件が成立したときの処理
        } else {
            System.out.println("キライ");   //条件が成立しなかったときの処理
        }
        System.out.println(flag);
    }
}
```

