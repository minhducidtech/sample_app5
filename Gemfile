source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
gem "rails", "~> 5.0.1"
gem "bcrypt", "3.1.11"
gem "bootstrap-sass", "3.3.7"
gem "sqlite3"
gem "puma", "~> 3.7"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "jquery-rails", "4.3.1"

group :development, :test do
  gem "autoprefixer-rails"
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "better_errors"
  gem "brakeman", require: false
  gem "bundler-audit"
  gem "capybara", "~> 2.13"
  gem "database_cleaner"
  gem "eslint-rails"
  gem "factory_girl_rails"
  gem "guard-rspec", require: false
  gem "jshint"
  gem "nokogiri"
  gem "rack", "~> 2.0.1"
  gem "railroady"
  gem "rails_best_practices"
  gem "reek"
  gem "rspec"
  gem "rspec-collection_matchers"
  gem "rspec-rails"
  gem "rubocop", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "scss-lint", require: false
  gem "scss_lint_reporter_checkstyle", require: false
  gem "selenium-webdriver"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "web-console", ">= 3.3.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "guard", "2.13.0"
  gem "guard-minitest", "2.4.4"
  gem "minitest-reporters", "1.1.14"
  gem "rails-controller-testing", "1.0.2"
  gem "shoulda-matchers"
  gem "simplecov-json"
  gem "simplecov-rcov", require: false
end

group :production do
  gem "pg", "0.18.4"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Added at 2017-07-06 15:10:43 +0700 by minhduc:
gem "rails-ujs", "~> 0.1.0"
