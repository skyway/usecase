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

#### 4. submodule `usecase-videos`のディレクトリに入り、最新のコンテンツを`git pull`する

```
$ cd usecase-videos
$ git checkout master
$ git pull origin master
```

#### 4. submodule `usecase-videos`のディレクトリから出て、submoduleの更新を`git push`する

```
$ cd ..
$ git add usecase-videos
$ git commit -m 'Update submodule usecase-videos'
$ git push
```
