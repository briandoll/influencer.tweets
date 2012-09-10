# influencer.tweets

What are "influencers" saying about X on twitter, right now?  influencer.tweets shows recent tweets by influencers that mention a given topic.

## Why?

Because, surprisingly, no "social media" app solves for this yet. The current landscape of social media apps allow you to shout louder into multiple mouth pieces at once. They don't seem to (yet) help you actually have conversations with people.

I didn't want to miss an "important" tweet about something I care about.

## How to use it

You can download this code and run it directly from your computer by opening ``index.html`` in your browser of choice. It's best if you can host this code on a server somewhere intead, since you'll probably want to view these tweets on your phone.

To see tweets that mention ``coffee`` with more than 10,000 followers:

* http://host.tld/influencer.tweets/?q=coffee&c=10000

To see tweets that mention ``ruby`` with more than 5,000 followers:

* http://host.tld/influencer.tweets/?q=ruby&c=5000


**Note:** The Twitter API is rate limited to 150 queries per hour. Depending on the search terms, a single page view may make up to 11 queries. If the page goes blank, you're probably being rate limted. Be patient and try again later :)


## TODO

This is a silly hack of a project right now. I'd really prefer a company that builds social media tools solve for this in a better way.  To name a few:

* Let me specify a list of users to filter out (handy when searching for your company name, filter out employees)
* Push notifications to me rather than make this something I have to remember to use all the time
* Make the UI not horrible
* Pull-to-refresh on mobile
* Reply to tweets via a specified account
* Any way to deal with rate limiting?
* and on and on and on...
