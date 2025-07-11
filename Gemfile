source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.5', '>= 6.1.5.1'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem "puma", "~> 3.11"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'active_model_serializers'
gem 'jquery-rails'
gem 'turbolinks'
gem "pg", "~> 1.1"
# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

gem 'webpacker', '~> 5.0'

gem 'will_paginate', '~> 3.3.0'
gem 'will_paginate-bootstrap'
gem 'whenever', require: false

gem "chartkick"
gem "groupdate"
gem 'highcharts-rails'
gem 'fcm'
gem 'countries'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'
gem 'devise'
gem 'devise-jwt'
gem 'dotenv-rails'
gem 'twilio-ruby'
gem "aws-sdk-s3", require: false
gem 'ransack'
gem 'stripe'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "acts_as_list", "~> 1.0"
