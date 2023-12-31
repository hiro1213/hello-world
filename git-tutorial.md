# hello-world
＜gitの機能についての説明＞ 

①gitについての概要
gitはソースコード管理を行うために使われるシステムのことを指す。これを用いることで他人と共同作業を行うことができる。

②レポジトリについて
レポジトリとはgitが管理するプロジェクトのフォルダのことである。ローカルレポジトリとローカルレポジトリの２種類がある。
簡単に説明するとローカルリポジトリは自分のパソコン内にあるリポジトリであり、リモートレポジトリはネットワーク上にあるリポジトリのことをいう。
複数人で同期をする際には、ローカルとリモートを使い分け、リモートリポジトリに同期する。
このようにリモートリポジトリとローカルのリポジトリの同期によって、それぞれのリポジトリを共有し作業を進めていける。

③ブランチについて
ブランチを用いて作業を枝分かれさせることができる。つまりは共同作業・並行作業が可能にさせるのがブランチの機能である。
ソフトウェアの開発では、ひとつのプロジェクトに対して複数のメンバーが同時に機能追加を行うことがよくある。
その際に、ブランチを用いて同じリポジトリ内でそれぞれの開発を同時に進める。

④コミットとプッシュについて
コミットはファイル作成・変更・削除の記録を行うものであり、リポジトリに保存される。
プッシュはファイルの追加や変更の履歴をリモートリポジトリにアップロードするための操作のことをいう。

⑤プルリクエストについて
プルリクエストとはローカルリポジトリでの変更を他の開発者に通知する機能のことである。
ソースコードの変更箇所がこれによりわかる。


## ＜コマンド一覧＞

- ### git init
   - gitの初期化・設定開始
- ### git status
   - ワークツリーのステータスを表示
- ### git config 
   - 設定周りの確認・変更
- ### git log
   - ログを表示
    -- onelineでコミットメッセージの1行のみの一覧表示
- ### git diff
   - ファイルの差分を表示
- ### git add
   - ステージングエリアに追加
- ### git commit 
   - コミットの実行
- ### git commit --amend --no-edit
   - コミットの修正
- ### git checkout
   - 削除されたファイルを復旧や過去コミットの復元など（元に戻す変更がstaging area/index内にある場合）
- ### git reset
   - コミットのリセット
- ### git revert
   - 「コミットの変更を打ち消す」コミット
- ### git rm
   - ファイルとindex情報の削除
- ### git clone
   - レポジトリをコピー
- ### git pull
   - リモートレポジトリの同期	
- ### git push
   - 変更をアップロードする
- ### git request-pull
   - プルリクエスト：変更依頼
- ### git remote
   - リモートレポジトリの設定
- ### git branch
   - ブランチの作成
- ### git checkout
   - ブランチの切り替え
- ### git merge
   - ブランチの統合
- ### git clone
   - レポジトリをコピー
- ### git push
   - 変更をアップロードする

## git flowについて

GitHubフローは、シンプルでわかりやすいブランチベースのワークフローです。
GitHubフローの目的は、開発フローをシンプルにし、mainブランチを常にデプロイ可能な状態に保つことです。これにより、開発者が効率的に働き、プロジェクトがスムーズに進行します。
