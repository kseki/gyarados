# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

gem 'importmap-rails', '>= 0.3.4'
gem 'jbuilder', '~> 2.7'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.1'
gem 'sqlite3', '~> 1.4'
gem 'stimulus-rails', '>= 0.4.0'
gem 'tailwindcss-rails', '>= 0.4.3'
gem 'turbo-rails', '>= 0.7.11'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', '>= 1.0.0', platforms: %i[mri mingw x64_mingw]
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
end

group :development do
  gem 'rack-mini-profiler', '>= 2.3.3'
  gem 'web-console', '>= 4.1.0'
end
