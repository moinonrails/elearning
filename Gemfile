source 'https://rubygems.org'

gem 'rails', '4.2.0'
gem 'mysql2', '~> 0.3.20'
gem 'jquery-rails', '~> 3.1.2'    # Use jquery as the JavaScript library
gem 'coffee-rails', '~> 4.1.0'    # Use CoffeeScript for .js.coffee assets and views
gem 'bootstrap-sass', '~> 3.3.4'  # UI
gem 'sass-rails', '~> 5.0.1'      # Use SCSS for stylesheets
gem 'paperclip', '~> 4.3'
gem 'haml-rails', '~> 0.9.0'
gem 'compass-rails', '~> 2.0.4'
gem 'uglifier', '~> 2.7.1'
gem 'therubyracer', platforms: :ruby
gem 'devise'
gem 'cancan', '>= 1.6.10'
gem 'kaminari', '~> 0.16.3'
gem 'friendly_id', '~> 5.1.0'
gem 'bootstrap-datepicker-rails'
gem 'annotate'
gem 'rails_admin'

group :development do
  gem 'better_errors', '~> 2.1.1'
  gem 'quiet_assets', '~> 1.1.0'
  gem 'dotenv-rails'
  # gem 'traceroute'
  # gem 'rack-mini-profiler'
  # gem 'brakeman', require: false
  # gem 'rails_best_practices'
  # gem 'rubocop', require: false
end

group :development, :test do
  gem 'byebug', '~> 5.0.0'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development keeping your app running in the background.
  # Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem 'rspec-rails'
end

group :production do
  gem 'unicorn', '~> 4.9.0'
  gem 'unicorn-rails'
  gem 'exception_notification', '~> 4.1.0'
end