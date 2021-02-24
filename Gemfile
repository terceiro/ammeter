source 'https://rubygems.org'

rspec_version = ENV['RSPEC_VERSION'] || '~> 4.0'
rails_version = ENV['RAILS_VERSION'] || '>= 5.1.0'

if rspec_version == 'master'
  gem "rspec-rails", :git => 'git://github.com/rspec/rspec-rails.git'
  gem "rspec", :git => 'git://github.com/rspec/rspec.git'
  gem "rspec-core", :git => 'git://github.com/rspec/rspec-core.git'
  gem "rspec-expectations", :git => 'git://github.com/rspec/rspec-expectations.git'
  gem "rspec-mocks", :git => 'git://github.com/rspec/rspec-mocks.git'
  gem "rspec-collection_matchers", :git => 'git://github.com/rspec/rspec-collection_matchers.git'
  gem "rspec-support", :git => 'git://github.com/rspec/rspec-support.git'
else
  gem 'rspec-rails', rspec_version
end

gem 'rails', rails_version
gem 'uglifier'
gem 'rake'
gem 'coffee-rails'
gem 'sass-rails'
gem 'jquery-rails'
gem 'haml-rails'

# Specify your gem's dependencies in ammeter.gemspec
gemspec

