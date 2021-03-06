[![Code Climate](https://codeclimate.com/github/globalavocado/yelp-clone/badges/gpa.svg)](https://codeclimate.com/github/globalavocado/yelp-clone)

<h1>Yelp clone</h1>

<h2>Makers Academy week 9 - Ruby on Rails</h2>
Ruby on Rails version of the Yelp Restaurant review site. 

<strong>included features:</strong>
Facebook social login
star ratings
map locations

<h3>Technologies used</h3>
- ruby
- Rails
- RSpec
- Capybara
- Cucumber
- PostgreSQL
- Ajax
- Poltergeist
- Devise
- Omniauth
- Paperclip
- Gmaps
- Bootstrap framework (CSS3, HTML5, Javascript)

<h3>instructions</h3>
To run the Yelp clone, create a database 

~~~
  ... =# CREATE DATABASE "yelp_clone_test";
  ... =# CREATE DATABASE "yelp_clone_development";
  ... =# \q
~~~

install the gems:

~~~
	... $ bundle
~~~

then generate some database contents (creates 2 entries):

~~~
    ... $ bin/rake db:seed
~~~

install the gems and start the server:

~~~
	... $ rails s
~~~

Go to your browser and you should see the site at http://localhost:3000 
If not, check the port number in the command line.