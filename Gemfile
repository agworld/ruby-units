source 'https://rubygems.org'

group :development do
  gem 'pry', '0.12.2' # Pry fails with error on load with version 0.13.1 - `NameError: uninitialized constant Pry::Command::ExitAll`
  gem 'pry-byebug', platform: :mri
  gem 'ruby-maven', platform: :jruby
  gem 'ruby-prof', platform: :mri
end

# This is a minimal set of Gems required to build on travis
group :test do
  gem 'bundler'
  gem 'rake'
  gem 'rspec'
  gem 'simplecov'
end

gemspec
