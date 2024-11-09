*DiscordBot*

DiscordBot is a free, open-source, extensible bot for Discord servers, built on top of discord.js. This bot is generally self-hosted either on a dedicated server (like a Raspberry pi) or general cloud hosting like AWS etc. You can think of this bot as privacy focused as you are in total control of the code, so you can be sure that your information is secure.

*Features:*
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This bot has been in development since 2015 and has accumulated a ton of commands. Here are a few highlights:

__General Commands__
**!help [command]** -> Lists all commands or just help for one command.

**!gif query** -> Returns a gif connected to search query. Example = !gif dogs

**!image query** -> Returns an image from Google Images (careful, no adult filter) Example: !image dogs

**!youtube query** -> Returns a youtube link. Example: !youtube Fortnite

**!wiki query** -> Returns the summary of the first search result on Wikipedia.

**!wolfram query** -> Queries Wolfram Alpha for results.

**!meme memetype "text1" "text2"** => Returns a meme image. notice the quotes around text, they are vitally important!

**!say text** -> Make the bot say text, useful mostly in combination with alias.

**!alias **-> Create custom shorthand commands in Discord!

**!invite** -> Generates an invite link for the Bot to join the requested server, easy way to get the bot in multiple servers.

**!twitch** -> pulls info on a twitch streamer

**!stock** -> check a ticker value

Channel management!

do !help to get all the availble commands. Submissions for new generic commands are welcome. A lot of code is submitted and merged from users if it seems interesting enough but is not actively maintained by the main contributors so please report if you see any suspected bugs ;)

!alias can be very powerful to create shotcuts for other commands or create copypastas. eg **!alias tsla stock $TSLA** will create a **!tsla** alias to run **"stock $TSLA"**

*Setting up*

Before the first run you will need to create an auth.json file. A bot token is required. The other credentials are not required for the bot to run, but they are highly recommended as commands that depend on them will not function. See auth.json.example.
------------------------------------------------------------------------------------------------------------------------------------
*Running longterm*

Once you've setup your keys and checked that the features you want are working, you have a couple of options for running the bot.
--------------------------------------------------------------------------------------------------------------------------------------

*Running on Repl.it*
You will still need to create an auth.json file with your credentials with this process, follow the steps above.


