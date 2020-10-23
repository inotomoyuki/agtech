# Agtech (アグテック)  
### [Agiculture(農業)とTechnology(科学技術)の造語]

![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQWUkrryinpp3nwHELaek25_Ki7ywO0tCes6Q&usqp=CAU)


### Agtech URL **http://54.65.200.20**    
### GitHub **git clone    https//github.com/inotomoyuki/agtech.git**

# 詳細

### 生産者と、消費者をつなげる、チャットアプリ。  
### 農家の担い手も少なくなり、衰退していくようにみえる農業。しかし、AI,Iot等次世代テクノロジーをいかし、消費者とも繋がりを強くし、さらなる成長を目指す。これからの日本の基幹産業の一つとして、明るい未来を後世に伝えていく、期待を込めたアプリ。

![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS8D5t9Lk5WVrS0m18W4etUDEg4bDkC80LscA&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTv3Caaui4pAyUomuCxwIxYkWXjAaYGiaGkiw&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRmWP3JyyKNqEuJZtdj4bR5nZM6iN5wWmjqVw&usqp=CAU)

# 実装機能

![画像](https://i.gyazo.com/f566c7a768ee9d89e56f37d3bc109146.gif)
## ・ユーザー新規登録/ログイン  
### ・ニックネーム、アドレス、パスワードを入力。
・今回は、ヘッダーへログイン/新規登録のボタンを配置しました。
ログインすると、ログインボタンがユーザー名へ切り替わり、登録したユーザー名/投稿するボタンのような配置へなるようにします。

![画像](https://i.gyazo.com/d244df89370000aad05cc9283f2c1984.gif)
## ・ツイート一覧表示
・データを読み込む機能を実装しました。indexアクションを使用した、ページの新設。
## ・ツイート投稿
・ツイートの投稿機能を実装しました。
ストロングパラメーターなどセキュリティを考慮したformの実装。
## ・ツイート検索
・ツイート検索機能を実装しました。
whereやLIKE句などの概念の習得。
![画像](https://i.gyazo.com/f0cc213f2ec07c5cbf15cbc9ddab0246.gif)
## ・ツイート詳細表示
・ツイートの詳細表示機能を実装しました。
また、before_actionなどの概念の習得。
## ・ツイート編集
・ツイートの編集機能を実装しました。
すでにデータとして保存されているものを、上書き保存するような処理です。
## ・ツイート削除
・ツイートの削除機能を実装しました。
データベースからデータを削除する処理です。
## ・ツイートへコメント
・詳細画面からツイートに対して、コメントが書き込める機能を実装しました。
「コメント投稿フォーム」と「コメント表示欄」の実装。
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSr15zQ4KMi5BpfnPUCzGZOumra6px-9EOg0g&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQCraISnBf-ZLwdRBldWfN3InpQkChFezztMg&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSbUC8PXjIxVZ5twMLVal_xKR4rccQYyzr7eA&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSkORfo7Z5wZOfgGF2gYFOABXxZCAUGD6f5kg&usqp=CAU)

# 工夫したこと
### ・マイページ実装 
・ツイートの一覧画面には全ユーザーのツイートが表示されています。
一覧画面とは別に、現在ログイン中のユーザーの投稿のみが表示されているマイページを作成しました。
### ・投稿者本人のみに編集、削除許可
・ユーザー本人が投稿したツイートを編集・削除できます。
「ユーザーがログインしている」かつ「投稿したユーザーである投稿だけに許可」という実装しました。
### ・ツイートにコメント投稿
・ツイート詳細画面からツイートに対して、コメントが書き込めるようなコメント機能を実装しました。
「コメント投稿フォーム」と「コメント表示欄」を実装。
### ・投稿探索機能
・投稿が増えてきた際に「検索したテキストを含む投稿」を表示させられると便利なので、ツイートの検索機能を実装しました。
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTomHZWRVrgUqeD3liXWKEcAEQn2vzWXQOeHw&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS5xR5_i-efySL45hMEWO7ELK6QCRsOyrtZZw&usqp=CAU)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTomHZWRVrgUqeD3liXWKEcAEQn2vzWXQOeHw&usqp=CAU)
# 今後の課題
### ・決済サービスの追加。 
・当事者同士の決済サービスを実装。
### ・複数ページで利用する表示の一部をまとめる等コードの見た目
・部分テンプレートを使用します。
これを使用してコードの記述量を減らすことができると同時に、管理もしやすくする。
![画像](https://d1f5hsy4d47upe.cloudfront.net/35/35026fc91177fc4bd56f03a7b71d1beb_t.jpeg)
![画像](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSp9ywP5OTqPNAphElXbZUeI-7y1X3K5fYoLA&usqp=CAU)




