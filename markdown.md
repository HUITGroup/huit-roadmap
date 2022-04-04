## マークダウンで記事を書くための環境構築

まだ環境がない人向けに快適にマークダウンを書く環境の構築方法を書いていきます！
最低限の内容なので、独自に便利な機能を探して拡張してください。

### 実現する機能

- マークダウン形式の記事を VSCode でリアルタイのプレビューをしながら書ける

### 準備

VsCode をダウンロードして、以下の拡張機能を DL する。

- Markdown All in One (キーボードショートカットや補完などを追加してくれる)

### 使い方

ctrl + k -> v のショートカットを打つと、エディターが 2 分割になって、片方はリアルタイムのプレビューになる。

![イメージ図](assets/root/markdown/split_preview.png)

### ローカルでテーマのプレビューをする

ここから先は余裕がある方向けです。
github pages に表示される内容のプレビューをするために、docker-compose を使います。

docker インストール方法

- [windows](https://makise-lab.com/dockerdesktop_1/)
- [mac (インストール部分だけで問題ないです)](https://qiita.com/gahoh/items/92217e0a887bb81e3155)

インストール後はルートで`docker-compose up`のコマンドを実行するだけです。localhost:4000 から見れるようになります。
