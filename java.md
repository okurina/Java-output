# 11/3
* クラス部分、メソッド部分、処理部分という構造
* 基本形  
public class Main {  
    public static void main(String[] args) {  
        System.out.println("Hello world");  
    }  
}  
* データの出力
  System.out.println()  =「()の中身(引数)を出力せよ」という「命令」のメソッド
* 文の終わりにはセミコロンを必ずつけること
* 数値は""で囲まない、記号は半角で入力する
  ex) System.out.println(3 + 2)
* 演算子はRubyと同様

# 11/5
* 変数を定義するには、①変数に入れる値のデータ型を指定する　②変数の名前を決める  
　ex) int number; String name; ※Sは大文字  
*「変数名 = 値」で代入
* System.out.println()の()に変数をいれると値を取り出す  
　ex) System.out.println(number);  
* 変数定義と同時に値を代入することを変数の初期化と呼ぶ  
　ex)int number = 3;  
     String text = "Hello World";  
* 数値が入った変数なら、数値と同様に計算が可能。数値と変数の計算も、変数同士の計算もできる。  
  ex) int number1 = 10;  
      System.out.println(number1 + 3);  ⇒13  
      int number2 = 5;  
      System.out.println(number1 + number2);　⇒15  
* 文字の連結も可能。　※変数にダブルクォーテーションを付けない  
 ex) String greeting = "こんにちは";  
     System.out.println(greeting + "佐藤さん");　⇒こんにちは佐藤さん  
     String name = "鈴木さん";  
     System.out.println(greeting + name);  ⇒こんにちは鈴木さん
* 変数の更新  
 ex) String name = "Sato";  
     System.out.println(name); ⇒Sato  
     name = "Suzuki";   ※更新時はデータ型をつけない。変数名の前にデータ型をつけると変数を定義しようとするが、同じ処理内で同一名の変数を定義できないため  
     System.out.println(name); ⇒Suzuki
* 自己代入　※省略形はRubyとほぼ同様「1を足す= x++;」「1を引く= x--;」  
 ex) int x =3;  
     System.out.println(x); ⇒3  
     x = x + 2  
     System.out.println(x); ⇒5

# 11/6
＜変数名のつけ方＞
- 1 文字目 ：アルファベット、アンダーバー
- 2 文字目以降 ：アルファベット、アンダーバー、数字
- 大文字と小文字を区別する
- 「userName」のように2語以上の変数名を使うときは、単語の始めを大文字にして区切る
- println などの命令をあらわすキーワードは使用できない
- 慣習として、日本語(全角)で書かない

# 11/7
* double型：少数を扱う
* boolean型：真偽値のデータ型　※true, falseにはダブルクォーテーションは付けない
* 比較演算子：値を比較するための記号
　ex)「x == y」はxとyが同じかどうかを比較し、同じであればtrue、違っていればfalse。また「x != y」はその逆
