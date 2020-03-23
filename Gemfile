# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.20.0"
gem "decidim-conferences", "0.20.0"
# gem "decidim-consultations", "0.20.0"
# gem "decidim-initiatives", "0.20.0"

gem "bootsnap", "~> 1.3"

gem "puma", "~> 3.12.4"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.9"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", "0.20.0"
  gem "capistrano", "~> 3.10", require: false
  gem "capistrano-rails", "~> 1.4", require: false
  gem 'capistrano-rbenv', '~> 2.1', require: false
  gem 'capistrano-bundler', '~> 1.6', require: false
  gem 'capistrano-passenger'
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end
