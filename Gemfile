source "https://rubygems.pkg.github.com/getvenga" do
  gem "mimemagic", "0.3.6"
end

source "https://rubygems.org"

gemspec

gem 'sqlite3', '~> 1.3.8', :platforms => :ruby
gem 'pry'

# Hinting at development dependencies
# Prevents bundler from taking a long-time to resolve
group :development, :test do
  gem 'activerecord-import'
  gem 'mime-types'
  gem 'builder'
  gem 'rubocop', require: false
  gem 'rspec'
end
