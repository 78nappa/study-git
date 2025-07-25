<<<<<<< Updated upstream
1. git init  ローカルリポジトリを初期化。これにより、カレントディレクトリが Git の管理下に入る。
=======
###  リポジトリ新規作成〜ファイル登録
1. githubでリポジトリを作成
2. git init  
ローカルリポジトリを初期化。これにより、カレントディレクトリが Git の管理下に入る
3. git add ファイル名
   git commit -m "コメント"
   ファイルをローカルリポジトリに登録
4. git remote add origin 「 https://github.com/ユーザーID/push_test.git 」  
「」内はリポジトリのURL  
リモートリポジトリを新規追加
5. git push  
ファイルをリモートリポジトリに登録

### リポジトリのファイル削除
1. git rm ファイル名
2. git commit -m "コメント"
3. git push
>>>>>>> Stashed changes

### ブランチ作成〜ブランチにPush
1. git branch ブランチ名
2. git switch ブランチ名
   作成したブランチに移動
3. add / commit / pushを行う

#### エラー
* dquote>
  コメントのダブルクォーテーションが抜けた  
  ＞＞「 " 」を打ってEnter


