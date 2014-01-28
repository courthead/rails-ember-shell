source 'http://rubygems.org'

# After updating gems that handle precompilation of assets (uglifier,
# sass-rails, ember-rails, etc), you may want to clear your cache thereby
# deleting existing precompiled assets: "rake tmp:clear".

# Running "gem cleanup" will uninstall old versions of gems no longer in use.
# This is helpful after you update gems. If you're wary about things, add the
# flag "--dryrun" at the command will instead provide a preview of what's to be
# removed.
#
# If you want to just start from scratch, you can erase the entire gemset (run
# "rvm gemset list" to make sure you have the right gemset selected, then run
# "rvm gemset empty"), then run "bundle install".

# Most of the version specifiers, like >= 1.0, are self-explanatory. The
# specifier ~> has a special meaning, best shown by example:
#   ~> 2.0.3 is identical to >= 2.0.3 and < 2.1
#   ~> 2.1 is identical to >= 2.1 and < 3.0
#   ~> 2.2.beta will match prerelease versions like 2.2.beta.12

# ----------

# Application
gem 'rails', '4.0.0.beta1' # Only upgrade deliberately; things will break.
gem 'devise' # After upgrading, you may want to update your Devise initializer.
gem 'ember-rails' # Use this to update Ember and Ember Data by running
                  # "rails generate ember:install --channel=canary". You can also
                  # specify "beta" or "release" as the channel.
gem 'figaro' # Run "rails g figaro:install" to generate /config/application.yml

# Server
gem 'passenger', '4.0.14' # Only upgrade deliberately; things will break.
gem 'mysql2'

# Asset Compilation
gem 'sass-rails'
gem 'therubyracer', platforms: :ruby
gem 'uglifier'
