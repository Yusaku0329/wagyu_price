# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？？

- リモート：githubに保存してあり、他の人もアクセスできるリポジトリ
- ローカル：各作業者のPCのストレージ内にあるリポジトリ
## githubの他にどんなリモートリポジトリがありますか？
- Bitbucket,GitLab,CloudForge,tracpathなど

## プッシュとマージの違いは何でしょうか？

- プッシュとマージの違いは異なるブランチの変更内容を取り込むかどうか

## pushもmergeもどちらも「ブランチの変更内容を取り込む」という点では一緒ですね。
## 対象のブランチにはどんな差があるでしょう？

- pushでの対象ブランチはローカルで作業したブランチAからリモートのブランチAに取り込ませること
- margeでの対象ブランチはブランチAから切り離して作業をしたブランチBの内容をブランチAに取り込ませること
- つまり、対象ブランチに分岐した履歴があるかどうかの差があります

## コミットとプッシュの違い

- リモートに変更内容を反映させるか

## リモートに変更内容を反映するのはどちらですか？

- プッシュになります

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- 変更内容を明確にわかりやすく

## プレフィックスとは？
- コミットメッセージの先頭に特定の文字をつけること
## プレフィックスの例
- add:ちょっとしたコードやファイルの追加
- change:ちょっとしたファイル・コードの変更
- feat：ユーザーが利用する機能の追加
- style:機能部分を変更しない、コードの見た目の変化

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- 異なるブランチの変更内容を取り込む際に、他の人が確認できる状態を挟むかどうか

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

- 先にマージされたものを取り込む、後にマージされたものを取り込む、どっちも取り込む、の3つがあるがぶつかった個所の担当の人と相談して対処する