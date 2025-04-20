source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  # Plugins supported by GitHub Pages (these are included by default, but you can add more if supported)
  # gem "jekyll-seo-tag"
  # gem "jekyll-sitemap"
  # gem "jekyll-feed"
  # gem "base64" # Only if required and supported
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "webrick", "~> 1.8" # Needed for local development with Ruby 3+
