source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.7.1"
gem "rails", "5.2.0"

gem "yajl-ruby", "< 1.3.1"
gem "psych", "~> 3.1.0"
gem "yaml_db"
gem "rails-erd"
gem "pdf-reader"
gem "cloudinary"
gem "watir"
gem "nokogiri", ">=1.5.9"
gem "httparty"
# gem 'pygments.rb', '~> 0.6.0'
gem "redcarpet", "~> 3.2.2"
gem "pry"
gem "bootstrap-sass"
# gem 'geocoder'

gem "pg", "~> 1.5.8"
gem "puma", "~> 3.0"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
# gem 'coffee-rails', '~> 4.2'
gem "jquery-rails"
gem "jbuilder", "~> 2.5"
gem "capistrano-rails"
gem "capistrano-bundler"
gem "capistrano-passenger"
gem "capistrano", "~> 3.7.2"
gem "capistrano-rvm"
gem "ed25519"
gem "bcrypt_pbkdf"
gem "standard"

gem "executable-hooks", "1.6.0"
gem "ffi", "1.13.1"

group :development, :test do
  # gem 'byebug', platform: :mri
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.1.5"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
