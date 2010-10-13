require 'rubygems'

require 'jeweler'
require 'yard'

YARD::Rake::YardocTask.new

Jeweler::Tasks.new do |gem|
  gem.name        = 'ts-datetime-delta'
  gem.summary     = 'Thinking Sphinx - Datetime Deltas'
  gem.description = 'Manage delta indexes via datetime columns for Thinking Sphinx'
  gem.email       = "pat@freelancing-gods.com"
  gem.homepage    = "http://github.com/freelancing-god/ts-datetime-delta"
  gem.authors     = ["Pat Allan"]
  
  gem.add_dependency 'thinking-sphinx', '>= 1.3.8'
  
  gem.add_development_dependency "rspec",    ">= 1.2.9"
  gem.add_development_dependency "yard",     ">= 0"
  gem.add_development_dependency "cucumber", ">= 0"
  
  gem.files = FileList[
    'lib/**/*.*',
    'LICENSE',
    'README.textile'
  ]
  gem.test_files = FileList[
    'features/**/*',
    'spec/**/*'
  ]
end

Jeweler::GemcutterTasks.new

# require 'tasks/testing'

task :default => :spec
