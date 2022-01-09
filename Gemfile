# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.0"

gem "jbuilder"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.1"
gem "sqlite3", "~> 1.4"

gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"

gem "importmap-rails"
# gem "redis", "~> 4.0"
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"
# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem "rack-mini-profiler"
  gem "rubocop", require: false
  gem "rubocop-minitest", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
