---
title: "hugoを使ったブログ作成"
date: 2021-02-06T21:00:00+09:00
---
## 経緯

先日同僚の方に[hugo](https://gohugo.io/)で簡単なブログの作成と公開の方法を紹介してもらいました。

せっかくなので作成

## 手順
1. [Quick Start](https://gohugo.io/getting-started/quick-start/)に沿ってローカル環境(Mac)を構築
2. このブログ投稿をマークダウン形式で作成
3. `config.toml`ファイルに`publishDir = 'docs'`を追加
4. `hugo`コマンドを実行し、静的ファイルを出力
5. リモートにプッシュ
6. GithubのSettings>Pages>Sourceからデプロイするブランチを選択
