source "https://rubygems.org"

# Specify the compatible Ruby version
ruby "3.3.0"

# Jekyll version compatible with Ruby 3.3.0
gem "jekyll", "~> 4.3.2"

# Jekyll plugins
group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.17'
  gem 'jekyll-sitemap', '~> 1.4'
  gem 'jekyll-compose', '~> 0.13.0'
  gem 'jekyll-postfiles', '~> 3.1'
  gem 'jekyll-spaceship'
end

# Webrick is required for serving Jekyll locally
gem "webrick", "~> 1.8"

# Ensure compatibility with Windows if needed
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Optional: Performance booster for watching directories on Windows
gem "wdm", "~> 0.1.1" if Gem.win_platform?
