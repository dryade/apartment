source "http://rubygems.org"

gem 'rails', '~> 3.1.2'
gem 'rake', '~> 0.8.7'
gem 'rspec', '~> 2.6.0'
gem 'rspec-rails', '~> 2.6.1'
gem 'capybara', '1.0.0'
gem 'delayed_job', '~> 2.1.4'

platforms :jruby do
  gem 'activerecord-jdbcpostgresql-adapter', :git => 'git://github.com/dryade/activerecord-jdbc-adapter.git'  
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'activerecord-jdbcmysql-adapter'
  gem 'jruby-openssl'
end

platforms :ruby do
  gem 'pg', '~> 0.11.0' 
  gem "silent-postgres", "~> 0.1.1"
  gem 'mysql2', '~> 0.3.7'
  gem 'sqlite3'
end
