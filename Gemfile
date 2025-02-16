# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
gem 'webrick'
gem 'sinatra'

group :jekyll_plugins do
  gem 'jekyll-archives'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
  gem 'jekyll-gist'
  gem 'jekyll-feed'
  gem 'jemoji'
end