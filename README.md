
# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

  * リモートリポジトリ

    * ネット上に配置して複数人で共有するためのリポジトリ。（個人開発用にも使える）
    
  * ローカルリポジトリ

    * 開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。

## プッシュとマージの違いは何でしょうか？

    プッシュはローカルリポジトリの変更内容をリモートリポジトリに反映させるコマンドであり
    マージはブランチで変更された二つの内容を一つにするコマンド

## コミットとプッシュの違い
    コミットはローカルリポジトリに変更を反映するコマンドであり
    プッシュはリモートリポジトリに変更を反映するコマンド

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

    一目で変更内容がわかるようなものにする

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

    ローカルでマージするフローは、ローカルで作業ブランチをmainにマージしてプッシュしていたのに対して、プルリクエストでマージするフローは、変更内容をマージをしてくださいという依頼を行うこと
    
## コンフリクトを起こしてしまった場合、どう対処すべきですか？
    1.先にマージされた変更内容を取り込む
    2.後にマージしようとしている変更内容を取り込む
    3.どちらの変更内容も取り込む
