source 'https://rubygems.org'
ruby '2.3.1'

# Edge Github Version
# TODO: Change this to 5.0 when it hits rubygems.org
gem 'rails', github: "rails/rails"
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'
# For API Responses
gem 'active_model_serializers'
# API Rate Limiting
gem 'rack-attack'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # Use RSpec for specs
  gem 'rspec-rails', '3.1.0'
  # Use Factory Girl for generating random test data
  gem 'factory_girl_rails'
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end