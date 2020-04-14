# README

This README would normally document whatever steps are necessary to get the
application up and running.

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

#comands to execute

#up the containers
docker-compose up -d

#generate data in the database
rails db:migrate db:seed

# First, add it to the Gemfile
bundle add graphql --version="~> 1.9"

# Then, run the generator
rails generate graphql:install

#install the webpacker
rails webpacker:install