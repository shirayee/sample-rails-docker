# sample-rails-docker

## usage

### build

```sh
$ docker-compose build
```

### start process

```sh
$ docker-compose up -d
# create db
$ docker-compose run --rm app rake db:create
# migration (if needed)
$ docker-compose run --rm app rake db:migrate
```

### stop process

```sh
$ docker-compose down -v
```