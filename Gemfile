source "https://rubygems.org"

gem "fastlane"

# builds the file path for fastlane/Pluginfile
plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
# This line tells Fastlane to load and evaluate the Pluginfile and ensures that any plugins specified there are loaded and made available to Fastlane
eval_gemfile(plugins_path) if File.exist?(plugins_path)
