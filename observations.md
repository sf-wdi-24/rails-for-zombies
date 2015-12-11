# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?
		
 - validates :password, length: {is: 6}

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?

 - Zombie has_many :tweets
 - Tweet belongs_to :zombie

3.  What does 'erb' stand for and how is it similar to handlebars?

 - Embedded Ruby.  It allows for templating data on the view

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?

 - It allows manipulating data in the DB.  It uses SQL and a table system
