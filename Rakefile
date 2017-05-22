# !/usr/bin/env rake
require 'yamllint/rake_task'

desc 'Runs cookstyle tests'
task :cookstyle do
  sh 'chef exec bundle exec cookstyle'
end

task default: [:cookstyle]