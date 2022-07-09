# README

This README would normally document whatever steps are necessary to get the
application up and running.

# Commands ...
`$ docker-compose run web + ...`

## build
`$ docker-compose build`

## after add gems
`$ docker-compose run web bundle install`

## create DB
`$ docker-compose run web bundle exec rails db:create`

## migrate
`$ docker-compose run web bundle exec rails db:migrate`


Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
