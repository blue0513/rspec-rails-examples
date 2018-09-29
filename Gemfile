source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails'

gem 'coffee-rails'
gem 'devise'
gem 'jquery-rails'
gem 'nokogiri'
gem 'sass-rails'
gem 'sqlite3'
gem 'turbolinks'
gem 'uglifier'
gem 'symmetric-encryption'

gem 'quiet_assets', group: :development

group :development, :test do
  gem 'byebug' # Call 'byebug' in code to stop execution and get a debugger console
  gem 'capybara'
  # gem 'chromedriver-helper' # helps with using Chrome in feature specs
  gem 'factory_girl_rails'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-rescue'
  gem 'pry-stack_explorer'
  gem 'puffing-billy'
  gem 'rspec-rails'
  gem 'selenium-webdriver' # used by JavaScript-dependent feature specs (`js: true`)
  gem 'spring' # Spring background-runs app in dev for speed
  gem 'spring-commands-rspec' # Enable Spring for RSpec
  gem 'bootsnap', require: false
  gem 'parallel_tests'
end

group :development do
  gem 'web-console', '~> 2.0' # Access IRB on error pages or by <%= console %> in views
end

group :test do
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'poltergeist' # helps with using PhantomJS headless browser in feature specs
  gem 'shoulda-matchers'
  gem 'vcr'
  gem 'webmock'
end
