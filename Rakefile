# Rakefile
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('sundawg_responsys_client', '0.0.1') do |p|
  p.description    = "Ruby SOAP Client For Responsys API"
  p.url            = "http://github.com/SunDawg/responsys_client"
  p.author         = "Christopher Sun"
  p.email          = "christopher.sun@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = ['mocha >=0.9.12']
  p.runtime_dependencies = ['soap4r-ruby1.9 >=2.0.5', 'fastercsv >=1.5.4']
end
