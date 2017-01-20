source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Core
gem 'rails', '~> 5.0.1'

# Bd
gem 'pg'
# gem 'sqlite3'
# gem 'squeel'
# gem 'counter_culture'
# gem 'friendly_id'


# Config
gem 'settingslogic'

# Authentication & Authorisation
# gem 'devise'
# gem 'switch_user'
# gem "pundit"

# Models
# Validations
# gem 'validates'
# gem 'phony_rails', :git => 'git://github.com/joost/phony_rails.git'

# States
# gem 'aasm'

# Form Objects
# gem 'virtus'

# Views Core
# gem 'slim-rails'
# gem 'haml-rails'

# Forms
# gem 'simple_form'
# gem 'cocoon'


# Presenters Decorators Facades
# gem 'draper'
# gem 'cells'
# gem "cells-haml", github: 'trailblazer/cells-haml'

# View Helpers
# gem 'simple-navigation', :git => 'git://github.com/andi/simple-navigation.git'
# gem 'simple-navigation-bootstrap'
# gem 'active_link_to'
# gem 'breadcrumbs_on_rails'

# Pagination
# gem 'kaminari'


# Assets
gem 'turbolinks', '~> 5'
# Js
gem 'jquery-rails'
gem 'jquery-turbolinks'
# gem 'role-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
# gem 'therubyracer', platforms: :ruby

# Css
gem 'bootstrap-sass'#, '~> 3.2.0'
# gem 'compass'
# gem 'compass-rails'
gem 'sass-rails', '~> 5.0'

# Uploading
# gem 'mini_magick'
# gem 'rmagick'
# gem 'carrierwave'


# Admin
# gem 'devise'
# gem 'activeadmin', github: 'activeadmin'

# Queue
# gem 'sidekiq'
# gem 'whenever', :require => false


# Api
# gem 'grape', github: 'intridea/grape'
# gem 'grape-cors', github: 'cambridge-healthcare/grape-cors'
# gem 'grape-swagger-rails'
# gem 'grape-entity'

# Money
# gem 'money', :git=>'git://github.com/tinkerdev/money.git'
# gem 'money-rails', :git=>'git://github.com/tinkerdev/money-rails.git'
# gem 'russian_central_bank'


# Mail
gem 'letter_opener', :group => [:development, :test]


# Errors
# gem 'airbrake_user_attributes'
gem 'airbrake', :github => 'airbrake/airbrake'

# Seo
# gem 'sitemap_generator', :git => 'git://github.com/kjvarga/sitemap_generator.git'
# gem 'meta-tags', :require=>'meta_tags'

# Performance
# gem 'gctools'

# Versions
# gem 'semver2'

# Server
gem 'puma', '~> 3.0'


group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # Other stuff
  # gem 'quiet_assets' # no asset logging in rails console
  gem "better_errors" # errors inspection in views
  gem 'ruby-progressbar'


  # Deploy
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv'
  gem 'capistrano-puma'
  gem 'capistrano-rails-console'
  gem "capistrano-db-tasks", require: false
end

group :development, :test do
  # Pry stuff
  gem 'pry-rails'
  gem 'pry-pretty-numeric' # 1_234_768
  gem 'pry-doc' # ? loop
  gem 'pry-docmore'
  gem "pry-stack_explorer" # show-stack in console
  gem 'pry-byebug' # step, next, finish, continue, break

  gem 'awesome_print' # nice inspection in console

  gem 'rspec-rails'
  # gem 'guard-rspec', require: false
end

group :test do
  # Minmum pack
  gem 'factory_girl_rails'
  gem "database_cleaner"

  # Seeds
  # gem 'forgery'
  # gem 'ffaker'

  # Specific Test Gems
  # gem "fakeredis", :require => "fakeredis/rspec"
  # gem 'resque_spec'
  # gem "email_spec", ">= 1.2.1"

  # Coverage
  # gem 'simplecov', :require => false
  # gem 'simplecov-rcov', :require => false
  # gem 'capybara-screenshot'
end

group :production do
  # gem 'newrelic_rpm'
end
