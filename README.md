### Atcoder用のディレクトリ・ファイル作成
①「user_info.py」を作成し、自分のユーザー情報と言語IDを設定する。

    USERNAME='hogehoge'
    PASSWORD='hogehoge'

    # 言語ID
    CPP_ID = 3023　# python


②コンソールで以下のコマンドを実行（ex.ABC093）。


    python mkdir.py abc 086
以下のディレクトリとファイルが作成される。

    .
    └── ABC
        └── 093
            ├── A.py
            ├── B.py
            ├── C.py
            └── D.py



また、問題ページの入力パターンから入力を受け取るソースが自動生成される（入力パターンがシンプルな場合のみ）。

    import sys
    input = sys.stdin.readline
    s = input()


---

### テスト実施〜提出〜ジャッジ結果の取得
①コンソールで以下のコマンドを実行（ex.「/ABC/093/C.py」を提出したい場合）。


    python testnsub.py abc 093 c
    
②コンソールにテスト結果が出力され、提出するかどうかを標準入力で問われる。


    [提出ファイル]
    /hogehoge/ABC/093/C.py
    ************************************************************
    [入力例 1]
    2 5 4
    [出力例 1]
    2
    [あなたの出力]
    2
    ************************************************************
    [入力例 2]
    2 6 3
    [出力例 2]
    5
    [あなたの出力]
    5
    ************************************************************
    [入力例 3]
    31 41 5
    [出力例 3]
    23
    [あなたの出力]
    23
    ************************************************************
    [3/3]
    提出しますか？(y/n)

③提出したくない場合は「n」を入力し、リターン。処理終了します。
提出したい場合は「y」を入力し、リターン。提出後、ジャッジ結果を取得。

    y
    提出完了しました.
    結果を取得します.
    　　　　　　　 　.i||||||||||||||||||||||||||||||i.　　　　　　　　　　　　　..ii||||||||||!!!!||||||||||||||||||||||||| 
    　　　　　　　　.i| !||||||||||||||||||||||||||||||i. 　　　　　　　　 　..ii|||||||||||||!　ii||||||||||||||||||||||||||| 
    　　　　　　　 i|| 　!||||||||||||||||||||||||||||||i. 　　　　　　　 .i||||||||||||||||!　 i||||||||||||||||||||||||||||| 
    　　　　　 　 i|| 　　.!||||||||||||||||||||||||||||||i.　　　　　　.ii||||||||||||||||!! 　 .||||||||||||||||||||||||||||| 
    　　　　　　i|||　　　　!||||||||||||||||||||||||||||||i.　　 　　.i|||||||||||||||||||i　　　!||||||||||||||||||||||||||| 
    　　　　　 i|||| 　　　 　!||||||||||||||||||||||||||||||i.　　　.||||||||||||||||||||||i.　　　　!||||||||||||||||||||||| 
    　　　　 i||||||||.　　　　　!||||||||||||||||||||||||||||||i.　　 |||||||||||||||||||||||||ii.. 
    　　　 i||||||||||||i. 　　　　 !||||||||||||||||||||||||||||||i.　　|||||||||||||||||||||||||||||ii.. 
    　　. i||||||||||||||||||i 　　　　!||||||||||||||||||||||||||||||i. 　 !||||||||||||||||||||||||||||||||iiii.. 
    　　.||||||||||||||||||||||||||||||||. .!||||||||||||||||||||||||||||||i.　　 ||||||||||||||||||||||||||||||||||||||||||||||||||||||| 
    　　||||||||||||||||||||||||||||||||| 　!||||||||||||||||||||||||||||||i.　　!||||||||||||||||||||||||||||||||||||||||||||||||||||| 
    　　.||||||||||||||||||||||||||||||||　　!||||||||||||||||||||||||||||||i. 　　!|||||||||||||||||||||||||||||||||||||||||||||||||| 
    　　. !|||||||||||||||||||||||||||||| 　　!||||||||||||||||||||||||||||||i. 　　　.!||||||||||||||||||||||||||||||||||||||||||||| 
    　　　 !||||||||||||||||||||||||||||　　　!||||||||||||||||||||||||||||||i. 　　　　 .!|||||||||||||||||||||||||||||||||||||||| 
    　　　　　.!||||||||||||||||||||||| 　　　.!||||||||||||||||||||||||||||||i. 　　　　　　　.!!|||||||||||||||||||||||||||||| 
# atcoder_tools
# atcoder_tools