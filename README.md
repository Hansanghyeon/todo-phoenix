## phoenix init

```
mix phx.new app --no-dashboard --no-gettext --no-mailer
```

## database 추가

phoenix 기본 데이터베이스는 PostgreSQL이다 해당 docker 추가

```
docker compose up -d
```

## phoenix ecto.create

```
mix ecto.create
```

## phoenix server 실행해보기

```
mix phx.server
```
