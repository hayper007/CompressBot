# VideoCompress

### Special Features:
- Bot's Live Status on Channel
- Force Sub to Channel
- Database:
	- Can Broadcast messages
	- Can Ban-Unban Manually
	- Can see numbers users in DB



## Easy Deploy:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## Required Configs:
* `SESSION_NAME` - Any name of session. Better keep default.
* `TG_BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
* `LOG_CHANNEL` - Put Your Bot's Logs Channel's Username. 
* `BOT_USERNAME` - Your Bot's Username which you send to [@BotFather](https://t.me/BotFather) while creating Bot. ***(Without `@` Before Username!!)***
* `APP_ID` - Get this from my.telegram.org
* `API_HASH` - Get this from my.telegram.org
* `DATABASE_URL` - Your MongoDB Database URL.
* `AUTH_USERS` - Put your ID & other Sudo Users IDs. Separate with **Space**. Just for using [Admin Commands]).

## Optional Configs:
* `UPDATES_CHANNEL` - Put your Channel Username which you want to do Force Sub. But bot should be Admin in that channel. If got any error or not understand anything than ask in [Support Group](https://t.me/linux_repo).
* `COMMAND_EXEC` - `/exec` Command Handler.
* `COMMAND_STATUS` - `/status` Command Handler.
* `COMMAND_CANCEL` - `/cancel` Command Handler.
* `COMMAND_COMPRESS` - `/compress` Command Handler.
* `COMMAND_START` - `/start` Command Handler.
* `COMMAND_HELP` - `/help` Command Handler

### Public Commands:
```
start - Start Bot
compress - Compress Video
help - How to Use Bot
```

### Admin Commands:
```
cancel - Cancel Last Process
status - Total User Number in Database
broadcast - Reply to Message to Broadcast
ban_user - Ban A User with time & reason
unban_user - Unban a User
banned_users - Show Banned Users
exec - EXEC 🙄
```

