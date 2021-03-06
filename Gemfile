# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

#gem 'uhura_client', path: '../uhura-client'
gem 'uhura_client', git: 'git@github.com:dailydrip/uhura-client.git', branch: 'master'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0.beta1'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '>= 4.0.0.rc.3'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
# Devise helps us on login stuff
gem 'devise'
# Administration framework for ruby on rails
gem 'administrate'
# omniauth
gem 'omniauth', '~> 1.9'
# omniauth identity strategy
gem 'omniauth-identity'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# slim
gem 'slim-rails'
gem 'jquery-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'spinach-rails'
  gem 'awesome_print'
  gem 'hirb'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'database_cleaner', '~> 1.7.0'
  gem 'factory_bot_rails', '~> 5.0.2'
  gem 'rails-controller-testing', '~> 1.0.4'
  gem 'rspec-rails', '~> 3.8.2'
  gem 'selenium-webdriver', '~> 3.142.3'
  gem 'shoulda-matchers', '~> 4.1.2'
  gem 'webdrivers', '~> 4.1.2' # Easy installation and use of web drivers to run system tests with browsers
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
  gem 'brakeman'
  gem 'rubocop', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
