source "https://rubygems.org"
  ruby "3.3.4"
gem "rails", "~> 7.2.1"
gem "sprockets-rails"
 
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'devise', '~> 4.9', '>= 4.9.4'
gem 'devise-bootstrap-views', '~> 1.0', '>= 1.0.1'
# gem "redis", ">= 4.0.1"
# gem "kredis"
# gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
  gem "sqlite3", ">= 1.4"
end

group :production do
  gem 'pg'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
