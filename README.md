# windows_team

## 1.git add
git add は、作業ディレクトリ内の変更をステージングエリアに追加するコマンド

## 2.git commit
git addの後に実行。ローカルに保管するコマンド。

## 4.git commit --amend

## 5.git branch fix/42
fix/42という名前でブランチを作成します。

	git branch <branchname>


## 6.git checkout -b fix/42;git commit
checkout -bは、新規ブランチを作り、それをカレントブランチにする。
同時に、コミットする。

## 7. git checkout -b fix/42
	git checkoutは、作業対象のブランチの切り替えを行う
	本コマンドではブランチ fix/42をチェックアウトする

## 8. git reset --hard master

## 12. git checkout
ブランチを切り替えます。

	git checkout <branch>

## 13. git merge --ff-only
Refuse to merge and exit with a non-zero status unless the current HEAD is already up-to-date or the merge can be resolved as a fast-forward.

FFとは？
⇒　ファーストフォワードの略

◆ファーストフォワードである
コミットAの歴史がコミットBにすべて含まれていること

◆ファーストフォワードでない
コミットAの歴史がコミットBにすべて含まれていない　(ブランチが分かれている状況)

-ffをつけると、マージコミットは作らず、ブランチの参照先のみを更新する


## 14. git merge --no-ff
指定したブランチを現在のブランチにマージしますが、その際に常に (たとえそれが「早送り」可能であっても) マージコミットを作成してマージします。

## 18. git pull --rebase
--rebase は git pull コマンドのオプションです。
git pull は fetch + merge ですが、--rebase オプションをつけると fetch + rebaseとして実行します。

	git pull --rebase

## 19. git push
ローカルの更新を登録

## 20. git cherry pick
git cherry pick <id>は、ブランチにidで指定したコミットを適用します。

## その他1．git status
変更されたファイルの一覧を表示

## その他2. git reflog
ローカルリポジトリの reflog を表示するコマンドです。

## その他3. git add -p
インタラクティブなステージングセッションを開始します。

## その他4. git log
引数なしの場合、リポジトリのコミットを新しい順で表示します。
各コミットの、コミットID、作者の名前、メールアドレス、コミット日時、コミットメッセージが得られる。

## その他5. git stash
ある作業が中途半端な状態になっているときに、ブランチを切り替えてちょっとだけ別の作業をしたいとき、
中途半端な状態をコミットしたくないので、コミットせずに後でその状態から作業を再開したいときに使うコマンドです。

## その他6. git tag
重要なポイントにしるしをつけることができます。
一般にこの機能はリリースポイントとして使われます。

## その他7．git mergetool
マージを助けるツールが立ち上がる。
『merge前の状態』、『mergeしたい差分が生まれる直前の状態』、『mergeしたい差分』が表示される。

## その他8. git reset -p
順に対象を選びリセットを行う
