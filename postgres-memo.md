# PostgreSQLメモ
## インストール
### 環境
- ubunt 18.04 LTS
- postgreSQL 11
### 手順
- 公式サイトのインストール手順に従う
- https://wiki.postgresql.org/wiki/Apt
- 
- キー情報の登録し直し
```sh
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 7FCC7D46ACCC4CF8
```
- インストール
```sh
sudo apt-get update
sudo apt-get install postgresql-11 pgadmin4
``
- セットアップ
```sh
# postgresユーザーで実行する
sudo su - postgres

# バージョン確認
psql -V

```
## 内部構造
## 開発に役立つ知識
## 運用に役立つ知識
