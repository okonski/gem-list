source :rubygems

def github(link, branch = 'master')
  return {:git => "git://github.com/#{link}", :branch => branch}
end

# Core
gem 'rails', '3.1.0.rc5'
  
## Database
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'mysql2'
  
gem 'devise'                # Authentication
gem 'slim'                  # Layout
gem 'sass'                  # SASS CSS
gem 'cancan'                # Permissions
gem 'acts_as_commentable'   # Comments
gem 'acts-as-taggable-on'   # Tags
gem 'vestal_versions'       # History, versions and changes
gem 'formtastic'            # Forms
gem 'validation_reflection' # Detect required fields for formtastic\
gem 'will_paginate'         # Pagination
gem 'simple-navigation'     # Multiple levels navigation
gem 'jquery-rails'          # jQuery
gem 'inherited_resources'   # RESTful controllers
gem 'has_scope'             # Scopes in urls for advanced queries
gem 'themes_for_rails'      # Theming
gem 'metric_fu'             # Metrics and code statistics
gem 'event_calendar'        # Calendar for views
gem 'mini_magick'           # Image rendering/manipulation
gem 'recaptcha'             # Bot prevention
gem 'prism'                 # Microformats parser
gem 'pacecar'               # Automatic scopes for models    

group :development, :test do
  gem 'rspec-core'         # RSpec testing framework
  gem 'rspec-rails'
  gem 'mocha'              # Mocking framework for RSpec
  gem 'cucumber-rails'     # Cucumber
  gem 'webrat'             # Testing selectors for veryfing views
  gem 'database_cleaner'
end
