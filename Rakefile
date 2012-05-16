#!/usr/bin/env rake

require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

desc 'Run those specs'
task :spec do
  RSpec::Core::RakeTask.new(:spec) do |t|
    t.pattern    = 'spec/**/*_spec.rb'
    t.rspec_path = 'bundle exec rspec'
  end
end

task :default => :spec
