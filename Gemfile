source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '6.1.4.1'
gem 'puma', '5.5.1'
gem 'sass-rails', '6.0.0'
gem 'webpacker', '5.4.3'
gem 'turbolinks', '5.2.1'
gem 'jbuilder', '2.11.2'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

gem 'bootsnap', '1.9.1', require: false

group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug', '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '4.1.0'
  gem 'rack-mini-profiler', '2.3.3'
  gem 'listen', '3.7.0'
  gem 'spring', '3.0.0'
end

group :test do
  gem 'capybara', '3.35.3'
  gem 'selenium-webdriver', '3.142.7'
  gem 'webdrivers', '4.6.1'
  gem 'rails-controller-testing', '1.0.5'
  gem 'minitest', '5.14.4'
  gem 'minitest-reporters', '1.4.3'
  gem 'guard', '2.18.0'
  gem 'guard-minitest', '2.4.6'
end

group :production do
  gem 'pg', '1.2.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
