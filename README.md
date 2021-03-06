TwitterClient
=============

Time spent: 6 hours spent in total

Completed user stories:
 
 * [x] User can sign in using OAuth login flow
 * [x] User can view last 25 tweets from their home timeline
    User should be able to see the user, body and timestamp for tweet
    User should be displayed the relative timestamp for a tweet "8m", "7h"
 * [x] User can load more tweets once they reach the bottom of the list using "infinite scroll" pagination
 * [x] User can compose a new tweet
    User can click a “Compose” icon in the Action Bar on the top right
    User will have a Compose view opened
    User can enter a message and hit a button to post to twitter
    User should be taken back to home timeline with new tweet visible
 * [x] User can switch between Timeline and Mention views using tabs.
   User can view their home timeline tweets.
   User can view the recent mentions of their username.
   User can scroll to bottom of either of these lists and new tweets will load ("infinite scroll")
 * [x] User can navigate to view their own profile
   User can see picture, tagline, # of followers, # of following, and tweets on their profile.
 * [x] User can click on the profile image in any tweet to see another user's profile.
   User can see picture, tagline, # of followers, # of following, and tweets of clicked user.
   Profile view should include that user's timeline
 
Notes:
There are a few fixes needed:
 * [x] When the list view item is being reused, I should clear the image right away, right now it switches from the old image to the new one.

Walkthrough of all user stories:

![Video Walkthrough](simpletwitter2.gif )
