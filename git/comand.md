構造
workspace => staging => localRepository => RemoteRepository

workspace => staging
git add .
git add ファイル名


staging => localRepository
git commit -m コメント



=================================
確認
=================================
git log    //gitのログを確認する
git status  //ローカルの変更を確認する

=================================
ブランチ
=================================
ブランチで
本番環境とは別の世界線を作る
いろいろ書き換えることができる

もしダメだった場合
チェックアウトで元に戻すことができる

git branch  　　　　　　　//現在のブランチを表示する
git branch ブランチ名    //ブランチを作成 (作成したブランチには移動しない)
git branch -d ブランチ名 //ブランチを削除

=================================
チェックアウト
=================================
ブランチを移動して、その最終点と同じようにする

git checkout ブランチ名　//ブランチ名の最終点に切り替える
git checkout -b ブランチ名　//ブランチ名に切り替えてその状態に戻る

=================================
マージ
=================================
ブランチを一つにまとめる



# 変更、削除したファイルがついてくる
git rest



=================================
　ブランチ
=================================

# ブランチの確認
git branch

# ブランチの作成
git branch <ブランチ名>

# ブランチの削除
git branch -D <ブランチ名>

# ブランチの作成、切り替え
git checkout -b <ブランチ名>

# ブランチの切り替え
git checkout　<ブランチ名>


=================================
　リモートレポジトリ
=================================

# 確認
git remote -v

# 追加
git remote add　<名前> <追加したいリポジトリ>

# 削除
git remote rm <名前>

