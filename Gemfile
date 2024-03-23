# frozen_string_literal: true

source "https://rubygems.org"

<<<<<<< HEAD
gem "jekyll-theme-chirpy", "~> 5.3", ">= 5.3.0"

group :test do
  gem "html-proofer", "~> 3.18"
=======
gem "jekyll-theme-chirpy", "~> 6.5", ">= 6.5.4"

group :test do
  gem "html-proofer", "~> 4.4"
>>>>>>> chripy-starter/main
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
<<<<<<< HEAD
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
=======
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
>>>>>>> chripy-starter/main
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
<<<<<<< HEAD
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"
=======
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
>>>>>>> chripy-starter/main
