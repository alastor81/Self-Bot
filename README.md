# Introductions

Self Bot based on https://valtman.name/telegram-bot
	
Developer:
[Amir Bagheri](https://github.com/Codelua)
 

# Installation
After installing the dependencies, let's install the bot:
```bash
 git clone https://github.com/CerNerCompany/Self-Bot
 cd Self-Bot
 chmod +x CPM
 ./CPM c --Configing Bot
 ./CPM lc --Login Self
 ./CPM l --Launching Bot
```
## for luanch as auto run 
 (use after config and login)

```bash 
 chmod +x AutoRunning.sh
 screen ./AutoRunning.sh
```
 
# How to Use :

 #####after `./CPM c` and `./CPM lc` : 

+ first insert your Telegram id (not username) in ``./bot/utils.mika`` [line 3 - 4] instead of my id (497391069) 

+ you can customise another configs like "myname"  , "answers" or ...

+ then you can simply use `./CPM l` or Use `screen ./AutoRunning.sh ` 

## Commands :

+ You find CMD(s) by seasrching `CMD :` in `./bot/bot.mika`

### List of currant CMD(s) :

+ `/self [on/off]` : turn Self bot on or off in a specific chat or group

+ `/markread [on/off]` : turn markread messages on or off (seen every message in a specific chat by robot) (you'll never have any unread mesage in that chat !)

+ `/answer [on/off]` : turn clerk on or off (clerk will answer other when they call your name or PM you but don't read any message if `markread` is off)

+ `/save` : reply on a message to save it on your telegram cloud

+ `/save [CMD]` : save a media with CMD (use /get [CMD] to get it) 

+ `/get [$file]` : send $file 

+ `/files` : list of all saved media

+ `/del file [$file]` : delete $file

+ `/clean files` : clean all saved media

+ `/typing [on/off]` : turn  typing mode on or off (when it's on , if some one message you , your status switches to typing for a while)

+ `/flood [lock/unlock]` : enable or disable flood protection (if someone flood your PV bot will block him)

+ `/malevolent [on/off]` enable or disable malevolent mode ( insult your enemy in Groups when they send message :|)

+ `/echo [on/off]` : enable or disable Echo mode (forward any message again :|)
 
+ `/bc` reply to a message to *send* it to all your group(s) (send and forward are different !)
 
+ `/fwd` : reply to a message to *forward* it to all your group(s)

+ `/panel` : shows your settings , redis and source file size and your last offline and online time

+ `/mydell` : delete all of your message in group

+ `/scm` or `/setclerkmessage` : reply to a message to set it as your clerk message

+ `/set flood [$amount]` : set bot Sensitivity for flood to $amount

+ `/set floodtime [$seconds]` set bot interval for check flooding to $seconds

+ `/set gif [CMD]` : reply to a gif to save the CMD for that gif (use CMD , then bot replace it with gif)

+ `/del gif [CMD]` : delete a gif/CMD

+ `/gifs` : list of saved gif/CMD (s)

+ `/set sticker [CMD]` : reply to an Sticker to save the CMD for that sticker (use CMD , then bot replace it with sticker)

+ `/del sticker [CMD]` : delete a sticker/CMD

+ `/stickers` : list of saved sticker/CMD

+ `/boobs` : NOTHING to say :|

+ `/web [$address]` : send description of site ($address most contain http:// or https://)

+ `/calc [$sentence]` : calculate $sentence (ex : /calc sin(30)+40)
   
+ `/backup` : send a copy of bot files

+ `/delallfrom` or `/daf` : reply on someone message to delete all of his messages [ONLY super groups]

+ `/reload` : reload bot 

+ `/dump` reply on a message to dump message JSON 

+ `/inv [reply | username | id]` : invite user to group

+ `/call [reply | username | id]` : start a call to user

+ `/addtoall [id]` add user to all groups

+ `/kick [reply | username | id]` : kick user from group

+ `/id [reply | username | id]` : return id of user

+ `/mute [reply | username | id]` : mute user in group

+ `/unmute [reply | username | id]` : unmute user in group

+ `/mute links [reply | username | id]` : prevent user to send links (for disable : `/unmute`)

+ `/mute media [reply | username | id]` : prevent user to send media (for disable : `/unmute`)

+ `/res [reply | id]` : show information of user

+ `/set enemy [reply | username | id]` : set user as enemy

+ `/del enemy [reply | username | id]` : delete user from enemy list

+ `/enemys` : list of enemys

+ `/clean msgs` : delete messages as mutch as possible [super groups ONLY]

+ `/flood [$amount]` : reply on a message to forward it there $amount times

+ `/to sticker` : reply on image to convert it to sticker

+ `/block [reply | username | id]` : block user

+ `/unblock [reply | username | id]` : unblock user

+ `/addc` : reply to a contact-message to contacts list

+ `/del` : reply to message to delete

+ `/pin` : reply to message to pin message in group

+ `/unpin` : reply to unpin message in group

+ `/name [$name]` : change chat/group name to $name

+ `/unban [reply | username | id]` : unban user in group 

+ `/deletemyacc [$reason]` : delete your account with reason : $reason

+ `/fw [username]` : reply to message to forward it to $username

