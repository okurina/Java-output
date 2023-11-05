# 11/3
* クラス部分、メソッド部分、処理部分という構造
* データの出力
  System.out.println()  =「()の中身を出力（表示）せよ」という「命令」
* 文の終わりにはセミコロンを必ずつけること
* //　コメントアウト
* 数値は""で囲まない、記号は半角で入力する
  System.out.println(3 + 2)
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
