# how-to-github
to learn Git

## Command

### git remote -v
- local-repositoryがどのremote-repositoryと繋がっているかを確認

### git branch
- branch確認
- <branch name>の指定でbranchを作成
- -dオプション <branch name>で削除

### git checkout <branch name>
- 指定したbranchに移動
- -bオプションでブランチを作成し、移動


### git add <target>
- ターゲットとなるファイル・ディレクトリをstaging areaに追加

### git commit -m <messeage>
- ローカルリポジトリにコミット
- -mオプションでそのままコミットメッセージを書ける

### git merge 
- 今いるブランチにマージする


### git log
- コミット履歴を確認
- --onelineオプション
- --graphオプション
- -- <file name>
- --followオプション　ファイル名の変更も考慮

### git pull <remote repository> <branch name>
- fetch・mergeという処理をまとめて行っている

### git push <remote repository> <branch name>
- github上でpull reequestpull reequest

### git restore <file>
- working dirでの作業をキャンセル
- --staged <file>でステージングエリアへのaddをキャンセル

### git mv <file name1> <file name2> 
- 1->2へ名前を変更
- 変更を自動的にaddして管理してくれる
- linuxの通常のコマンドであるmvを使った場合は、git add -A で変更をstaging areaに追加する必要がある。

### git rm <file name>
- fileを削除し、gitで管理
- trackされてないファイルとStarging areaに作業内容があるファイルは削除できない

### git show <commit ID>
- コミット情報の表示

## .gitignore
- Gitで管理しないファイル、フォルダを定義
- https://github.com/github/gitignore


git