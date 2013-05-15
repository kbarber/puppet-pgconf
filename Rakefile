require 'rake'
require 'rspec/core/rake_task'

task :default do
  sh %{rake -T}
end

desc 'Run all RSpec tests'
RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = ['--color']
end
