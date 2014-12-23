source 'https://rubygems.org'
ruby '2.1.5'

gem 'rails', '3.2.21'
gem 'locomotive_cms', '~> 2.5.6', require: 'locomotive/engine'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'compass',        '~> 1.0.1'
  gem 'compass-rails',  '~> 2.0.1'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
end

group :development do
  # Use unicorn as the app server
  gem 'unicorn'
end

group :production do
  gem 'locomotive-heroku', '~> 0.1.0', require: 'locomotive/heroku'
  gem 'thin'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
