source 'https://rubygems.org'

# 使用 GitHub Pages 兼容的 Jekyll 版本
gem 'github-pages', group: :jekyll_plugins

# 核心插件（直接影响站点构建）
group :jekyll_plugins do
    gem 'jekyll-archives-v2'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-get-json'
    gem 'jekyll-imagemagick'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-regex-replace'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-tabs'
    # gem 'jekyll-terser', :git => "https://github.com/RobertoJBeltran/jekyll-terser.git" # ❌ 删除，因为 GitHub Pages 不支持
    gem 'jekyll-toc'  # 如果仍然报错，可以注释掉它
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'

    gem 'classifier-reborn'  # 用于分类
end

# 其他插件（外部数据获取或开发环境）
group :other_plugins do
    gem 'css_parser'
    gem 'feedjira'
    gem 'httparty'
    gem 'observer'       # jekyll-scholar 需要
    gem 'ostruct'        # jekyll-twitter-plugin 需要
    gem 'faraday-retry'  # 修复 Faraday 的依赖问题
end
