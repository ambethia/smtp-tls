require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "smtp-tls"
    gem.summary = "SMTP TLS (SSL) extension for Net::SMTP"
    gem.description = "A gem package for the SMTP TLS code that's been floating around for years"
    gem.email = "jasper@ambethia.com"
    gem.homepage = "http://github.com/ambethia/smtp-tls"
    gem.authors = ["Unknown", "Jason L Perry", "Elliot Cable"]
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

require 'rake/rdoctask'

Rake::RDocTask.new do |rdoc|
  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = "Net::SMTP"
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end