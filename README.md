# Cat
Discord.js bot with moderation and leisure features.
## Planned features
- ~~Ask command, gives a randomized and somewhat humourous answer to any question in the world.~~
- ~~Moderation functions, kicking, banning, warning and role management of users in the server.~~
- ~~User join log and deleted message log.~~
- Implementing a starred message program, such as a bot would provide like Starboard.
- Music and audio engine to play local .flac and .mp3 files in the bot's folder as well as YouTube audio streaming features.

# Adding the bot to your server
If you'd like to add the bot to your server, please go to https://discordapp.com/deadlink to invite it. Beware that you'll need Manage Server permissions. Also beware that the bot goes offline every once in a while, since it is self hosted. The more servers it is in, the more stress it will endure.. I am currently not fully able to host the bot 24/7. Hopefully in the future this will change. I would **strongly** recommend hosting it yourself, which takes a minimal amount of knowledge in Git, as well as your traditional Terminal and cmd. It is fairly easy to keep updated and does not require too much attention as long as you keep the prompt up and running with a strong network connection. If there ever is bug issues you are unable to solve, please send me an email at leidentaysarconah@gmail.com, or more traditionally, my discord handle is Leiden Arnesson#1807.

## Installation and Running of the bot on your server (hosting it yourself)
This bot will need some basic dependencies to run. It requires [node.js](https://nodejs.org/en/download/), [git](https://git-scm.com/downloads), and [yarn](https://yarnpkg.com/en/docs/install). 

You can use this option if you are not happy with dealing with regular bot outages. At this time, the bot is still in development. You'll have to create a bot user in Discord, which isn't that hard to do. (https://discordpy.readthedocs.io/en/rewrite/discord.html) Use at your own risk. I am not responsible for any incidents that are caused by this bot. If there is any bugs with the bot, or you need help installing it, please send me an email at leidentaysarconah@gmail.com, or by Discord DM to Leiden Arnesson#1807.


**I recommend downloading the version of the bot via source code or by git. I always will update the git first, and the zip file in the releases will be behind. To have all the latest commands, please clone via git.**

**Make sure you have Node.js, Git and yarn installed before beginning these next steps.**
To download the latest **stable** version of the bot via a .zip release file, please go here:
https://github.com/ldeon/Cat-DiscordBot/releases/latest

To download the **stable** version of the bot via git; i.e. the version the official bot is running, run the following in a terminal:
```bash
git clone https://github.com/ldeon/Cat-DiscordBot.git
```

Having downloaded the bot, download the node dependencies:
```bash
yarn install
```
Then to start the bot (This uses `nodemon`):
```bash
yarn start
```
If you want to run it in the background with `screen` you can use `yarn background` instead.

# Configuration
**Step One**
Once you have created your bot user, and selected your desired avatar and username, copy the bot user's token. Please, **DO NOT SHARE THE TOKEN.** It will put you, your friends and your entire server at risk if it leaks out. Immediately reset the token as soon as you find out it has been compromised.
