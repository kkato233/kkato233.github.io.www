## 目的

https://kkato233.github.io で公開している github の プロジェクトについて
GitHub Pages に公開される前に動作確認するための環境。

## github ページの 編集確認用環境

サブモジュールを含むソースのチェックアウト

```
git clone --recursive https://github.com/chaconinc/MainProject
```

または clone のあとで
```
git submodule init
git submodule update
```
を行います。

sub module の使い方については

https://git-scm.com/book/ja/v2/Git-のさまざまなツール-サブモジュール

を参照。

## 開発方法

Visual Studio で開いて ブラウザで表示。
または、
```
cd src
dotnet run
```

http://localhost:5002/
http://localhost:5002/ken_all_mdb/index.html

を開く


