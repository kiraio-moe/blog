source "https://rubygems.org"

group :jekyll_plugins do
#    gem "github-pages", "~> 227"
    # gem "jekyll-feed", "~> 0.17.0"
    # gem "jekyll-gist", "~> 1.5.0"
    # gem "jekyll-last-modified-at", "~> 1.3.0"
#    gem "jekyll-multiple-languages-plugin", "~> 1.8"
    gem "jekyll-paginate-v2", "~> 3.0.0"
#    gem "jekyll-polyglot", "~> 1.5.1" bug at Win platform
    gem "jekyll-redirect-from", "~> 0.16.0"
    gem "jekyll-sass-converter", "~> 3.0.0"
    gem "jekyll-seo-tag"
    gem "jekyll-sitemap"
    gem "jekyll-relative-links"
    gem "webrick"
    gem "sass-embedded", "~> 1.69.5"
    gem "google-protobuf", "~> 3.25.5"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
