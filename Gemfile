source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.1"
gem "rails", "~> 7.0.3", ">= 7.0.3.1"
gem "sprockets-rails"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
# gem "redis", "~> 4.0"
# gem "kredis"
# gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
# gem "sassc-rails"
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "sqlite3", "~> 1.4"
  gem 'byebug', '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console"
  # gem "rack-mini-profiler"
  # gem "spring"
end

group :production do
  gem 'pg', '1.1.4'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
