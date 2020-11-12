source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'httparty'
gem 'jsonapi-serializer'
gem 'pg'
gem 'puma'
gem 'rails'
gem 'rswag-api'
gem 'rswag-ui'
gem 'strong_migrations'

group :test do
  gem 'vcr'
  gem 'webmock'
end

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'listen'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'rswag-specs'
  gem 'rubocop'
end

group :development do
  gem 'web-console'
end
