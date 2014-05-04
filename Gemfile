source 'http://rubygems.org'

ruby '2.1.1'

gem 'foreman'
gem 'puma'
gem 'rack'
gem 'grape', github: 'intridea/grape'
gem 'grape-swagger'
gem 'mongoid', github: 'mongoid/mongoid'
gem 'sidekiq'
gem 'sidekiq-status'
gem 'docker-api', :require => 'docker'
gem 'rake'

group :development do
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-puma'
  gem 'guard-sidekiq'
  gem 'rb-inotify', :require => false
  gem 'rubocop'
end

group :test do
  gem 'rspec'
  gem 'rspec-sidekiq'
  gem 'rack-test'
  gem 'database_cleaner'
  gem 'fabrication'
  gem 'webmock'
  gem 'vcr'
end
