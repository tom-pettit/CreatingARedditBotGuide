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

> I'm aware this is not the best explanation / the most in depth. So if you do want to find out more, visit: https://github.com/reddit-archive/reddit/wiki/OAuth2-App-Types#script-app. 

> If you're just making a bot for say moderation or responding to comments or posting on a subreddit then the *SCRIPT* category is the one for you! 

- Description: A short description of what your bot will do. (This doesn't have to be complicated, just a brief one will do!)

- About URL: If you have a website related to the app, then you can put the link of this website here. this is NOT REQUIRED.

- Redirect URI: This is the location that the authorization server will send to the user once the app has been successfully authorised, and granted an authorisation code or access token. 
> Now, I'm aware this is also another not great description, so for those who are interested, this explains it better: https://www.oauth.com/oauth2-servers/redirect-uris/.

> However, what most people use for this field is: http://localhost:8080!

- I know this may be a lot to read, and if you are revisiting this then you may not want to read through all this again, and so an example screenshot would be more useful. So here you go: 

[![TUTORIAL APP SCREEN](https://snipboard.io/vStXCo.jpg)]()



