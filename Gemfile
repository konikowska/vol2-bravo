source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',                   '~> 5.1.5'
gem 'pg',                      '>= 0.18', '< 2.0'
gem 'puma',                    '~> 3.7'
gem 'sass-rails',              '~> 5.0'
gem 'uglifier',                '>= 1.3.0'
gem 'turbolinks',              '~> 5'
gem 'bootstrap',               '~> 4.0.0'
gem 'jquery-rails'
gem 'devise'
gem 'haml'
gem 'haml-rails'
gem 'draper'
gem "font-ionicons-rails"
gem 'dotenv-rails'

group :development, :test do
  gem 'byebug',                platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara',              '~> 2.13'
  gem 'selenium-webdriver'
  gem 'rspec-rails',           '~> 3.7'
  gem 'factory_bot_rails',     '~> 4.0'
  gem 'pry-rails'
  gem 'faker'
  gem 'rubocop', '~> 0.52.1', require: false
end

group :development do
  gem 'web-console',           '>= 3.3.0'
  gem 'listen',                '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'shoulda-matchers',      '~> 3.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
