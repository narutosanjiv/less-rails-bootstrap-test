source 'http://rubygems.org'

gem 'rails', '3.2.4'
gem 'sqlite3'
gem 'json'
gem 'jquery-rails', '>= 2.1.4'

group :assets do
  gem 'coffee-rails', '>= 4.0.0'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
  if ENV['LESS_RAILS_SOURCE']
    gem 'less-rails', :path => ENV['LESS_RAILS_SOURCE']
  else
    gem 'less-rails'
  end
  if ENV['LESS_RAILS_BOOTSTRAP_SOURCE']
    gem 'less-rails-bootstrap', :path => ENV['LESS_RAILS_BOOTSTRAP_SOURCE']
  else
    gem 'less-rails-bootstrap'
  end
end



