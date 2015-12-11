# Observations

**How would you validate that a password has a length of six characters?**

```ruby
validates_length_of :password, minimum: 6
validates :password, length: {minimum: 6}
```

**How would you create a relationship where one Zombie has many Tweets and that a Tweet belongs to a Zombie?**

```ruby
class Zombie < ActiveRecord::Base
	has_many :tweets
end

class Tweet < ActiveRecord:: Base
	belongs_to :zombie
end
```

**What does 'erb' stand for and how is it similar to handlebars?**

ERB stands for embedded Ruby.
It is similar to handlebars in that it allows you to incorporate information from the database in the html view.

**How is using ActiveRecord similar to your experience with MongoDB?  How is it different?**

ActiveRecord and MongoDB are both database systems for managing data.  The commands are very similar.  ActiveRecord has better documentation.  It is a little simpler to use.