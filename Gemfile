# frozen_string_literal: true
source 'https://rubygems.org'

# Declare your gem's dependencies in europeana_logging.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
# gem 'byebug', group: [:development, :test]

group :development do
  gem 'brakeman'
  gem 'bundler-audit'
end

group :test do
  gem 'coveralls', require: false
end

group :test, :development do
  gem 'rubocop', '0.53', require: false
end
