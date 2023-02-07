# アプリケーション名

famous-product

# アプリケーション概要

全国の県の名物を調べることができるアプリを作成することで、旅行先の提案に役立てたい。

# URL

https://famous-product-38773.onrender.com

# テスト用アカウント

・Basic認証パスワード: 2222<br>
・Basic認証ID: admin<br>
・メールアドレス: test@string.com<br>
・パスワード: abcxy10702

# 利用方法

# 名物投稿

1.トップページ（一覧ページ）のヘッダーからユーザー新規登録を行う。<br>
2.新規投稿ボタンから、名物の内容(タイトル、メッセージ、画像)を入力し投稿する。

# ユーザーの好きな名物を共有

1.新規登録時に好きな名物を登録することで、好きな名物を共有することができる。

# コメント投稿

1.投稿した内容に関してコメントを送ることができる。

# アプリケーションを作成した背景

私は旅行が好きなので、全国の旅行が趣味の方々にその県の有名な名物を知ってもらうことによって、今まで
行ったことがない県に興味を持ってもらい、たくさんの県の良さを知ってほしいために作成した。

# 洗い出した要件

https://docs.google.com/spreadsheets/d/1rmP90I82xs5cvAsJ6PkkqJbLT9q5nkkwoIGRd-8G5cU/edit#gid=1148367473

# 実装した機能についての画像やGIFおよびその説明

投稿についてコメントできる機能を実装した。

# 実施予定の機能

現在１つの県しか登録できていない状態なので、47の都道府県全てを登録できるようにしたい。

# データベース設計
  
  https://github.com/kenji198834/application_submit/blob/main/test.png

# 画面遷移図

  https://github.com/kenji198834/application_submit/blob/main/text.png
# 開発環境

・フロントエンド<br>
・テスト<br>
・テキストエディタ

# ローカルでの動作方法

以下のコマンドを順に実行<br>
% git clone https://github.com/kenji198834/famous-product<br>
% cd projects<br>
% cd famous-product<br>
% bundle install
% yarn install

# 工夫したポイント
 
 新規登録時に好きな名物を登録することによってお互いの好きな名物を共有し合うことができ、ただ単に名物を投稿する
 だけではなく、チャットアプリの役目も果たすようにした。
 ユーザーの一覧画面に商品一覧画面の表示を移し替えることで、ログインした時に一番初めにユーザーの一覧画面に遷移
 ようにした。