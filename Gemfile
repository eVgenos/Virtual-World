source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Rails and DB
ruby '2.4.0'
gem 'rails', '~> 5.0.4'
gem 'pg', '~> 0.18'
gem 'pg_search'

# Assets
gem "rolify"
gem 'cancancan', '~> 1.10'
gem 'devise'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'sass-rails', '~> 5.0'
gem 'rspec-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'font-awesome-rails', '4.7.0.1'
gem "slim-rails"
gem 'simple_form'
gem 'puma', '~> 3.0'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
