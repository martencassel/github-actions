# frozen_string_literal: true

source 'https://rubygems.org'
gemspec

group :development do
  gem 'rack-test'
  gem 'smart_proxy', :git => 'https://github.com/theforeman/smart-proxy.git', :branch => 'develop'
end

group :test do
  gem 'public_suffix'
  gem 'rack-test'
  gem 'rubocop', '~> 1.28.0'
  gem 'rubocop-performance', require: false
end
