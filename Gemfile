source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.0.rc1'
gem 'sass-rails', '~> 5.0'
gem 'bootstrap', '~> 4.0'
gem 'popper_js', '~> 1.12.9'
gem 'jquery-rails'
gem 'merit', '~> 3.0.1'
gem 'jquery-atwho-rails', '~> 1.5.4'
gem 'autoprefixer-rails', '~> 7.2.5'
gem 'jquery-ui-rails', '~> 6.0.1'
gem 'd3-rails', '~> 4.10.2'
gem 'will_paginate-bootstrap4'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.3'
gem 'devise', '~> 4.4.1'
gem 'carrierwave', '~> 0.11.2'
gem 'mini_magick', '~> 4.8'
gem 'friendly_id', '~> 5.2.3'
gem 'public_activity', '~> 1.5'
gem 'acts_as_votable', '~> 0.11.1'
gem 'acts_as_commentable', '~> 4.0.2'
gem 'acts_as_follower', '~> 0.2.1'
gem 'counter_culture', '~> 1.9'
gem 'faker', '~> 1.8.7'
gem 'populator', '~> 1.0'
gem 'auto_html', '~> 2.0'
gem 'sanitize', '~> 4.6'
gem 'active_model_serializers', '~> 0.10.7'
# Use sqlite3 as the database for Active Record
# Use Puma as the app server
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.11'
# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'puma', '~> 3.11'
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors'
  gem 'letter_opener'
  gem 'guard'
  gem 'guard-rspec', '~> 4.7.3'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

group :production do
  gem 'pg'
  gem 'unicorn'
  gem 'rails_12factor'
  gem 'fog'
  gem 'fog-aws'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
