source 'https://rubygems.org'

ruby '3.0.0'

gem 'jekyll', '~> 4.2.0'
gem 'webrick', '~> 1.7'
# To use GitHub Pages, remove the `gem 'jekyll'` above and
# uncomment this line:
#    gem 'github-pages', group: :jekyll_plugins
#  To upgrade, run `bundle update github-pages`
group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.12'
  gem 'jekyll-paginate'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.1', platforms: %w[mingw x64_mingw mswin]
