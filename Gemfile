source 'https://rubygems.org'

gem 'rake'

# style
gem 'foodcritic'
# https://github.com/bbatsov/rubocop/issues/2218
gem 'rubocop', '~> 0.33.0', require: false

# unit
gem 'rspec'
gem 'chefspec'
gem 'berkshelf'

# integration
gem 'serverspec'
gem 'test-kitchen'

group :'local-integration' do
  gem 'kitchen-docker'
  gem 'kitchen-vagrant'
end

group :'ci-integration' do
  gem 'kitchen-docker-api'
end

# publish
gem 'stove'
