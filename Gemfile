source 'https://rubygems.org'

gemspec

gem 'rake', '~> 10.3'

group :development do
  gem 'rake-compiler', '~> 0.9'
  gem 'rubocop', '~> 0.25'
end

group :test do
  gem 'mocha', '~> 1.1'
  gem 'minitest', '~> 5.4'
  gem 'simplecov', '~> 0.9', require: false
  gem 'codeclimate-test-reporter', github: 'deivid-rodriguez/ruby-test-reporter', branch: 'add_appveyor_support', require: false
end
