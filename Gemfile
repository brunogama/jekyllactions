source "https://rubygems.org"

# Use GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Required for Jekyll with newer Ruby versions
gem "kramdown-parser-gfm"
gem "webrick"

# Add remote theme plugin
gem "jekyll-remote-theme"

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