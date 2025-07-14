source 'https://rubygems.org'

ruby "2.2.3"

gemspec

gem "administrate-field-image", ">= 1.1.0"
gem "delayed_job_active_record", ">= 4.1.5"
gem "high_voltage"
gem "markdown-rails", ">= 2.0.2"
gem "pg"
gem "redcarpet"
gem "unicorn"

group :development do
  gem "web-console", ">= 3.0.0"
end

group :development, :test do
  gem "appraisal", ">= 2.2.0"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.7.6"
  gem "factory_girl_rails", ">= 4.6.0"
  gem "faker"
  gem "i18n-tasks", ">= 0.9.0"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5.0"
end

group :test do
  gem "ammeter", ">= 1.1.4"
  gem "database_cleaner"
  gem "formulaic", ">= 0.4.0"
  gem "launchy"
  gem "poltergeist", ">= 1.8.0"
  gem "shoulda-matchers", "~> 3.0.0", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end
