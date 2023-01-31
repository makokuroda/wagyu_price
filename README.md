# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
### リモートリポジトリ
ネット上に配置して複数人で共有するためのリポジトリ。
### ローカルリポジトリ
開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。



## プッシュとマージの違いは何でしょうか？
### プッシュ
ローカルリポジトリの内容をリモートリポジトリに反映させる。

### マージ
ローカルで現在いるブランチに指定したブランチの変更履歴を取り込むことができる。


## コミットとプッシュの違い
### コミット
ローカルリポジトリの変更内容の保存

### プッシュ
ローカルリポジトリの内容をリモートリポジトリに反映

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
編集内容をより正確に表すように書く



## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージするときは、ローカルでマージした後は、masterブランチにプッシュするだけでリモートに更新されるため、コードレビューされずにmasterに反映される。

- プルリクエストの場合は、プッシュしてからプルリクエストを作成し、コードレビューをしてからmasterに反映される。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先にマージされた変更内容を取り込む
- 後にマージしようとしている変更内容を取り込む
- どちらの変更内容も取り込むのどれかを選択。意図が読み取れない処理とぶつかったら、そのソースコードを書いた人と相談しながら作業を進めるようにする
