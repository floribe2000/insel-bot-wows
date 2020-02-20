# insel-bot-wows
A discord bot meant for World of Warships clans


Once you invited the bot to your server, you have to set a bot channel first.
To do this, just use the command `!config -bot #channel` (replace #channel with a channel of your choice, keep in mind it has to be a valid channel mention and the bot has to be able to read and write in this channel!)

Command documentation for the bot

info  
!info : Shows a list of all available bot commands
Available aliases: !help

notify  
!notify [date] : Notifies all users which have not reacted to the sign-up messages for the specified date yet. The roles that should be checked can be edited with the config command. Date format: dd.MM.

create  
!create [date] : Creates the cw sign-up messages for the given date. Date must be specified in format dd.MM.

ignore  
!ignore [add|remove|list|info] : Options for the ignore list. For more details see !ignore help

messages  
!messages [date] : Returns the message IDs of all sign-up messages for the specified date.

delete  
!delete [date] : Deletes all sign-up messages for the given date

reminder  
!reminder {-n|-notify} : Creates a reminder or executes the notify task for a reminder.

config  
!config [param] {new value} : Shows the current config setting or sets a new value.
Possible params: 
command, bot, messages, botpublic, admin, lang, reactions, save

emote  
!emote [add|modify|remove] [name:user:emotes] : Adds, modifies or removes an emote. For more details see !emote help.

reactions  
!reactions [date] : returns a list of all users who reacted to the messages for the specified date and also returns a list of everyone who didn't react at all.

stats  
!stats {region} [name] [season] : Shows clan battle stats for the given player for the specified season. Doesn't work with hidden stats.
