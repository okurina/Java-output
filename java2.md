# コメント  
* // : 行の先頭・うしろ、コメントアウト 
* /* ~ */：複数行にまたがる

# データの受け取り(入力タブ)
```
import java.util.*;  #データを受け取る機能をプログラムの中で扱えるようにする  
  
public class Main {  
    public static void main(String[] args) {  
        Scanner scan = new Scanner(System.in);  #変数scanにデータを受け取る機能を割り当てる  
        String text = scan.next();  #nextという入力データを読み込むメソッドを呼び出す  
        System.out.println(text);  
    }  
}
``` 

# 整数データの受け取り
```
import java.util.*;  #データを受け取る機能をプログラムの中で扱えるようにする  
  
public class Main {  
    public static void main(String[] args) {  
        Scanner scan = new Scanner(System.in);  #変数scanにデータを受け取る機能を割り当てる  
        int number = scan.nextInt();  #nextという入力データを読み込むメソッドを呼び出す ※Iは大文字  
        System.out.println(number * 10);  ※計算も可能
        System.out.println("おこづかい" + number + "円"); ※文字列と連結  
    }  
}
``` 

# if 条件分岐
```
import java.util.*;  

public class Main {  
    public static void main(String[] args) {  
        Scanner scan = new Scanner(System.in);  
        int number = scan.nextInt();  
        System.out.println(number);  

        if (number == 10) {  ※関係演算子  
            System.out.println("Welcome");
        } elsif (number > 10) {
            System.out.println("Goodmorning");
        } else {
            System.out.println("Goodbye"); 
        }  ※セミコロン必要なし  
    }  
}
```
