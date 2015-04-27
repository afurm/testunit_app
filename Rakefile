require 'rake'
require 'rake/testtask'
require 'ci/reporter/rake/test_unit'
#task :test do
#  ruby 'test/run_test.rb'
#end
#task :testunit => 'ci:setup:testunit'
Rake::TestTask.new do |t|
  t.libs << "test"
  t.test_files = FileList['test/test*.rb']
  t.verbose = true
end
