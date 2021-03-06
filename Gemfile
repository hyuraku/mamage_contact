source 'https://rubygems.org'
ruby '2.7.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3.3'
gem "activerecord", ">= 6.0.3.5"
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.12'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 6.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'html2slim'

gem 'slim-rails'

gem 'slim'

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'

  gem 'rspec-rails','3.6.0'
end

group :test do
  gem "rspec"
  gem "rspec_junit_formatter"

  gem 'rails-controller-testing'
end

gem 'faker'

gem "bootstrap-sass", ">= 3.4.1"
gem 'jquery-rails'

gem 'paperclip', '~> 6.1'
gem 'jasny-bootstrap-rails', '~> 3.1', '>= 3.1.3'

group :development do
  gem 'bullet'

  gem 'guard', '~> 2.14.0'
  gem 'guard-rspec', '~> 4.7.2'
  gem 'guard-cucumber', '~> 2.1.2'
  gem 'annotate'
end

gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'

gem "devise", ">= 4.6.0"

gem 'pundit'

gem 'rake', '>= 2.0.6', '< 13.0'

gem 'toastr-rails'
gem "nokogiri", ">= 1.11.0.rc4"
gem "loofah", ">= 2.2.3"
gem "rack", ">= 2.0.6"
gem "yard", ">= 0.9.20"

gem 'pagy', '>= 3.10' 
