source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '6.0.0'
# Use sqlite3 as the database for Active Record
gem 'mysql2'

# Use puma as the app server
gem 'puma', '~> 4.3'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
gem 'webpacker-react'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# access control
gem 'rack-attack'

# redirect trailing slash
gem 'rack-rewrite'

# js grobal variables
gem 'gon'

# Use ActiveStorage variant
gem 'image_processing', '~> 1.2'

# active storage
gem 'aws-sdk-s3', require: false

# KVS
gem 'hiredis'
gem 'redis', require: ['redis', 'redis/connection/hiredis']
gem 'redis-objects'

# template engine
gem 'slim-rails'

# auto Prefixer
gem 'autoprefixer-rails'

# meta
gem 'meta-tags'

# job controller
gem 'sidekiq'
gem 'sinatra', require: false
gem 'mini_scheduler'

# settings
gem 'rails-settings-cached', '0.7.2'

# fast json builder
gem 'jb'

# fast json parser
gem 'oj'

# fast detect spaces
gem 'fast_blank'

# localizer
gem 'enum_help'

# pagination
gem 'pagy'

# auth
gem 'sorcery'

# sitemap
gem 'sitemap_generator', require: false

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# profiling
gem 'scout_apm'

group :production do

  # for debug
  gem 'pry', require: false
  gem 'pry-rails', require: 'pry-rails/console'

  # Use Uglifier as compressor for JavaScript assets
  gem 'mini_racer', platforms: :ruby
end

# for development
local_gemfile = File.join(File.dirname(__FILE__), 'Gemfile.development')
instance_eval File.read(local_gemfile) if File.exist? local_gemfile
