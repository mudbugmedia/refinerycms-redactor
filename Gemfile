source 'https://rubygems.org'


# Declare your gem's dependencies in refinery_redactor.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

git "http://github.com/refinery/refinerycms", branch: "master" do
  gem "refinerycms"
  gem "refinerycms-testing"
end

group :development, :test do
  gem 'selenium-webdriver', '~> 2.43'
  gem 'sqlite3'
end

