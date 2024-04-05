source 'https://rubygems.org'

ruby '2.5.0'

gem 'rails', '~> 7.0.8', '>= 7.0.8.1'
gem 'sass-rails', '>= 5.0.8'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '>= 5.0.0'
gem 'jquery-rails', '>= 4.3.2'

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
  gem 'better_errors', '>= 2.5.0'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails', '>= 3.8.0'
  gem 'rack-test', '>= 1.1.0'
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
gem 'mongoid', '~> 6'
gem 'kaminari-mongoid'
gem 'kaminari-actionview', '>= 1.2.0'
gem 'httparty'
gem 'rack-cors', require: 'rack/cors'
gem 'redis'
gem 'bootstrap-sass', '~> 3.1.1'
gem 'dotiw', '>= 4.0.1'
gem 'devise', '~> 4.7.0'
gem 'pusher'
gem 'interactor', '~> 3.0'
gem 'rollbar'
gem 'oj'
gem 'webpacker', '~> 3.2', '>= 3.2.1'
gem 'active_model_serializers', '>= 0.10.13'
gem 'puma'
