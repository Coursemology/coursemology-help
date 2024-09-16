source "https://rubygems.org"
ruby RUBY_VERSION

# Jekyll version
gem "jekyll", "3.10.0"

# Default theme for Jekyll sites
gem "minima", "~> 2.0"

gem "kramdown-parser-gfm", "~> 1.1"

# Jekyll plugins
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
end

# Windows support
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

require 'uri'
require 'net/http'
require 'json'

uri = URI('https://pages.github.com/versions.json')
response = Net::HTTP.get_response(uri)
versions = JSON.parse(response.body)
gem 'github-pages', versions['github-pages']
