#!/usr/bin/env rake

begin
  require 'bundler/setup'
rescue LoadError
  puts 'You must `gem install bundler` and `bundle install` to run rake tasks'
end

require 'rake'
require 'rspec/core/rake_task'
require "bundler/gem_tasks"
RSpec::Core::RakeTask.new(:spec)
task :default  => :spec

