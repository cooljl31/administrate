source 'https://rubygems.org'

ruby "2.2.3"

gemspec

gem "administrate-field-image", ">= 1.0.0"
gem "delayed_job_active_record", ">= 4.1.5"
gem "high_voltage"
gem "markdown-rails"
gem "pg"
gem "redcarpet"
gem "unicorn"

group :development do
  gem "web-console", ">= 2.2.1"
end

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.7.6"
  gem "factory_girl_rails"
  gem "faker"
  gem "i18n-tasks"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5.0"
end

group :test do
  gem "ammeter"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "poltergeist"
  gem "shoulda-matchers", "~> 2.8.0", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end
