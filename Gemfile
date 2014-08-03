source 'https://rubygems.org'

ruby '2.1.2'

# Server requirements
gem 'puma'

# Project requirements
gem 'rake'
gem 'rinku'

# Component requirements
gem 'slim'
gem 'sass'
gem 'erubis'

group :production do
  gem 'dalli'
end

group :development do
  gem 'pry-padrino'
  gem 'foreman'
end

# Test requirements
group :test do
  gem 'rspec'
  gem 'rack-test', :require => 'rack/test'
end

gem 'padrino', '0.12.2'
