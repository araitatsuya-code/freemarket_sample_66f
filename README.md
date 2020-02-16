# freemarket_sample_66f

![freemarket_sample_TOP](https://user-images.githubusercontent.com/58362112/74603822-d98a7f80-50fa-11ea-99b1-85245fbc052f.jpg)


プログラミングスクールTECH::EXPERTの最終課題で某フリーマーケットサービスのクローンサイトを作成しました。約1ヶ月間、４人チームでアジャイル開発を行いました。

# リンク
http://13.114.137.80/

Basic認証をかけています。ご覧の際は以下のIDとPassを入力してください。

* Basic認証
  * ID: admin
  * Pass: 2222

* テスト用アカウント等
  * 購入者用
    * メールアドレス: tech-exp@com
    * パスワード: 13131313
  * 購入用カード情報（pay.jpテストカード）
    * 番号：3530111333300000
    * 期限：03/2025
    * ユーザー名：任意
    * セキュリティコード：325
  * 出品者用
    * メールアドレス名: techexp@com
    * パスワード: 12121212


# ER図
<img width="300" alt="freemarketsampleER" src="https://user-images.githubusercontent.com/58362112/74603647-1fdedf00-50f9-11ea-9af0-2ad36100c67a.png">

# araitatsuya-codeの担当箇所

## デプロイ

AWS（EC2,S3）
WEBServer：Nginx
APPServer：Unicorn
DataBase：MySQL
Capistranoを導入した自動デプロイを行いました。

## ユーザー登録ページ

<img width="400" alt="サインイン画面" src="https://user-images.githubusercontent.com/58362112/74603919-12772400-50fc-11ea-93ca-260fbdc3a8a3.png">

* フロントエンド
  * 新規登録（ログイン方法選択画面）、ログイン画面
* バックエンド
  * RecaptchaAPIを導入した本人確認機能

## クレジットカード登録関連（フロントエンド）
  * マイページ左下お支払い方法変更からご覧頂けます。
    * クレジットカード情報がない場合の画面
    * クレジットカードを変更、追加する画面
    * 追加するとカード情報が表示される

## 本人確認ページ
  <img width="400" alt="Freemarket本人情報ページ" src="https://user-images.githubusercontent.com/58362112/74603994-d2647100-50fc-11ea-9630-9ed15bd80f92.png">














