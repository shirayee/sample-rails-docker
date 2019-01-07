# sample-rails-docker

## usage

### build

```
$ docker-compose build
```

### start process

```
$ docker-compose up -d
# create db
$ docker-compose run --rm app rake db:create
# migration (if needed)
$ docker-compose run --rm app rake db:migrate
```

### stop process

```
$ docker-compose down -v
```