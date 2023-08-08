**:warning: 本リポジトリは過去アーカイブ版です。最新版は [:github: coderdojo-japan/coderdojo.jp](https://github.com/coderdojo-japan/coderdojo.jp) からご確認いただけます。**

[coderdojo.jp](http://coderdojo.jp/)で公開されているウェブサイトの中身です。

[GitHub Pages](https://pages.github.com/)と[Jekyll](http://jekyllrb.com/) (Gemの名前は'github-pages') を使って公開されています。

## 必要なソフトウェア

- [Ruby](https://www.ruby-lang.org/) (1.9.3以上)
- [Bundler](http://bundler.io/)

参考: [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/)

## セットアップの手順

1. [Ruby](https://www.ruby-lang.org/) (1.9.3以上) をインストールする
2. `$ gem install bundler` で Bundler をインストールする
3. 本リポジトリを clone する
4. 本リポジトリのトップディレクトリで `$ bundle install` を実行する
5. `$ bundle exec jekyll serve -w` でローカルサーバを立ち上げる
6. ブラウザから http://localhost:4000 にアクセスする
7. CoderDojo Japan のページが表示されていれば OK :)

詳細: [Using Jekyll with Pages](https://help.github.com/articles/using-jekyll-with-pages/)

## 編集の手順

1. `$ bundle exec jekyll serve -w` でローカルサーバを立ち上げる
2. `index.md` を Markdown で編集する
3. ブラウザで変更結果を確認する
4. 問題なさそうであれば Pull Request を送る

参考: [Using pull requests](https://help.github.com/articles/using-pull-requests/)


## 他のリポジトリ 一覧

- :octocat: https://github.com/coderdojo-japan (CoderDojo Japan)
