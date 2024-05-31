source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.1.3"
# gem "sqlite3", "~> 1.4" #we are not going to use this for our productive scale, where multiple people hit it at the same time
gem "puma", ">= 5.0"
gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do #software for development
  gem "tabulo"
  gem "web-console"
  gem "sqlite3", "~> 1.4"
end

group :production do #software for production
  gem "pg"
end
