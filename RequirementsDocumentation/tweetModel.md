## Properties of tweet 
- tweet ID (unique, will receive from mongoDB)  
- User ID  (using this ID, we can fetch user details like, username, displayname, profile picture) 
- created_at (timestamp, can be generated in mongoDB)
- text written in tweet (what is written in tweet) 
- like count 
- array of user IDs who have liked the tweet


### Database structure
- All tweets can be stored in one collection




- references
    - [https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet](https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet)