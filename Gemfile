# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.11.2"

# Uncomment the following line if you want to use decidim-assemblies plugin
gem "decidim-assemblies", "0.11.2"

gem "puma", "~> 3.0"
gem "uglifier", ">= 1.3.0"

gem "faker", "~> 1.8.4"

group :development, :test do
  gem "byebug", "~> 10.0", platform: :mri


  gem "decidim-dev", "0.11.2"
end

group :development do
  # gem "decidim-deploy-heroku", '0.0.1', git: "https://github.com/codegram/decidim-deploy-heroku.git"
  gem "letter_opener_web", "~> 1.3.0"
  gem "listen", "~> 3.1.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"
end

group :production do
  gem 'passenger'
  gem 'fog-aws'
  gem 'dalli'
  gem 'sendgrid-ruby'
  gem 'newrelic_rpm'
  gem 'lograge'
  gem 'sentry-raven'
  gem 'sidekiq'
end
