source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'jquery-rails'

#sets different gem for use in production to allow for Heroku--which doesnt work with sqlite
group :production do
  gem 'pg'
end
#sets sqlite3 for use only in development environment
group :development, :test do
  gem 'sqlite3'
end

# Gems used only for assets and not required in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
	gem 'uglifier', '>= 1.0.3'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', :platforms => :ruby

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

