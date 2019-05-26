# PostgreSQL on Docker for Mac
## コンテナ作成と起動
```sh
docker container run -d --rm --name {container name} -e POSTGRES_USER=postgres -e POSTGRES_PASS={password} -p 5432:5432 postgres
```
## 接続
```sh
docker container exec -it {container name} bash
psql --version
psql -U postgres
```
## ホストから接続
```sh
# install
brew install postgresql
# stop service
brew services stop postgresql
# login to docker-postgres
psql -h localhost -U postgres
```

## コンテナ停止
```sh
docker container stop {container name}
```
