# README



# ~~ OGORARETAI!!!!!!!!!! ~~

### AWS:
### Heroku:
##### ＊ほぼAWSしか更新していません。


## 概要
奢られやー、パパ活。そんな奢られたい人たちのニーズを満たすサービス。

## バージョン
- Ruby 2.6.5
- Rails 5.2.4

## 機能一覧

- [ ] ユーザ機能

  - [ ] ユーザCRUD機能（作成、詳細、更新、削除）
  - [ ] フォロー機能とその表示機能
  - [ ] レビュー機能
  - [ ] ダイレクトメッセージ機能

- [ ] ユーザ管理機能

  - [ ] ユーザ編集機能
  - [ ] ユーザ削除機能
    - [ ] ユーザの編集と削除は作成したユーザと管理者のみ実行可能

- [ ] メール通知機能

  - [ ] メール通知機能（イベント主催者へのお問い合わせ）
  - [ ] メール通知機能（イベントの詳細変更の通知メール）
  - [ ] メール通知機能（イベントの中止の通知メール）

- [ ] 画像アップロード機能
- [ ] ページネーション機能
- [ ] ログイン機能
- [ ] 簡易版ゲストログイン機能



## カタログ設計
詳細は[こちら](https://docs.google.com/spreadsheets/d/1jzKGT_3a9xmagpc9RAHunR8BEhg3C-Pu0EhWB_1oJiw/edit?usp=sharing)をご覧ください。

## テーブル定義
詳細は[こちら](https://docs.google.com/spreadsheets/d/1ZxAl-qePMVRVjMSjJvvdCAtxFa8Lr9Chx3hgXIj9r2s/edit?usp=sharing)をご覧ください。

## ER図
詳細は[こちら](https://raw.githubusercontent.com/KakeruYamamoto/graduation/master/erd.png)をご覧ください。

## 画面遷移図
詳細は[こちら](https://cacoo.com/diagrams/y5Szk1GeOvPKQRcD/9E3BF)をご覧ください。

## 画面ワイヤーフレーム
詳細は[こちら](https://cacoo.com/diagrams/51O1AnZuSgtrGNYT/B6EB3)をご覧ください。

# 使用技術
- ログイン機能
  - devise
  - omniauth(<=<=予定)
  - omniauth-facebook（<=<=予定）
- 管理者機能
  - rails_admin
- 権限管理
  - cancancan
- 画像編集機能
  - carrierwave
  - mini_magick
- 検索機能
  - ransack
- ページネーション
  - kamminari
- デバッグ
  - better_errors
  - binding_of_caller
  - pry-rails
- テスト
  - rspec-rails
  - spring
  - spring-commands-rspec
  - factory_bot_rails
  - capybara
  - selenium-webdriver
  - database_cleaner
  - launchy
  - faker
- デザイン
  - bootstrap
  - kaminari-bootstrap
<!-- - 辞書機能
  - i18n -->
- メール機能
  - SendGrid(<=<=予定)
- マップ機能
  - GoogleMap(<=<=予定)

# デプロイ先
- AWS
- Heroku

## How to Start
```
  1.  git clone https://github.com/KakeruYamamoto/graduation.git
  2.  rails db:create
  3.  rails db:migrate
  4.  rails db:seed
  5.  yarn install
  6.  bundle exec rspec    
  7.  rails s  
```
