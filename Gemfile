source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'

# Windows 本地预览必需：tzinfo 需要额外数据源，
# 否则 jekyll 在 Windows 上启动时报 ZoneinfoDirectoryNotFound。
# 用 platforms 限定，Linux CI 上会被忽略。
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
