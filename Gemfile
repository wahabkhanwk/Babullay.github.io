source "https://rubygems.org"
ruby "3.1.4"
# Updated Jekyll version for compatibility with Ruby 3.3.0
gem "jekyll", "~> 4.2.0"

# Plugins and dependencies
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-compose", "~> 0.13.0"
  gem "jekyll-postfiles", "~> 3.1"
  gem "jekyll-spaceship"
end

# Required for Ruby 3.3.0 compatibility
gem "webrick", "~> 1.8"

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "wdm", "~> 0.1.0" if Gem.win_platform? 

# Ensuring compatibility with latest bundler
gem "bundler", "~> 2.4"
