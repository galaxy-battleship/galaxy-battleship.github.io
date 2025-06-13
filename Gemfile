# frozen_string_literal: true

source "https://rubygems.org"

ruby '3.1.6'

gem "jekyll", "~> 4.4", ">= 4.4.1"
gem "jekyll-theme-chirpy", "~> 7.3", ">= 7.3.0"

gem "public_suffix", "~> 6.0"

gem "google-protobuf", "~> 4.31", ">= 4.31.1"
gem "jekyll-sass-converter", "~> 3.1"
gem "rouge", "~> 4.5", ">= 4.5.2"

group :test do
  gem "html-proofer", "~> 3.18"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", install_if: Gem.win_platform?

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"

