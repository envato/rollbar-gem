# This file was generated by Appraisal

source 'https://rubygems.org'

is_jruby = defined?(JRUBY_VERSION) || (defined?(RUBY_ENGINE) && RUBY_ENGINE == 'jruby')

gem 'activerecord-jdbcsqlite3-adapter', :platform => :jruby
gem 'appraisal'
gem 'jruby-openssl', :platform => :jruby
gem 'rails', '4.2.3'
gem 'rake'
gem 'rspec-rails', '~> 3.4'
gem 'sqlite3', :platform => [:ruby, :mswin, :mingw]

gem 'oj', '~> 2.12.14' unless is_jruby

if RUBY_VERSION > '1.8.7' && RUBY_VERSION < '2.2.2'
  gem 'sidekiq', '>= 2.13.0', '< 5.0'
else
  gem 'sidekiq', '>= 2.13.0'
end

platforms :rbx do
  gem 'minitest'
  gem 'racc'
  gem 'rubinius-developer_tools'
  gem 'rubysl', '~> 2.0' unless RUBY_VERSION.start_with?('1')
end

if RUBY_VERSION.start_with?('1.9')
  gem 'sucker_punch', '~> 1.0'
elsif RUBY_VERSION.start_with?('2')
  gem 'sucker_punch', '~> 2.0'
end

gem 'database_cleaner', '~> 1.0.0'
gem 'delayed_job', :require => false
gem 'generator_spec'
gem 'girl_friday', '>= 0.11.1'
gem 'redis'
gem 'resque'
gem 'shoryuken'
gem 'sinatra'

gemspec
