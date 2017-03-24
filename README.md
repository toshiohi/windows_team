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

## 14. git merge --no-ff
指定したブランチを現在のブランチにマージしますが、その際に常に (たとえそれが「早送り」可能であっても) マージコミットを作成してマージします。
