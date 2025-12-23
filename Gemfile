source "https://rubygems.org"

# 这是 GitHub Pages 的官方支持
gem "github-pages", "~> 232", group: :jekyll_plugins

# 指定兼容版本
gem "jekyll", "~> 4.3.3"  # GitHub Pages支持的版本
gem "jekyll-theme-hacker", "~> 0.2.0"

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]


group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# 指定支持的平台
platforms :ruby do
  # 这些gem在所有平台都可用
end

# 如果你在Windows开发，可以添加Windows特定平台
platforms :x64_mingw do
  # Windows特定依赖（可选）
  gem "wdm", "~> 0.1.1" if Gem.win_platform?
end