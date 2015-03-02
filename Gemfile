source 'https://rubygems.org'

gem 'rails', '~> 4.2.0'
gem 'rails-i18n'

gem 'sqlite3'
gem 'haml'
gem 'haml-rails'
gem 'jquery-rails-cdn'
gem 'simple_form'
gem 'cocoon'
gem 'bootstrap-sass'
gem "jquery-timepicker-rails"
gem 'date_validator'
gem 'carrierwave'
gem 'mini_magick'
gem 'json'
gem 'font-awesome-rails'

gem 'redcarpet'

gem "friendly_id", :git => 'https://github.com/FriendlyId/friendly_id.git' # rails4
gem 'kaminari'

# Mida provides Microdata format helpers for Schema.org
# But the dependency on blankslate raises a warning, which was later fixed in Builder, where it was extracted from
# The fork of blankslate fixes the warning and the fork of Mida uses Bundler and the .gemspec file as per modern gem design
gem 'blankslate'
gem 'green_monkey'
gem 'chronic_duration'

gem 'ri_cal'

gem 'oj'
gem 'fog'
gem 'elasticsearch-rails'
gem 'elasticsearch-model'

# Old assets group
gem 'sass-rails', '~> 4.0.3'
gem 'coffee-rails'
gem 'therubyracer', :platforms => :ruby
gem 'uglifier'
gem "compass-rails"
gem "autoprefixer-rails"

gem 'unicorn'
gem 'flowdock'

gem 'newrelic_rpm'
gem 'airbrake'

gem 'has_properties', :git => 'git@github.com:factorymedia/has_properties.git'
# gem 'has_properties', :path => '~/git/factory/has_properties'
gem 'byebug'
gem 'spring'
gem 'js-routes'
gem 'zeroclipboard-rails', '~> 0.1.0'

group :development do
  gem 'web-console', git: 'https://github.com/rails/web-console', branch: 'master'
  gem 'guard-rails'
  gem 'guard-spork'
  gem 'guard-cucumber'
  gem 'guard-rspec'
  gem 'thin'
  gem 'capistrano'
  gem 'bazaar' # For populating random events
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'selenium-webdriver'
  gem 'capybara-mechanize'
  gem 'poltergeist'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  gem 'simplecov', :require => false
  gem 'simplecov-rcov', :require => false
  gem 'webmock', :require => false
  gem 'excon' #, git: "https://github.com/geemus/excon.git"
  gem 'vcr'
  gem 'microdata'
  gem 'launchy'
  gem 'show_me_the_cookies'

end

group :production do
  gem 'passenger'
end
