# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?
validate_length_of:password, minimum: 3 

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?
class Zombie <ActiveRecord::base
	has many:tweets
end
class Tweet < ActiveRecord::base
belongs_to:zombie
end

3.  What does 'erb' stand for and how is it similar to handlebars?
	Embedded Ruby. the erb page are views and templating the page with data from the db. the genral structure built with  html tags
4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?
the ActiveRecord take care of the putalize of the "Schemas" it built same way (models and collections).
The differance is that as I undeerstand ActiveRecord sitting in the middel between the db to the routs.
Also the models look like excel.
