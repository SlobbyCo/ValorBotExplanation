# Valor Bot

Valor Bot is a Discord Bot designed to provide an all-in-one experience for Riot's Games. We designed it in order 
to create a single bot that can cover all of your Riot Games needs without the hassle! 

## Functionality:

This bot provides information on any LoL summoner’s rank in both solo queue and flex queue. The bot also can retrieve a 
requested summoner’s rank in TFT. Using the bots "opt-in/opt-out" feature, users can request to be notified when a patch
note comes out for the following games: LoL, TFT, and Valorant. You can also request for ValorBot to use the opt in 
feature to grab live tweets from the main Riot Games twitter account and the main twitter accounts for the other 
respective games. A unique feature to ValorBot is our local leaderboard system, where players of LoL and TFT can create
a “group” of up to 15 summoners and they can see how they rank against their friends in solo queue. Groups of players 
can also refresh the ranks of all players within the group using a single command. 

## Upcoming Features:

We plan to provide support for both the leaderboards and rank retrieval as soon as the API is released for Valorant, 
and if/when a more robust API is released for Legends of Runeterra in the future.

This will show a list of all the commands that Rito bot currently offers and how to use them


## Valor Bot Main Help Commands
Please reference the setup commands if you this is your first time using Rito Bot on this server! Here are some 
acceptable forms of each game input: 

+ **League of Legends:** LoL, League, League of Legends, or lol
+ **Valorant:** val, Valorant, or valorant
+ **Teamfight Tactics:** TFT, Teamfight Tactics, Team fight Tactics, tft, team fight tactics or teamfight tactics
+ **Legends of Runeterra:** lor, LoR, Legends of Runeterra, or legends of runeterra


## Server Setup Commands 
These commands are for admins only

**?setregion region** - This command sets the default region for this server. Current options: na, euw, eune, oce, kr, jp, 
br, las, lan, ru, and tr (capatalization does not matter)

**?sendtweet** - Use this command to set up the text channel that you wish to receive
live tweets in, you will not receive these tweets until you run this command. If you
wish to change the channel simply run this command again.

**?sendpatch** - Use this command to set up the text channel that you wish to receive
live patch notes in, you will not receive these tweets until you run this command. If
you wish to change the channel simply run this command again.

**?stoptweets game** - This is used to disable live tweets for this game

**?stoppatch game** - This is used to disable live patch notes for this game


## Tweet Commands

**?tweets** - This lets you know which games have live tweets enabled on this server


## Patch Notes Commands
*Does not support Legends of Runeterra*

**?currentpatch game** - This is used to view the current patch of whichever game you put.

**?patch** - This lets you know which games have live patch notes enabled on this server


## League of Legends Commmands

**?rank summoner-name** -  Tells you the summoner's rank in
solo queue, flex queue, and even TFT! It will also let you know if they are in a live game

**?livegamelol summoner-name** - Will give detailed information on the league game that they are currently in, if they 
are in one.

**?clash** - This will display when the upcoming clash dates!

**?freechamps** - This will display all the current free champion rotation for all you norms players!

**?myregion** - Looks up the region of this server'


## Leaderboards 
*Only supported for League of Legends, use ?makegroup first!*

**?makegroup group-name** - Makes a group where you and 
your friends can track ranks and compete against eachother to see who comes out on top. 
Whatever name you choose will be how you see the leaderboard later so make sure to name 
it something you can remember.

**?addplayer summoner-name** - Adds a summoner to your group, only the group 
leader can do this!

**?leaderboard group-name** - Type the group name that you want to lookup, anyone can do 
this it does not have to be your group!


## Leaderboard Administrative Commands 
*make sure you are a group owner before using these commands*

**?mygroup** - Displays the leaderboard name that you own (if you own one).'

**?deleteplayer summoner name** - Deletes a summoner from your group, only the group 
leader can do this!

**?renamegroup new-group-name** - Type the new group name that you wish to use

**?deletegroup** - This deletes the group that you own!

