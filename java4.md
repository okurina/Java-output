# ループ処理(for)
```
public class Main {
    public static void main(String[] args) {
        String greeting = "Hello japan";

        for (int i = 0; i < 5; i++) {  //i=カウンタ変数
          //int i = 0; ⇒初期値　i < 5; ⇒繰り返し条件　i++ ⇒カウンタ変数の増減
            System.out.println(greeting);
        }
    }
}
```
# ループ処理(while)
```
public class Main {
    public static void main(String[] args) {
        int i = 0; // カウンタ変数の初期化
        while (i <= 5) { //0,1,2,3,4,5
            System.out.println("hello world" + i)// 繰り返し処理
            i = i + 1; // カウンタ変数の更新
        }
        System.out.println("last" + i); //6
    }
}
```

# 繰り返し回数を受け取る
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int count = scan.nextInt();
        System.out.println(count);

        for (int i = 0; i < count; i++) {
            System.out.println("Hello world");
        }
    }
}
```
# 複数のデータを受け取る
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int count = scan.nextInt(); //入力タブから整数を受け取る
        System.out.println(count);

        for (int i = 0; i < count; i++) {
            String name = scan.next(); //入力タブから文字列を受け取る
            System.out.println("Hello " + name);
        }
    }
}
```
