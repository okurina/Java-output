# 配列
```
public class Main {
    public static void main(String[] args) {
        String player_1 = "勇者";
        String player_2 = "魔法使い";
        
        String[] team = {"戦士", "忍者", player_1}; //文字列のみ可能 数値を使いするとエラーになる
    
        System.out.println(team[0]); // 「戦士」配列のインデックスを指定
        System.out.println(team[1]); // 「忍者」
        System.out.println(team[2]); // 「勇者」
    }
}
```
