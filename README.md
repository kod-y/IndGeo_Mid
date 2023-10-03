# 2023年秋冬学期 産業地理学 中間レポート
Created by 2120274m

このリポジトリは2023年秋冬学期産業地理学の中間レポートを再現するためのコードを格納したリポジトリです。

## ディレクトリ構成
本リポジトリは次のような構成を取っています：
- `notebooks`
    - `main.ipynb`: 分析を行っているノートブックです
    - `test.ipynb`: 分析のテストを行っているノートブックです
- `reports`
    - `notebooks`の成果物が格納されています
    - 今回は提出したFigureや`.csv`が格納されています
        - 実際に提出したファイルはこれらのファイルを名前変更だけ行ったものです
- （`data`）:
    - 前処理されたデータが格納されています
    - 二次配布を防ぐためフォルダごと`git ignore`されています


## 再現方法
1. `git clone`
2. `pip install -r requirements.txt`
3. `main.ipynb`を上から順に実行