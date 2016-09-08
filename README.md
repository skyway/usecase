
## gh-pages

https://skyway.github.io/usecase/

## 使い方

- ローカルで動かす時
  - _config.ymlを `url: http://localhost:4000` に修正
  - `bundle exec jekyll serve` でサーバ起動
  - http://localhost:4000 にアクセス
- Pushする時
  - _config.ymlを `https://skyway.github.io/usecase` に修正
  - `bundle exec jekyll build` でcommit用のページ生成
  - あとはいつものaddして、commitして、push
