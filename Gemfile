source 'http://rubygems.org'
gemspec

gem "coveralls", "~> 0.7.0", require: false, group: :test
gem "pry-debugger", group: :development, platform: :mri

platforms :rbx do
  gem 'rubysl', '~> 2.0' # if using anything in the ruby standard library
  gem 'json', '~> 1.8.1'
  gem 'rubinius-coverage'
end

# XML parsing
gem 'ox', '~> 2.0.0', platform: :ruby
gem 'nokogiri', '~> 1.6.1', platform: :jruby
