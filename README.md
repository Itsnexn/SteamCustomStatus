# nodejs Steam custom status "*Under test*"

This bot login into your account and change the status when you idle in steam ...



## Getting Started
For you to get started you need the following things
```
NODEJS
Your Shared Secret
```

### Installing

First off get your  Shared Secret. Read this page [HERE](https://github.com/SteamTimeIdler/stidler/wiki/Getting-your-%27shared_secret%27-code-for-use-with-Auto-Restarter-on-Mobile-Authentication)

Fill in config.json

After this open console, and write the following.
```
mkdir steam-custom-status
npm install steam-user
npm install steam-totp
```

After this make your way to this directory, and copy the following files into the directory.
```
bot.js
config.json
```

Once this is complete type the following into Command Prompt.


```
node bot
```

# Bat file 
if you want to make a bat file for easier usage you can just create a file with bat format than you just have to copy this :
```
node bot
pause
```



# donations

[![Steam Donate][steam-img]][steam-url]

<!-- Badge URLs -->

[steam-img]:  https://img.shields.io/badge/donate-Steam-lightgrey.svg?style=flat-square
[steam-url]:  https://steamcommunity.com/tradeoffer/new/?partner=953292535&token=YqArtQDn
