source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use pg as the database for Active Record
gem 'pg', '0.19.0'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'active_model_serializers', '~> 0.10.0'

gem 'slim-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'font-awesome-rails'
gem 'jquery-datatables-rails', '~> 3.4.0'

gem 'devise', '~> 4.2.0'

gem 'omniauth-facebook','4.0.0'
gem 'omniauth-google-oauth2', '0.4.1'

gem 'carrierwave', '~> 1.0'
gem 'sidekiq', '4.2.9'
gem 'httparty', '~> 0.14.0'

group :development, :test do
  gem 'rspec_api_documentation'

  gem 'figaro'
  gem 'annotate'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'rspec-rails', '~> 3.5', require: 'rspec/rails'

  gem 'pry-rails'
  gem 'rubocop', require: false
  gem 'mailcatcher', require: false # Catches emails in localhost, See https://mailcatcher.me/
  gem 'zeus', require: false
end

group :development do
  gem 'rails-erd'
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


group :test do
  gem 'faker'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'rails-controller-testing'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
