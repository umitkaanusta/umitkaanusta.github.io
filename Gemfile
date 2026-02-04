source "https://rubygems.org"

# Jekyll version compatible with Ruby 2.6
gem "jekyll", "~> 3.9"

# Required for markdown processing
gem "kramdown-parser-gfm"

# Required for Ruby 2.6
gem "webrick", "~> 1.7"

# Lock ffi to version compatible with Ruby 2.6
gem "ffi", "< 1.17"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
