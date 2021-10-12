# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.6.3'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'pg', '~> 1.1.4'
gem 'puma', '~> 5.5'
gem 'rails', '~> 5.2.2.1'

gem 'bcrypt'
gem 'dry-configurable'
gem 'dry-validation', '~> 0.13.3'
gem 'jsonapi-rails', github: 'jsonapi-rb/jsonapi-rails'
gem 'jwt'
gem 'rack-cors', require: 'rack/cors'
gem 'reform-rails'
gem 'trailblazer-endpoint', github: 'trailblazer/trailblazer-endpoint'
gem 'trailblazer-rails'

group :development, :test do
  gem 'ffaker'
  gem 'pry-byebug'
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner'
  gem 'dox', require: false
  gem 'factory_bot_rails'
  gem 'json_matchers'
  gem 'shoulda-matchers'
end
