# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png"> Observations

1.  How would you validate that a password has a length of six characters?
- validates_length_of :password, minimum: 6

2.  How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?
- Zombie has_many :tweets
- Tweet belongs_to :zombie, :foreign_key => :user_id

3.  What does 'erb' stand for and how is it similar to handlebars?
- embedded ruby, it allows data to be passed to the view (similar to handlebars)

4.  How is using ActiveRecord similar to your experience with MongoDB?  How is it different?
- It's similar in that you can query specific information, it's different in that it abstracts away some of the technical query (it's also different if ActiveRecord is using a relational-db)