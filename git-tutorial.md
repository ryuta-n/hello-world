# gitコマンド一覧

- git init
<br>
 gitの初期化・設定開始
- git status
<br>
 ワークツリーのステータスを表示
- git config 
<br>
 設定周りの確認・変更
- git log
<br>
 ログを表示
<br>
 -- onelineでコミットメッセージの1行のみの一覧表示
- git diff
<br>
 ファイルの差分を表示
- git add
<br>
 ステージングエリアに追加
- git commit 
<br>
 コミットの実行
- git commit --amend --no-edit
<br>
 コミットの修正
- git checkout
<br>
 削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）
- git reset
<br>
 コミットのリセット
- git revert
<br>
 「コミットの変更を打ち消す」コミット
- git rm
<br>
 ファイルとindex情報の削除
- git clone
<br>
 レポジトリをコピー
- git pull
<br>
 リモートレポジトリの同期	
- git push
<br>
 変更をアップロードする
- git request-pull
<br>
 プルリクエスト：変更依頼
- git remote
<br>
 リモートレポジトリの設定
- git branch
<br>
 ブランチの作成
- git checkout
<br>
 ブランチの切り替え
- git merge
<br>
 ブランチの統合
- git clone
<br>
 レポジトリをコピー
- git push
<br>
 変更をアップロードする

# githubフローの説明

**githubフロー**とは、mainとは別にブランチを作成して、ブランチ上で作成することで、
<br>
 mainのデータを損失することなく編集することができ、mainでも更新したいときに
<br>
 編集者の任意のタイミングで更新することも可能となる、ブランチベースのワークフローである。 