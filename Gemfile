source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use mysql as the database for Active Record
gem 'mysql2', '~> 0.3.20'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use Unicorn as the app server
gem 'unicorn'

# Simple Rails app configuration
gem 'figaro'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # rspec-rails is a testing framework for Rails 3.x and 4.x.
  gem 'rspec-rails'

  # Acceptance test framework for web applications http://jnicklas.github.com/capybara/
  gem 'capybara'
end

group :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # A library for setting up Ruby objects as test data.
  gem 'factory_girl_rails'

  # Collection of testing matchers extracted from Shoulda http://matchers.shoulda.io
  gem 'shoulda-matchers'

  # Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
  gem 'database_cleaner'

  # Uploads Ruby test coverage data to Code Climate https://codeclimate.com
  gem 'codeclimate-test-reporter', require: nil

  # Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites https://www.ruby-toolbox.com/projects/simplecov
  gem 'simplecov', require: false

  # A library for generating fake data such as names, addresses, and phone numbers
  gem 'faker'
end
