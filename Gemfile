source "https://rubygems.org"

# Gem do Jekyll
gem "jekyll", "~> 4.3.0"

# Tema padrão
gem "minima", "~> 2.5"

# Plugins essenciais para GitHub Pages
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Dependências do Windows e JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Dependência para melhor performance no Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Dependência para JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
