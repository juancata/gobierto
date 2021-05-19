# frozen_string_literal: true

source "https://rubygems.org"

gem "actionpack-action_caching", ">= 1.2.1"
gem "active_model_serializers", ">= 0.10.12"
gem "bcrypt", "~> 3.1.0"
gem "cookies_eu", ">= 1.7.7"
gem "dalli"
gem "hashie"
gem "ine-places", "0.3.0"
gem "jbuilder", "~> 2.5"
gem "mechanize", ">= 2.8.0"
gem "meta-tags", ">= 2.14.0"
gem "paper_trail"
gem "paranoia"
gem "pg", "~> 1.1"
gem "rails", "~> 6.0", ">= 6.0.3.6"
gem "redcarpet", require: true
gem "responders", ">= 3.0.1"
gem "rollbar"
gem "ruby_px"
gem "before_renders"
gem "bootsnap"
gem "truncate_html"
gem "rake", "~> 13.0"

# Frontend
gem "i18n-js", ">= 3.0.0.rc11" # required to i18n-tasks
gem "font-awesome-sass", "~> 5.6" # required until FA moved to npm

# Webpack
gem "webpacker", "~> 5.2", ">= 5.2.1"

# Elasticsearch
gem "elasticsearch", "~> 6.0", ">= 6.0.2"
gem "elasticsearch-extensions", "~> 0.0.27"

# Background processing
gem "sidekiq", "~> 5.2.7"
gem "sidekiq-monitor-stats"

# AWS SDK client
gem "aws-sdk-s3", "~> 1"

# AWS SES client
gem "aws-ses", git: "https://github.com/zebitex/aws-ses.git", ref: "78-sigv4-problem"

# Calendar view component
gem "simple_calendar", "~> 2.4", ">= 2.4.1"

# Search client
gem "pg_search", "2.3.5"

# Search client indexing sanitizer
gem "rails-html-sanitizer", ">= 1.3.0"

# Pagination
gem "kaminari", "~> 1.2", ">= 1.2.1"

# Captcha
gem "invisible_captcha", ">= 1.1.0"

# Redis
gem "redis", "~> 4.0"

# Translations
gem "json_translate", "~> 4.0"
gem "route_translator", ">= 10.0.0"

# Liquid
gem "liquid", "~> 4.0"
gem "liquid-rails", git: "https://github.com/maierru/liquid-rails.git"

# Google API
gem "geocoder"
gem "google-api-client"

# Microsoft Exchange calendars
gem "exchanger", ">= 0.3.0"

# Web Services: Alcobendas, Valencia
gem "savon", "~> 2.12.0"

# Image management
gem "cloudinary"

# Gobierto data
gem "gobierto_data", git: "https://github.com/PopulateTools/gobierto_data.git"

# API
gem "rubyXL", ">= 3.4.17"

# Performance
# TODO: v3 raises a middleware error
gem "appsignal", "= 3.0.3"

# Auth strategies
gem "net-ldap"
gem "ladle"

# Detect encoding
gem "charlock_holmes"

# CORS support
gem "rack-cors"

# Redirections
gem 'rack-rewrite'

group :development, :test do
  gem "byebug", platform: :mri
  gem "i18n-tasks", ">= 0.9.34"
  gem "spring"
  gem "puma"
end

group :test do
  gem "capybara", ">= 3.35.3"
  gem "capybara-email", ">= 3.0.2"
  gem "simplecov"
  gem "simplecov-cobertura"
  gem "launchy"
  gem "minitest"
  gem "minitest-reporters"
  gem "minitest-retry"
  gem "minitest-stub_any_instance"
  gem "minitest-stub-const"
  gem "minitest-ci"
  gem "mocha"
  gem "selenium-webdriver"
  gem "spy"
  gem "timecop"
  gem "vcr"
  gem "webmock"
end

group :development do
  gem "rubocop"
  gem "listen"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "foreman"
  gem "rb-readline"
end
