require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  require 'irb'
  ARGV.clear
  IRB.start
  Artist.column_names
  a = Artist.new(name: 'Jon')
  a.age = 30
  a.save
end
