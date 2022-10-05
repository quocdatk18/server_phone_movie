# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

gem 'bootsnap', require: false
gem 'bootstrap', '~> 5.1.3'
gem 'figaro'
gem 'font-awesome-sass', '~> 6.2.0'
gem 'importmap-rails'
gem 'jbuilder'
gem 'mysql2', '~> 0.5'
gem 'pagy'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.3', '>= 7.0.3.1'
gem 'rails-i18n'
gem 'redis', '~> 4.0'
gem 'sass-rails', '>= 6'
gem 'sidekiq'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'faker'
  gem 'pry-rails'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
