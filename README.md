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
---
 Basic RoR 7 Project exploring Hotwire and Turbo
 
[Bacancy Technology](https://www.bacancytechnology.com/blog/hotwire-rails-tutorial)

---
## Log 
### Create new rails app
```zsh
mkdir ~/projects/railshotwire
cd ~/projects/railshotwire
echo "source 'https://rubygems.org'" > Gemfile
echo "gem 'rails', '~> 7.0.0'" >> Gemfile
bundle install  
bundle exec rails new . --force -d=postgresql
```
