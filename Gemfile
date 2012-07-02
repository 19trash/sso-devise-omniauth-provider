source 'http://rubygems.org'

gem 'rails'
gem 'execjs'
gem 'therubyracer'

# asset pipeline
group :assets do
  gem 'sass-rails'#, '~> 3.1.5.rc.2'
  gem 'coffee-rails'#, '~> 3.1.1'
  gem 'uglifier'#, '>= 1.0.3'
end

gem 'jquery-rails'

gem 'devise', git: 'git://github.com/plataformatec/devise.git'
gem 'omniauth'
# gem 'omniauth-facebook'
# gem 'omniauth-twitter'

group :test do
  gem 'sqlite3'
end

group :development do
    gem 'mysql2'
end

group :production do
  gem 'pg'
  gem 'activerecord-postgresql-adapter'
end
