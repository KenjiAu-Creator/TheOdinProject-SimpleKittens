The Odin Project Simple Kittens API
===========

This is a straightforward project where an Rails app was set up to be a data-producing API. 

Features
-----------

-Quick creation of kitten models and input into the database
-Responds to JSON queries made into the show and index actions

Installation
-----------

Download the files and run the database migration with
  
  rails db:migrate

To check the JSON queries fire up the IRB
  run $ require' rest-client'
  $ response = RestClient.get("http://localhost:3000/kittens", :accept => :json)
  $ puts response.body

Contribute
-----------


Support
-----------


License
-----------

The project is licensed under the BSD license.