source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'sinatra', '~> 2.0.5'
gem 'activerecord', '~> 5.2.2'
gem 'sinatra-activerecord', '~> 2.0.14'
gem 'pg'
gem 'rake'
gem 'pg_search', '~> 2.0.1'

group :development do
  gem 'tux'
end

gem 'factory_bot'
gem 'ffaker'
gem 'database_cleaner'

group :test do
  gem 'rack-test', require: 'rack/test'
  gem 'rspec'
end
