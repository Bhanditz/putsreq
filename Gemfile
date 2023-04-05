source 'https://rubygems.org'

ruby '2.5.0'

gem 'rails', '~> 6.1.7', '>= 6.1.7.3'
gem 'sass-rails', '>= 6.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'
gem 'jquery-rails', '>= 4.4.0'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'webmock'
  gem 'codeclimate-test-reporter', require: nil
  gem 'simplecov'
  gem 'stub_env'
  gem 'rails-controller-testing', '>= 1.0.3'
end

group :development do
  gem 'better_errors', '>= 2.8.0'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rack-test', '>= 2.0.0'
  gem 'database_cleaner'
  gem 'dotenv-rails', '>= 2.7.6'
end

source 'https://rails-assets.org' do
  gem 'rails-assets-favico.js'
  gem 'rails-assets-dispatcher'
  gem 'rails-assets-bootstrap-less'
  gem 'rails-assets-clipboard'
end

gem 'therubyracer'
gem 'mongoid', '~> 7', '>= 7.0.12'
gem 'kaminari-mongoid'
gem 'kaminari-actionview'
gem 'httparty', '>= 0.21.0'
gem 'rack-cors', '>= 1.0.5', require: 'rack/cors'
gem 'redis'
gem 'bootstrap-sass', '~> 3.4.0'
gem 'dotiw'
gem 'devise', '~> 4.7.1'
gem 'pusher'
gem 'interactor', '~> 3.0'
gem 'rollbar'
gem 'oj'
gem 'webpacker', '~> 3.2', '>= 3.2.0'
gem 'active_model_serializers', '>= 0.10.12'
gem 'puma', '>= 4.3.12'
