rails-starter-minimized
=======================

Inspired by this Gist https://gist.github.com/josevalim/1942658

 Run this file with:

   bundle exec RAILS_ENV=production rackup -p 3000 -s thin

 And access:

   http://localhost:3000/hello/world

 We are using Bundler in this example, but we could also
 have used rubygems:

   require "rubygems"

   gem "actionpack"
   gem "railties"

   require "rails"
   require "rails/all"
 
 The following lines should come as no surprise. Except by
 ActionController::Metal, it follows the same structure of
 config/application.rb, config/environment.rb and config.ru
 existing in any Rails 3 app. Here they are simply in one
 file and without the comments.