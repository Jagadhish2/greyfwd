# Forward_Bot

* Bot to forward messages from one channel to other without admin permission in source channel.
* Can be used for both private and Public channels.
* Bot Index message from channel and saves to database, further forwards and deletes each messages from database.Use of database was to Remove duplicacy of files.
* For Private channels User account is used to copy messages, hence will be slow, to avoid ban.

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/greymatter658/my-forward-bot)



### Variables

* `API_HASH` API Hash from my.telegram.org
* `API_ID` API ID from my.telegram.org
* `BOT_TOKEN` Bot token from @BotFather
* `BOT_USERNAME` Your bot username without @
* `OWNER_ID` Telegram Id of Owner.
* `TO_CHANNEL` Channel ID of channel to which messages are forwarded eg:- -100xxxxxxxx
* `SESSION` Pyrogram session string Generate From here [![GenerateStringName]
* `DATABASE_URI` Database uri from [MongoDB](https://cloud.mongodb.com/)
* `DATABASE_NAME` Database Cluster name
* `COLLECTION_NAME` Database Collection name.
