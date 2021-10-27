source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem "rails", "~> 6.1.4", ">= 6.1.4.1"
gem "pg"
gem "puma", "~> 5.0"
gem "sass-rails", ">= 6"
gem "importmap-rails"
gem "hotwire-rails"
gem "simple_form"
gem "country_select"

# Delayed jobs
# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"
# gem "redis-namespace"
# gem "sidekiq"
# gem "sidekiq-scheduler"

# Use Active Model has_secure_password
# gem "bcrypt", "~> 3.1.7"
# gem "devise"
# gem "devise-i18n"
# gem "devise-bootstrap5"

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
# gem "mini_magick"

# Utilities
# gem "valid_email2"
# gem 'httparty'
# gem 'active_hash'
gem "amazing_print"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.4", require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "brakeman" # security tests https://github.com/presidentbeef/brakeman
  gem "rexml", "~> 3.2", ">= 3.2.4"
  gem "dotenv-rails"
end

group :development do
  gem "foreman"
  gem "pry"
  gem "pry-rails"
  gem "better_errors"
  gem "binding_of_caller"
  gem "web-console", ">= 4.1.0"
  gem "listen", "~> 3.3"
  gem "spring"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", ">= 1.2016.7"  # Don't rely on OSX/Linux timezone data
