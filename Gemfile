source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.1"
gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "sassc-rails"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "bootsnap", require: false
gem "bootstrap", "~> 5.2.2"
gem "jquery-rails"
gem "font-awesome-sass", "~> 6.3.0"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
  gem "listen", "~> 3.1", ">= 3.1.5"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.1"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem "pg"
end
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]