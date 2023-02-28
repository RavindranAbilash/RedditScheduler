# Insatll dependence 

Go to https://www.python.org/downloads/ and download and install python

After that open the cmd and check the python install properly 

Then Run these 2 commends one by one in cmd.
  1. pip install --upgrade praw
  2. pip install pandas

# Setup

Go to your [app preferences](https://www.reddit.com/prefs/apps). Click the "Create app" or "Create another app" button. Fill out the form like so:

- **name:** PostScheduler
- **App type:** Choose the **script** option
- **description:** A versatile Python script for scheduling all sort of reddit posts.
- **about url:** https://github.com/ibid-11962/reddit-post-scheduler
- **redirect url:** http://localhost:8080

Hit the "create app" button. Make note of the client ID and client secret.

Edit the beginning of `postscheduler.py` to include your username, passwordm client ID and client secret.

# Scheduling Posts

Update the post.csv file according to your posts

