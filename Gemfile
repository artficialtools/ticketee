source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :test, :development do 
   gem 'rspec-rails', '~> 2.5'
end

group :test do
    # Cucumber is the testing tool that interacts with capybara to write testing code.
  gem 'cucumber-rails'
    # is a browser simulator used in integration tests. Cucumber and Capybara are not the same.
  gem 'capybara'
  gem 'database_cleaner'
end