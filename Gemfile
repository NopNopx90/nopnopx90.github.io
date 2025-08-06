# frozen_string_literal: true

source "https://rubygems.org"

# Specify your Jekyll version. Using a specific version helps prevent unexpected breaking changes.
# You can find the latest stable version on rubygems.org (e.g., 4.3.3 as of my last update).
gem "jekyll", "~> 4.3"

# If you are using GitHub Pages, uncomment the following line and comment out the `jekyll` gem line above.
# gem "github-pages", group: :jekyll_plugins

# Jekyll plugins
gem "kramdown"
gem "rouge"
gem "jekyll-feed"
gem "jekyll-seo-tag"
gem "jekyll-paginate" # Used for pagination based on your _config.yml

# For development dependencies (e.g., if you need to run `bundle exec jekyll serve` locally)
group :development do
  gem "webrick" # Required for Jekyll 4.x on Ruby 3.0+ for local serving
end

# To ensure Bundler is available
gem "bundler"
