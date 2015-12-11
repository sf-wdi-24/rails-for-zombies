# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?

validates_length_of :password, minumum: 6

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?

class Zombie < ActiveRecord::Base

app/models/zombie.rb
has_many : tweets
end 

3.  What does 'erb' stand for and how is it similar to handlebars?

embedded ruby code - does client side templating like handlebars

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?

ActiveRecord feels more complex at first attempt, but its too early to say. 
