source 'https://rubygems.org'

ruby '2.2.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0.alpha', git: 'https://github.com/rails/rails.git'
gem 'rack', '2.0.0.alpha', git: 'https://github.com/rack/rack.git'
gem 'arel', '7.0.0.alpha', git: 'https://github.com/rails/arel.git'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.18', '< 0.5'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use ActiveModelSerializers to serialize JSON responses
gem 'active_model_serializers', '~> 0.10.0.rc2'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.0'
  gem 'capybara'
  gem 'pry-rails'
  gem 'spring'
  gem 'spring-commands-rspec'
  # CLI
  gem 'httparty'
  gem 'httmultiparty'
  gem 'awesome_print'
  gem 'rails_best_practices'
end

group :development do
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'web-console', '~> 2.0'
  gem 'database_cleaner'
  gem 'timecop'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  gem 'fork_break'
  gem 'erd'
  # Loading the listen gem enables an evented file system monitor. Check
  # https://github.com/guard/listen#listen-adapters if on Windows or *BSD.
  # gem 'listen', '~> 3.0.5'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
