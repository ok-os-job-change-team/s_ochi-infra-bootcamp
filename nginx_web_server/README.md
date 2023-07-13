# 簡易的なWebサーバー
Dockerを使ってローカル環境にWebサーバーを構築することは一般的な手法で、素のHTMLをサーブすることも可能です。
NginxをWebサーバーとして使用しています。

## 使い方
- dockerコンテナを起動しましょう。その後に、http://localhost:8080 にアクセスすると、index.htmlが表示されます。
```bash
# Dockerコンテナを起動する
$ docker-compose up
```
