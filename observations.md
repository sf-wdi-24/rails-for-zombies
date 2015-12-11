# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?

validates_length_of :password, minimum: 6

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?

-one Zombie has many Tweets
class Zombie < ActiveRecord::Base
	has_many: tweets
end

-a Tweet belongs to a Zombie
class Tweet < ActiveRecord::Base
	belongs_to: zombie
end

3.  What does 'erb' stand for and how is it similar to handlebars?

erb stands for Embedded Ruby. It allows to render data from databases to the views.

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?

They both allow us to manipulate the data. ActiveRecord is easier to use, validation and data relationship are simple and easy to understand.
