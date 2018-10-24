source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

gem 'rails',       '~> 5.2.1'
gem 'pg',          '~> 1.1', '>= 1.1.3'
gem 'puma',        '~> 3.11'
# gem 'jbuilder',  '~> 2.5'
# gem 'redis',     '~> 4.0'
# gem 'bcrypt',    '~> 3.1.7'

# gem 'mini_magick', '~> 4.8'

# gem 'capistrano-rails', group: :development

gem 'bootsnap',    '>= 1.1.0', require: false

# ActiveAdmin.
gem 'devise',      '~> 4.5'
gem 'activeadmin', '~> 1.3', '>= 1.3.1'

# gem 'rack-cors'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  gem 'rubocop-rails_config',  '~> 0.2.5'
end

group :development do
  gem 'listen',                '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
