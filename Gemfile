source 'http://rubygems.org'

gem 'sinatra'
gem 'activerecord', '~> 5.2', '>= 5.2.4', :require => 'active_record'
gem 'sinatra-activerecord', :require => 'sinatra/activerecord'
gem 'rake'
gem 'rack'
gem 'require_all'
gem 'thin'
gem 'pg'
gem 'shotgun'
gem 'bcrypt'
ruby "2.7.1"

group :development, :test do
  gem 'pry'
end

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
  gem 'database_cleaner', git: 'https://github.com/bmabey/database_cleaner.git'
end