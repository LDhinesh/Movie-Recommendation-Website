Movie Recommendation Website made using Django and TheMovieDB API

It has 3 main components/pages:

1.Catalogue-Shows 10 most popular movies on the page according to TheMovieDB API

2.Chatbot-It answers the users query according to the keywords listed in the query. tell,cast,popularity,kids,genre,review,popular are the keywords used. Some examples of valid queries are-
  i.<i>Tell</i> me about the <i>movie</i> extraction
  ii.What is the <i>cast</i> of <i>movie</i> extraction
  iii.<i>popularity</i> of <i>movie</i> extraction
  iv.Suggest some movies for <i>kids</i>
  v.Give me some movies with <i>genre</i> Action
  vi.Give me a <i>Review</i> of the <i>movie</i> extraction
  vii.What are some <i>popular</i> movies right now
  
  <b>Note:</b> 1. Italicized words are neccessary keywords for valid queries
              2.You cannot mix 2 keywords in one query. For example: Tell me about a movie with genre Action. This is not valid as it uses                 both tell and genre keywords
  
 3.Personalised recommendation-This is a feature for only registered and logged in users. Users can input 5 movies of their preference and similiar 5 movies will be suggested to the user
