ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :environment do
  require_relative './config/environment'
end

desc 'Drop into the Pry console'
task :console => :environment do
  Pry.start
end
