source 'https://rubygems.org'

gem 'rails', '4.2.9'

gem 'pg', '~> 0.20.0'
gem 'sass-rails', '~> 5.0', '>= 5.0.4'
gem 'uglifier', '~> 3.2.0'
gem 'coffee-rails', '~> 4.2.1'
gem 'jquery-rails', '~> 4.3.1'
gem 'jquery-ui-rails'
gem 'turbolinks'

gem 'sprockets', '~> 3.7.1'

gem 'devise', '~> 3.5.7'
gem 'devise_security_extension'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook', '~> 4.0.0'
gem 'omniauth-google-oauth2', '~> 0.4.0'

gem 'kaminari', '~> 1.0.1'
gem 'ancestry', '~> 2.2.2'
gem 'acts-as-taggable-on'
gem 'responders', '~> 2.4.0'
gem 'foundation-rails', '~> 6.2.4.0'
gem 'foundation_rails_helper', '~> 2.0.0'
gem 'acts_as_votable'
gem 'ckeditor', '~> 4.2.3'
gem 'invisible_captcha', '~> 0.9.2'
gem 'cancancan', '~> 1.16.0'
gem 'social-share-button', '~> 0.10'
gem 'initialjs-rails', '0.2.0.5'
gem 'unicorn', '~> 5.3.0'
gem 'paranoia', '~> 2.3.1'
gem 'rinku', '~> 2.0.2', require: 'rails_rinku'
gem 'savon'
gem 'dalli'
gem 'rollbar', '~> 2.14.1'
gem 'delayed_job_active_record', '~> 4.1.0'
gem 'daemons'
gem 'devise-async'
gem 'newrelic_rpm', '~> 4.1.0.333'
gem 'whenever', require: false
gem 'pg_search'
gem 'sitemap_generator', '~> 5.3.1'

gem 'ahoy_matey', '~> 1.6.0'
gem 'groupdate', '~> 3.2.0' # group temporary data

gem 'browser'
gem 'turnout', '~> 2.4.0'
gem 'redcarpet', '~> 3.4.0'
gem 'rubyzip', '~> 1.2.0'

gem 'paperclip'
gem 'rails-assets-markdown-it', source: 'https://rails-assets.org'

gem 'cocoon'

gem 'graphql', '~> 1.6.3'
gem 'graphiql-rails', '~> 1.4.1'

group :development, :test do
  gem "bullet", '~> 5.5.1'
  gem "faker", '~> 1.7.3'
  gem 'byebug'
  gem 'factory_girl_rails', '~> 4.8.0'
  gem 'i18n-tasks', '~> 0.9.15'
  gem 'knapsack'
  gem 'launchy'
  gem 'letter_opener_web', '~> 1.3.1'
  gem 'quiet_assets'
  gem 'rubocop', '~> 0.49.1', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'capybara', '~> 2.14.0'
  gem 'coveralls', '~> 0.8.21', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'fuubar'
  gem 'poltergeist', '~> 1.15.0'
  gem 'rspec-rails', '~> 3.6'
end

group :development do
  gem "capistrano-rails", '~> 1.2.3', require: false
  gem 'capistrano', '~> 3.8.1', require: false
  gem 'capistrano-bundler', '~> 1.2', require: false
  gem 'capistrano3-delayed-job', '~> 1.7.3'
  gem 'mdl', require: false
  gem 'rvm1-capistrano3', require: false
  gem 'scss_lint', require: false
  gem 'web-console', '3.3.0'
end

eval_gemfile './Gemfile_custom'
