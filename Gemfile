source 'https://rubygems.org'

puppetVersion = ENV.key?('PUPPET_VERSION') ? ENV['PUPPET_VERSION'] : '~> 5.5.0'

gem 'rake'
gem 'puppet', puppetVersion
gem 'puppet-lint'
gem 'puppet-syntax'
gem 'rspec-puppet'
gem 'puppetlabs_spec_helper'

if RUBY_VERSION =~ /^1\./
  gem 'json_pure', '~> 1.8'
end

if RUBY_VERSION !~ /^1.8/
  gem 'puppet-blacksmith'
end
