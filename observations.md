# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?

validates :password, length: {minimum: 5}

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?

class Zombie < ActiveRecord ::Base
	has_many = tweets
end

class Tweet < ActiveRecord ::Base 
	belongs_to :zombie
end 

3.  What does 'erb' stand for and how is it similar to handlebars?

erb stands for embedded Ruby and it similar to handlebars because it refers information from another file by using helpers. 


4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?

Both support CRUD, but ActiveRecord has keys 

