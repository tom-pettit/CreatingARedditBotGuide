# A short, simple guide on how to set up your own reddit bot.
Because I couldn't seem to find a good one when I needed it :/

**Step 1**
> Visit: https://old.reddit.com/prefs/apps/

**Step 2**
> Click 'Create Another App'

**Step 3**
> You will be presented with this screen:
[![NEW APP SCREEN](https://snipboard.io/FUY3wA.jpg)]()

- Name: Enter the name of what you want your bot to be called

> The next bit is slightly more complicated: 
- Web App: This is normally a web site that exists already, which allows the users to log into reddit, normally through OAuth.
- Installed App: This is something like a phone app that each user of the app installs on their phone, so it would use one API key, but there are lots of different devices making requests for lots of different users.
- Script: This is the easiest one, which doesn't have any session based on tokens (refresh and access tokens).

> If you're just making a bot for say moderation or responding to comments or posting on a subreddit then the *SCRIPT* category is the one for you! 
