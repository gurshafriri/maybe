source "https://rubygems.org"

ruby "3.3.0"

# Rails
gem "rails", github: "rails/rails", branch: "main"

# Drivers
gem "pg", "~> 1.5"
gem "redis", ">= 4.0.1"

# Deployment
gem "puma", ">= 5.0"
gem "bootsnap", require: false

# Assets
gem "importmap-rails", ">= 2.0.2"
gem "propshaft", ">= 0.9.0"
gem "tailwindcss-rails", ">= 2.3.0"
gem "lucide-rails", github: "maybe-finance/lucide-rails"

# Hotwire
gem "stimulus-rails", ">= 1.3.4"
gem "turbo-rails", ">= 2.0.5"

# Background Jobs
gem "good_job", ">= 3.26.0"

# Other
gem "bcrypt", "~> 3.1.7"
gem "inline_svg"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "faraday"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "dotenv-rails", ">= 3.0.3"
  gem "letter_opener"
  gem "i18n-tasks", ">= 1.0.14"
end

group :development do
  gem "web-console", ">= 4.3.0"
  gem "hotwire-livereload", ">= 1.3.2"
  gem "ruby-lsp-rails", ">= 0.3.2"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
