### Deploy On Render
<details><summary>Deploy To Render</summary>
<br>
<b>
Use these commands:
<br>
<br>
• Runtime: Python 3
<br>
<br>
• Build Command: <code>pip3 install -U -r requirements.txt</code>
<br>
<br>
• Start Command: <code>gunicorn app:app & python3 bot.py</code>
<br>
<br>
Go to https://uptimerobot.com/ and add a monitor to keep your bot alive.
<br>
<br>
Use these settings when adding a monitor:</b>
<br>
<br>
<img src="https://telegra.ph/file/a79a156e44f43c9833b50.jpg" alt="render template">
<br>
<br>
<b>Click on the below button to deploy directly to render ↓</b>
<br>
<br>
<a href="https://render.com/deploy?repo=hhttps://github.com/ViSHWA14510/VM-FILE-STORE">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
</details>

### Deploy On Heroku 
<details><summary>Deploy To Heroku</summary>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/VJBots/VJ-Auto-Forward-Bot">
<img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku">
</a>
</details> ♥️

- `API_ID` - Get this from [TelegramORG](https://telegram.org)
- `API_HASH` - Get this from [TelegramORG](https://telegram.org)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. *(Without [@])*
- `DB_CHANNEL` - A Telegram Channel ID.
	- Make a Channel for Storing Files. We will use that as Database. Channel must be Private! Else you will be Copyright by [Telegram DMCA](https://t.me/dmcatelegram)!
- `BOT_OWNER` - Bot Owner UserID
	- Put your Telegram UserID for doing Broadcast.
- `DATABASE_URL` - MongoDB Database URI
	- This for Saving UserIDs. When you will Broadcast, bot will forward the Broadcast to DB Users.
- `UPDATES_CHANNEL` - Force Sub Channel ID *(Optional)*
	- ID of a Channel which you want to do Force Sub to use the bot. 
- `LOG_CHANNEL` - Logs Channel ID
	- This for some getting user info. If any new User added to DB, Bot will send Log to that Logs Channel. You can use same DB Channel ID.
 
