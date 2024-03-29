# r-multivariate-analysis

## Rで多変量解析を実行する
Rで多変量解析を行ったときのスクリプトをまとめました。
分析の流れ
1. 調査データを読み込み、分析に必要な部分を抽出する
2. 調査データの相関行列を求め、固有値を算出する
3. スクリープロットを描画し、因子数を決定する
4. 因子の特徴を抽出しやすくするために、因子軸の回転を行う。
5. 結果を元に、因子に名前をつけていく

今回利用した調査データは、世代ごとの価値観に関するアンケート調査(https://www.asmarq.co.jp/examine/2703katikan.html) を利用しました。
調査データとして利用するにあたり、調査データを編集して調査に必要な項目のみを抽出しました。

今回の調査より、Rで多変量解析を行う際の基礎知識、因子分析の基本について入門することができました。
次回以降、さらに発展させていくにあたり、インターネットの情報だけではなく、実際に書籍等の体系化されたテキストを利用して知識を取り入れていきたいと思います。
