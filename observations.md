# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?

validates_length_of :password, minimum: 6

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?
	class Zombie < ActiveRecord::Base
			Zombie has_many :tweets
	end

	class Tweet < ActiveRecord::Base
			Tweet belongs_to: zoombie
	end

3.  What does 'erb' stand for and how is it similar to handlebars?
	erb stands for 'Embeded RuBy'.  Acts like Handlebars by templating on server side for HTML display

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?
	It is also a DB where we can manipulate the data. The models look more like tables. seems to be easier to use.
