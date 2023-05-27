# リポジトリのテストのための、やつ！
今日2023/05/27、友達のPCにGitHubを連携させようとしたら、エラーの連続で結局失敗に終わった。1時間近くゴニョゴニョやっていて、それでも駄目だった。本当に自分が情けないと感じた。
ということで、今回から捨てる前提のリポジトリをたくさん作って、どのようなときにエラーが出るのか、そして、成功するための秘訣？を自分で学習していこうと思う。
## Git Initの場所を間違えたとき
間違ってGit Initのディレクトリを間違えてしまった（GitHubにはまだ手を出していない）とき、
```git -rf .git/```
でGitの管理をやめる事ができる、と、**Google検索**で一番初めに出てくる。
### しかし、
Windowsではこのコマンドが実行できない。だから私は失敗した、ということ、多分。

Windowsだと、
```Remove-Item -Recurse -Force .git/```
でできる、と、**ChatGPT**が答えてくれた。まじかよ～。Macだけ使うのは危ないわね。