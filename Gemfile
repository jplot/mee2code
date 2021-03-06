source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'
gem 'coffee-script'
# Rails locale data
gem 'rails-i18n'
# Use Puma as the app server
gem 'puma'
# Library for bulk inserting data using ActiveRecord.
gem 'activerecord-import'
# Authentication solution for Rails
gem 'devise'
# Devise locale data
gem 'devise-i18n'
# Authentication OAuth2
gem 'oauth2'
gem 'omniauth-oauth2', '~> 1.3.1'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Twitter Bootstap as stylesheet framework
gem 'bootstrap-sass'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'highcharts-rails'
gem 'underscore-rails'
gem 'momentjs-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'rails_admin'
gem 'rails_admin-i18n'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :production do
  # Use postgresql as the database for Active Record
  gem 'pg'
end

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'
  gem 'listen'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen'

  # Optimization tools
  gem 'rack-mini-profiler', require: false
  gem 'brakeman', require: false
  gem 'rubocop', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
