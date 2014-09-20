source 'https://rubygems.org'
ruby "2.1.0"

# Web Framework
gem 'rails', '~> 4.1.6'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 2.5.3'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

group :development do
  # Use sqlite3 as the database for Active Record in development
  gem 'sqlite3'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 1.1.3'
end

group :production do
  # Use PostgreSQL as the database for Active Record in development
  gem 'pg', '~> 0.17.1'

  # Heroku's Rails the 12factor way
  gem 'rails_12factor', '~> 0.0.2'

  # Better web server for Heroku
  gem 'unicorn', '~> 4.8.3'
end
