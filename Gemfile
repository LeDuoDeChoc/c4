source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'jquery-rails'
gem 'haml-rails'
gem 'paperclip'
gem 'simple_form'
gem 'bootstrap-sass'
gem 'factory_girl_rails'
gem 'aws-sdk'
gem 'thin'
gem 'devise'
gem 'faker'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'sqlite3'
  gem 'shoulda'
  gem 'meta_request', '0.2.1'
end

group :development do
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'ruby_gntp'
  gem 'rb-fsevent', :require => false
  gem 'rails_best_practices'
end

group :test do
  gem 'simplecov', :require => false
  gem 'database_cleaner'
end