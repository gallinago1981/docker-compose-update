# docker-compose-update
docker compose を利用した場合のContainer imageのUpdateを検証する
タグはlatest指定

# container image を更新して反映する

``` shell
# Docker Imageを最新化
$ docker compose pull

# 更新したイメージを反映する
$ docker compose up --no-deps -d web
```