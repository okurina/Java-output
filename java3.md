# ループ処理
```
public class Main {
    public static void main(String[] args) {
        String greeting = "Hello japan";

        for (int i = 0; i < 5; i++) {  ※i=カウンタ変数
          ※int i = 0; ⇒初期値　※i < 5; ⇒繰り返し条件　※i++ ⇒カウンタ変数の増減
            System.out.println(greeting);
        }
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
            System.out.println("Hello paiza");
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
        int count = scan.nextInt(); ※入力タブから最初の文字列を受け取る
        System.out.println(count);

        for (int i = 0; i < count; i++) {
            String name = scan.next(); ※入力タブから二つ目以降の文字列を受け取る
            System.out.println("Hello " + name);
        }
    }
}
```
