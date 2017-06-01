# ローカルで動かす方法

#### 1. `local-video`ブランチに切り替える

```
$ git checkout local-video
```

#### 2. サーバ起動

```
bundle exec jekyll serve
```

#### 3. ブラウザで http://localhost:4000 にアクセス

# ローカルの動画ファイルの更新方法

#### 1. GHEから`usecase-videos`レポジトリを`git clone` or `git pull`する

#### 2. 動画ファイルを追加し、`git push`する

#### 3. `local-video`ブランチに切り替える

```
$ git checkout local-video
```

#### 4. submodule `usecase-video`のディレクトリに入り、最新のコンテンツを`git pull`する

```
$ cd usecase-videos
$ cd checkout master
$ git pull origin master
```

#### 4. submodule `usecase-video`のディレクトリから出て、submoduleの更新を`git push`する

```
$ cd ..
$ git add usecase-video
$ git commit -m 'Update submodule usecase-videos'
$ git push
```

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
