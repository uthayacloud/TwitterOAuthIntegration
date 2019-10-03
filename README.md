# TwitterOAuthIntegration

Step1: Authenticate User.

Step2: #GET statuses/home_timeline

        Returns a collection of the most recent Tweets and Retweets posted by the authenticating user and the users they follow
        
        #GET https://api.twitter.com/1.1/statuses/home_timeline.json
 
 Step3: #POST Post tweet on user twitter 
 
        #POST https://api.twitter.com/1.1/statuses/update.json
        
        @Params - status - required text
        


