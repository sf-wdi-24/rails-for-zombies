# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?
use validate in the model that would require a password with a specified length
validates_length_of :password, minimum: 6

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?
		Zombie has_many :tweets
		Tweet belongs_to :zombie,
3.  What does 'erb' stand for and how is it similar to handlebars?

erb stands for embedded ruby. similar to rails just by putting what we want to display in the html apge

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?
similar by having a database full of info, its actually a bit easier to use
