# frozen_string_literal: true

source "https://rubygems.org"

# Specify the version of Jekyll you want to use
gem "jekyll", "~> 4.4.1"

# Plugins you might find useful
group :jekyll_plugins do
  gem "jekyll-timeago", "~> 0.13.1"  # Example plugin
  gem "jekyll-paginate"               # For paginating posts
  gem "jekyll-sitemap"                # For generating a sitemap
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end