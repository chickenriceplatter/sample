require 'bundler/setup'
require_relative 'lib/sample'

desc "prints current date"
task :date do
  puts Date.today.strftime("%B %d, %Y")
end

desc "prints current Eastern time"
task :time do
  puts Time.now.strftime("%I:%M %P")
end

desc 'prints current time in LA'
task :la_time do
  puts Time.now.in_time_zone("America/Los_Angeles").strftime("%I:%M %P")
end

desc 'prints current time in Chicago'
task :chicago_time do
  puts Time.now.in_time_zone("America/Chicago").strftime("%I:%M %p")
end

desc 'prints current time in London'
task :london_time do
  puts Time.now.in_time_zone("Europe/London").strftime("%I:%M %p")
end

desc 'prints current time in Tokyo'
task :tokyo_time do
  puts Time.now.in_time_zone("Asia/Tokyo").strftime("%I:%M %p")
end
