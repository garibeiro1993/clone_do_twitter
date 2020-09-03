source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Follow user
gem 'acts_as_follower', github: 'tcocca/acts_as_follower', branch: 'master'
# like content
gem 'acts_as_votable'
# Integration with Searchkick
gem 'searchkick'
# jwt authentication
gem 'knock'
# serializer json
gem 'active_model_serializers'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false
#authorization
gem 'cancancan'
#pagination
gem 'will_paginate', '~> 3.1.0'
# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'
#Use to protect API from external calls
gem 'rack-attack'
#bcrypt
gem 'bcrypt', '~> 3.1', '>= 3.1.11'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Generate record based in model
  gem 'factory_bot_rails'
  # Faker data
  gem 'ffaker'
  # Clean db after test
  gem 'database_cleaner'
  #Rspec
  gem 'rspec-rails'
  #Rspec test auxiliar gem
  gem 'rspec-json_expectations'
end

group :development do
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
