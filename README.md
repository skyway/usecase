# 使い方

- GitHub Pagesで動かす時
  - https://skyway.github.io/usecase/ にアクセス
- ローカルで動かす時
  - `git checkout local-video` でブランチ切り替え
  - `bundle exec jekyll serve` でサーバ起動
  - http://localhost:4000 にアクセス

# ブランチ

```
            update               update
            content              content
     master ---*----*---------------*----*----------->
                     \  then              \  then
                      v merge.             v merge.
local-video -----------*---------*----------*-------->
                              update
                              submodule
```
