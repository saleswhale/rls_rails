source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rack', '~> 2.2.20'
gem 'nokogiri', '~> 1.18.8'
gem 'net-imap', '~> 0.5.7'

# Declare your gem's dependencies in rls.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
group :development, :test do
    gem 'byebug'
    gem 'ruby-debug-ide'
    gem 'debase'
end