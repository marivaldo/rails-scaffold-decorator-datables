source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.1'

##
# Infrastructure
##

# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# PgSearch builds Active Record named scopes that take advantage of
#   PostgreSQL's full text search
gem 'pg_search'
# Use Puma as the app server
gem 'puma', '~> 4.3'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Load environment variables from .env into ENV
gem 'dotenv-rails'
# Memcached client
gem 'dalli', '~> 2.7.9'
# Annotate Rails classes with schema and routes info
gem 'annotate', group: :development

##
# Image & Uploads
##

# Use Active Storage variant
gem 'image_processing', '~> 1.2'
# Official AWS Ruby gem for Amazon Simple Storage Service (Amazon S3).
#   This gem is part of the AWS SDK for Ruby
gem 'aws-sdk-s3', require: false

##
# Async Tasks (Workers, Cron Jobs etc)
##

# Simple, efficient background processing for Ruby
gem 'sidekiq'
# Sidekiq strategy to restrict number of workers which are able to run specified queues simultaneously.
gem 'sidekiq-limit_fetch', '~> 3.4.0'
# Sinatra is a DSL for quickly creating web applications in Ruby with minimal effor
#   dependency for sidekiq web admin interface
gem 'sinatra', require: false

##
# Authentication & Authorization
##

# Flexible authentication solution for Rails with Warden.
gem 'devise', git: 'https://github.com/plataformatec/devise'
# Simple, robust and scalable authorization system
gem 'pundit'

##
# Utils
##

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
# Audinting and versioning records
gem 'paper_trail', '~> 10.2'
# Deal with CPF & CNPJ values
gem 'cpf_cnpj', '~> 0.5.0'
# Draper adds an object-oriented layer of presentation logic to your Rails application
gem 'draper'
# The ultimate pagination ruby gem
gem 'pagy', '~> 3.5'
# Has scope allows you to map incoming controller parameters to named scopes in your resources.
gem 'has_scope'
# A wrapper around DataTable's ajax methods that allow synchronization with server-side pagination in a Rails app
gem 'ajax-datatables-rails'
# Internationalization (i18n) library for Ruby
gem 'i18n'
# Repository for collecting Locale data for Ruby on Rails I18n as well as other interesting,
#   Rails related I18n stuff http://rails-i18n.org
gem 'rails-i18n', '~> 6.0.0'
# Slim templates generator for Rails 3, 4 and 5
gem 'slim-rails'
# Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.
gem 'simple_form'
# An attempt to tame Rails' default policy to log everything.
# Format logs and reduce default logs.
gem 'lograge'
gem 'logstash-event'

##
# Debug & Tests
##

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Show objects in nicely formatted columns for easy reading
  gem 'table_print', '~> 1.5.6'
  # Use Pry as your rails console
  gem 'pry-rails', '~> 0.3.9'
  # Combine 'pry' with 'byebug'. Adds 'step', 'next', 'finish', 'continue' and 'break' commands
  # to control execution
  gem 'pry-byebug'
  # Walk the stack in a Pry session
  gem 'pry-stack_explorer'

  # Bring the RSpec testing framework to Rails
  gem 'rspec-rails'
  # Simple one-liner tests for common Rails functionality
  gem 'shoulda-matchers'
  # A bunch of collection helpers for RSpec
  gem 'rspec-collection_matchers'
  # Use to ensure a clean state for testing
  gem 'database_cleaner'
  # Fixtures replacement with a straightforward definition syntax
  gem 'factory_bot_rails'
  # Lib for generating fake data such as names, addresses, and phone numbers
  gem 'faker'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end
