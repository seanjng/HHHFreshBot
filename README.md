# HHHFreshBot

This bot compiles [Fresh] posts submitted to /r/hiphopheads.

Functionality:

* Saves [Fresh] posts to database, deletes them if they don't hit +25 after being 6 hours old
* Reads messages sent to inbox
	* If it's a subscribe request, it subscribes the user to either the daily or weekly round up (possible to subscribe to both if you send each one once)
	* If it's a unsubscribe request, it unsubscribes the user from both round ups
	* If it's something else, it forwards it to the admin for review
* Send out the daily round up to all subscribed users
* Send out the weekly round up to all subscribed users
* Post the weekly round up to /r/hiphopheads

This is automated using Heroku and Heroku Scheduler. Since I just finished writing the bot today, and have never used Heroku before I don't know if it'll be 100% free. I suspect that it should be given the way it's been set up. If it isn't, then I'll be sad.

If you want to subscribe, check out these links! - [[Daily](http://www.reddit.com/message/compose/?to=HHHFreshBot&subject=subscribe&message=daily)] [[Weekly](http://www.reddit.com/message/compose/?to=HHHFreshBot&subject=subscribe&message=weekly)]