source :rubygems

def github(link, branch = 'master')
  return {:git => "git://github.com/#{link}", :branch => branch}
end

# Core
gem 'rails', '3.0.3'
  
## Database
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'mysql2'
  
gem 'devise'     # Authentication
gem 'haml'
gem 'haml-rails' # View generator for scaffold
gem 'cancan'     # Permissions
gem 'acts_as_commentable' # Comments
gem 'acts-as-taggable-on' # Tags
gem 'vestal_versions', github('adamcooper/vestal_versions') # History, versions and changes
gem 'formtastic'            # Forms
gem 'validation_reflection' # Detect required fields for formtastic\
gem 'will_paginate'         # Pagination
gem 'simple-navigation'     # Multiple levels navigation
gem 'jquery-rails', '>= 0.2.6' # jQuery instead of Prototype
gem 'inherited_resources'   # RESTful controllers
gem 'has_scope'             # Scopes in urls for advanced queries
gem 'themes_for_rails', github('lucasefe/themes_for_rails') # Theming
gem 'metric_fu'             # Metrics and code statistics

group :development, :test do
  gem 'rspec-core'         # RSpec testing framework
  gem 'rspec-rails'
  gem 'mocha'              # Mocking framework for RSpec
  gem 'cucumber'           # Cucumber
  gem 'cucumber-rails'
  gem 'webrat'             # Testing selectors for veryfing views
  gem 'database_cleaner'
end
