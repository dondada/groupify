source 'https://rubygems.org'

group :development do
  gem 'pry'
end

group :test do
  gem 'coveralls', require: false
end

# Specify your gem's dependencies in groupify.gemspec
gemspec

platforms :jruby do
  gem "activerecord-jdbcsqlite3-adapter"
  gem "activerecord-jdbcmysql-adapter"
  gem "jdbc-mysql"
  gem "activerecord-jdbcpostgresql-adapter"
end

platforms :ruby do
  gem "sqlite3"
  gem "mysql2"
  gem "pg"
end
