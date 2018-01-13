# socialAnalytics-challange

Note:

There are 2 parts to this project
1. Do a sentiment Analysis of different media sources using the tweets
2. Create two Twitter bots and perform a visualized sentiment analysis of a Twitter account's recent tweets. 
One Bot requests the other Bot to do a sentiment analysis of a given Twitter user and the 2nd Bot performs the analysis, creates a plot and posts the image as a response to the Bot1's tweet.

In order to do that exercise, we need to create 2 twitter accounts and then create an app within each account.
Twitter then generates 4 Keys:
consumer_key
consumer_secret
access_token
access_token_secret

I have saved these keys in separate files named account1.yaml and account2.yaml. I have then added these files to .gitignore file.
And then I have used yaml module, to access these keys in my code.


