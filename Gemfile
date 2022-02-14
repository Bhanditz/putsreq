source 'https://rubygems.org'

ruby '2.5.0'

gem 'rails', '~> 5.2.6', '>= 5.2.6.2'
gem 'sass-rails', '>= 5.0.7'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '>= 4.2.2'
gem 'jquery-rails', '>= 4.3.1'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'webmock'
  gem 'codeclimate-test-reporter', require: nil
  gem 'simplecov'
  gem 'stub_env'
  gem 'rails-controller-testing', '>= 1.0.2'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails', '>= 3.7.2'
  gem 'rack-test'
  gem 'database_cleaner'
  gem 'dotenv-rails', '>= 2.2.2'
end

source 'https://rails-assets.org' do
  gem 'rails-assets-favico.js'
  gem 'rails-assets-dispatcher'
  gem 'rails-assets-bootstrap-less'
  gem 'rails-assets-clipboard'
end

gem 'therubyracer'
gem 'mongoid', '~> 6'
gem 'kaminari-mongoid'
gem 'kaminari-actionview'
gem 'httparty'
gem 'rack-cors', require: 'rack/cors'
gem 'redis'
gem 'bootstrap-sass', '~> 3.1.1'
gem 'dotiw', '>= 4.0.0'
gem 'devise', '~> 4.4.3'
gem 'pusher'
gem 'interactor', '~> 3.0'
gem 'rollbar'
gem 'oj'
gem 'webpacker', '~> 3.2', '>= 3.2.0'
gem 'active_model_serializers', '>= 0.10.7'
gem 'puma', '>= 4.3.11'
