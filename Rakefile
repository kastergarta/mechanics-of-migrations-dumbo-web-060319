require_relative './config/environment'
require 'sinatra/activerecord/rake'

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    Artist.create_table
  end
end

desc 'drop into the Pry console'
task :console => :environment do 
  Pry.start
end  