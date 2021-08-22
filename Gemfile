source "https://rubygems.org"

ruby IO.read(File.expand_path("#{File.dirname(__FILE__)}/.ruby-version")).strip

gem "devise", ">= 4.7.3"
gem "devise-i18n", ">= 1.9.2"
gem "failbot_rails", ">= 0.5.0"
gem "faraday-http-cache"
gem "figaro"
gem "jquery-rails", ">= 4.4.0"
gem "octicons_helper", ">= 11.0.0"
gem "octokit"
gem "omniauth-github"
gem "pg"
gem "puma"
gem "rack-host-redirect"
gem "rails", ">= 6.0.4.1"
gem "sassc-rails", ">= 2.1.2"
gem "sitemap_generator"
gem "turbolinks"
gem "uglifier"

group :development, :test do
  gem "byebug"
end

group :development do
  gem "awesome_print"
  gem "listen"
  gem "rubocop"
  gem "spring"
  gem "spring-watcher-listen"
  gem "web-console", ">= 4.1.0"
end

group :production do
  gem "connection_pool"
  gem "dalli"
  gem "heroku-deflater"
  gem "kgio"
  gem "memcachier"
  gem "rack-cache"
end

group :test do
  gem "simplecov", require: false
  gem "vcr", require: false
end
