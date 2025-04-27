source "https://rubygems.org"

# Use Jekyll 3.9 to be compatible with the Lanyon theme
gem "jekyll", "~> 3.9"

# Theme
gem "jekyll-theme-lanyon", "~> 1.1"

# Required for Jekyll 3.9 with newer Ruby versions
gem "kramdown-parser-gfm"

# Required for Ruby 3+
gem "webrick"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Match your .ruby-version file
ruby "3.3.6"