# 2021.05.25Javaゼミ資料 DB設計書

## 改版履歴
|日付|版数|内容|
|---|---|---|
|2021.05.24|初版|初版作成|

## DB名:database_example

## ユーザーに関するテーブル

### users(ユーザー)
|カラム名|項目名|概要|データ型|NULLを許容|PRI|DEFAULT|備考|
|---|---|---|---|---|---|---|---|
|id|ID|登録した順に自動的に入力される番号|INT|NO|NULL|auto_increment|
|names|ユーザー名|半角20文字まで|VARCHAR(20)|NO|NULL||
|addresses|住所|半角200文字まで|VARCHAR(200)|NO|NULL||
|phone_numbers|電話番号|半角10文字まで|VARCHAR(10)|NO|NULL||