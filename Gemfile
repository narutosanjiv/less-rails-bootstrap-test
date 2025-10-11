source 'http://rubygems.org'

gem 'rails', '5.0.0'
gem 'sqlite3'
gem 'json'
gem 'jquery-rails', '>= 4.0.1'

group :assets do
  gem 'coffee-rails', '>= 4.1.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
  if ENV['LESS_RAILS_SOURCE']
    gem 'less-rails', '>= 2.2.3', '>= 2.2.3', :path => ENV['LESS_RAILS_SOURCE']
  else
    gem 'less-rails'
  end
  if ENV['LESS_RAILS_BOOTSTRAP_SOURCE']
    gem 'less-rails-bootstrap', '>= 2.0.13', '>= 2.0.13', :path => ENV['LESS_RAILS_BOOTSTRAP_SOURCE']
  else
    gem 'less-rails-bootstrap'
  end
end



