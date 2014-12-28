source "https://rubygems.org"

ruby '2.1.5'

gem "rails", "~> 4.2.0"
gem "sass-rails", "~> 5.0.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.1.0"
gem "jquery-rails"
gem "turbolinks"
# gem "bcrypt", "~> 3.1.7"

group :production do
  gem "puma"
  gem "pg"
  gem 'rails_12factor'
end

group :development, :test do
  gem "web-console", "~> 2.0.0"
  gem "rspec-rails", "~> 3.1.0"
end

group :development do
  gem "thin"
  gem "sqlite3"
  gem "byebug"
  gem "guard-rspec", require: false
end
