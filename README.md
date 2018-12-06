# docker-rails5

* Ruby on Rails 5 Sample Application on Docker

## Requirement
* Docker >= 1.12

## Usage
* Build
```
$ cd /path/to/rails-develop
$ docker-compose build
```

* Database creation
```
$ docker-compose run rails rails db:create
```

* Up
```
$ docker-compose up -d
```

* http://127.0.0.1

* Run tests(For Mac)
```
$ bundle exec rspec
```

* Run guard
```
$ docker-compose run rails guard --force-polling
```
