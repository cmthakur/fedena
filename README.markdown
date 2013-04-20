#Installation
  * 0. Ruby 1.8.7
  * 1. bundle install
  * 2. rake fedena:plugins:install_all
  * 3. rake db:setup
  * 
Opps error occured while running rake file then try this:
  gem update --system 1.5.3

Be sure mysql gem and server is installed

If you are a mac user then comment out this code from wickedpdf.rb in vendor/plugins directory
 if Platform.is_windows?
   include Win32PdfRenderer
  elsif Platform.is_linux?
   include NixPdfRenderer
  else
   raise "Unable to find Platform"
  end
 

#Fedena : Open source school management system

Project Fedena is the open source school management system based on Ruby on Rails. It is developed by a team of developers at Foradian Technologies. The project was made open source by Foradian, and is now maintained by the open source community. Fedena is the ideal solution for schools and campuses that want an easy means to manage all campus records.

The Project Fedena website http://www.projectfedena.org/ is the home to the developer community behind Fedena project. There you can find forums and bug tracker for Fedena.

#Demo
A demo website for Fedena has been set up at demo.projectfedena.org. You can log in with following usernames and passwords:

    * As admin -- username - admin, password - admin123
    * As student -- username - 1, password - 1123
    * As employee -- username - E1, password - E1123

#License

Fedena is released under the Apache License 2.0.

#Installation

Visit  http://projectfedena.org/install for detailed installation instruction.

#Community Support:

Visit www.projectfedena.org for community support.
