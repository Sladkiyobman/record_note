source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'bootstrap', '~> 4.0'
gem 'sprockets-rails', '~> 3.2', '>= 3.2.1'


gem 'jquery-rails'
gem 'rails', '~> 5.1.4' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'sqlite3' # Use sqlite3 as the database for Active Record
gem 'puma', '~> 3.7'  # Use Puma as the app server
gem 'sass-rails', '~> 5.0'  # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0'  # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.2'  # Use CoffeeScript for .coffee assets and views
gem 'turbolinks', '~> 5'  # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jbuilder', '~> 2.5'  # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'capybara', '~> 2.13'   # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  gem 'rspec-rails', '~> 3.7'
end

group :test do
  gem 'database_cleaner'
end

group :development do
  gem 'web-console', '>= 3.3.0' # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
