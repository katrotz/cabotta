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
```
bundle update i18n
bundle install
rails g spree:install --user_class=Spree::User
rails g spree:auth:install
rails g spree_gateway:install

# Production
bundle exec rake assets:precompile RAILS_ENV=production
```
