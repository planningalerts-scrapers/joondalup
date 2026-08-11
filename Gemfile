# frozen_string_literal: true

# It's easy to add more libraries or choose different versions. Any libraries
# specified here will be installed and made available to your morph.io scraper.
# Find out more: https://morph.io/documentation/ruby

source "https://rubygems.org"

ruby "3.2.2" # ruby 3.2.3 does NOT run on heroku-18!

gem "mechanize", "~> 2.14"
gem "nokogiri", "~> 1.17.2" # nokogiri 1.18 does NOT run on heroku-18!
gem "scraper_utils", "~> 0.12.1"
gem "scraperwiki", git: "https://github.com/openaustralia/scraperwiki-ruby.git",
                   branch: "morph_defaults"
gem "sqlite3", "~> 2.2.0" # sqlite3 2.3.0 does NOT run on heroku-18!

group :development do
  gem "rake", "~> 13.0"
  gem "rspec", "~> 3.12"
  gem "rubocop", "~> 1.84"
  gem "simplecov", "~> 0.18.0"
  gem "simplecov-console", "~> 0.9.5"
  gem "timecop", "~> 0.9.10"
  gem "vcr", "~> 6.4"
  # gem "watir", "~> 7.3"
  gem "webmock", "~> 3.19.0"
end
