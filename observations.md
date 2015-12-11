# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?
You would type something like 

class Thisclass
	validates :password, presence: true
										length: { minimum: 6}
end

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?

class Zombie 
	has_many :tweets
end
class Tweet 
	belongs_to :zombie
end

3.  What does 'erb' stand for and how is it similar to handlebars? Embedded Ruby. It's similar because it allows for interpolation in rails.
 
4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different? ActiveRecord and MongoDB are similar in the way data can be stored within each DB. ActiveRecord seems to encapsulate many features that were separated between Mongo, MongoDB, and Mongoose. The centralized theme of things seems to make it easier to keep track of things.


