source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"

gem "rails", "~> 7.0.1"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails", ">= 0.3.4"
gem "turbo-rails", ">= 0.7.11"
gem "stimulus-rails", ">= 0.4.0"
gem "tailwindcss-rails", ">= 0.4.3"
gem "jbuilder", "~> 2.7"

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", ">= 1.4.4", require: false

group :development, :test do
  gem "debug", ">= 1.0.0", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console", ">= 4.1.0"
  gem "rack-mini-profiler", ">= 2.3.3"
end

