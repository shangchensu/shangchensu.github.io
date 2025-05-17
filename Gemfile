source 'https://rubygems.org'

gem "jekyll", "~> 4.4.1" # installed by `gem jekyll`
# gem "webrick"        # required when using Ruby >= 3 and Jekyll <= 4.2.2

gem "just-the-docs", "0.10.1" # pinned to the current release
# gem "just-the-docs"        # always download the latest release


gem 'wdm', '>= 0.1.0' if Gem.win_platform?

gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 2.0.6"
  gem "tzinfo-data"
end
