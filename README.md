<h1 align="center">HUIT RoadMap</h2>

## &#x1f4d8;このレポジトリについて

HUIT のメンバーが初心者向けに書いた、分野ごとの学習手順をまとめた記事です。  &#x1f973;
この「初心者」は、プログラミングは触ったことがないが、word や excel は講義などで
使っているレベルを想定しています。  
始めたばかりで何から始めていいのか分からないときなどにご活用ください。

## &#x270f;編集者へ  ```必ずお読みください```

### 記事を書くときのお願い

- これは「ロードマップ」で、初学者の方に向け学習の手順を示すことを目的としています。網羅的に学習を進められるよう、__ネットに存在する記事や本を多く活用し__、ロードマップ自体は簡潔にまとめるようお願い致します。
- 難しい単語を使わず平易な説明でお願いします。
- 文字だけではなく、図や画像があるのが望ましいです。
- 語尾はおまかせします。
- 基本雛形に沿って記述するようにお願い致します。新たな項目を書くことは大丈夫です。

### 編集方法

このレポジトリの main ブランチが [huitgroup.github.io/huit-roadmap](https://huitgroup.github.io/huit-roadmap) に反映されるようになっています。  
PR は別のブランチで作業してから main へ送ってください。  
原則として HUIT のメンバーがレビューをした後にマージします。

### 記事の追加方法

1. clone または fork をする
2. main から適当な名前のブランチを切る
3. base.md ( ホームページの場合は base_home.md )のひな型に沿って記事を書く。ファイルの場所は、例えば frontend の react の記事なら
   frontend/react.md のようにする。(各カテゴリーのトップページは index.md です)
5.  _data/authors.ymlに自分の名前、アイコン、bio、linkを追加し、作成したページの初めに筆者を記載する。
6. 変更を commit して push、その後 PR を送る。

### ディレクトリ構成

各分野のまとめページは \<分野名\>/index.md</br>
記事の保存場所は \<分野名\>/\<技術名\>.md  
画像などの静的ファイルは assets/\<カテゴリー\>/\<技術名\>/sample.png
