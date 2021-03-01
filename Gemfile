source 'https://rubygems.org'

ruby ENV['CUSTOM_RUBY_VERSION'] || '~> 2.7.1'

gem 'rails', '~> 6.0.3'
gem 'puma'
gem 'bootsnap'

gem 'sass-rails', '~> 5.0'
gem 'sass-rails-bootstrap'
gem 'jquery-rails'
gem 'uglifier'

group :development do
  gem 'foreman'
  gem 'sqlite3'
  gem 'listen'
end

group :production do
  gem 'pg'
  gem 'newrelic_rpm'
  gem 'sqreen', '< 1.23.2'
  gem 'airbrake'
end
