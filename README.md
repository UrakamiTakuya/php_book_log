## 環境構築

```bash
# Docker イメージのビルド
docker-compose build

# Docker コンテナの起動
docker-compose up -d

# Docker コンテナ内でコマンドを実行する
docker-compose exec app php -v

# Docker コンテナの停止・削除
docker-compose down

# MySqlへ接続
$ docker-compose exec app /bin/bash
$ mysql -h db -u book_log -D book_log -p

```
