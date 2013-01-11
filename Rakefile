require 'rubygems'  
require 'rake'  
require 'echoe'  
  
Echoe.new('pi_piper', '1.0.1') do |p|  
  p.description     = "Event driven Raspberry Pi GPIO library"  
  p.url             = "http://github.com/jwhitehorn/pi_piper"  
  p.author          = "Jason Whitehorn"  
  p.email           = "jason.whitehorn@gmail.com"  
  p.ignore_pattern  = ["examples/*"]  
  p.development_dependencies = []  
end  
  
Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }  