## Merge Premium Bot
[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/Tamilupdates/Merge-Premium-Bot)

```diff
- TODO's:
+ Add ability to edit metadata of exported video

- FEATURES:
+ (new) Option to add multiple audio tracks to telegram video
+ (new) Option to add multiple subtitles to telegram video
+ Upload Files to Drive (Send your rclone config to bot)
#  1. Send your rclone config to bot.
#  2. Then send videos to merge, after you tap "Merge Now", upload to drive option will available.
+ Merged video preserves all streams of the first video you send (i.e. all audiotracks/subtitles)

+ Merge Upto 20 videos in one 
+ Upload as document/video 
+ Custom thumbnail support
+ Users can login to bot using password
+ Owner can broadcast message to all users
+ Log Channel to store all merged videos

```

## Config File Variables :
1. `TELEGRAM_API` : User Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : User Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather XD
4. `OWNER`: Enter bot owner's ID
5. `OWNER_USERNAME`: User name of bot owner
6. `DATABASE_URL`: Enter your mongodb URI
7. `PASSWORD`: Enter password to login bot
8. `LOGCHANNEL`: Log channel will store all users merged videos ("-100" + "channel Id")
9. `USER_SESSION_STRING`: Premium account session string to upload upto 4GB (requires `LOGCHANNEL`)

## Commands (add via @botfather) :
```
start - Start The Bot
extract - Extract audios/subtitles from telegram media
showthumbnail - Shows your thumbnail
deletethumbnail - Delete your thumbnail
settings - User Settings to manage different modes
help - How to use Bot
about - About the bot
login - Access bot
ban - (admin only) Ban any user
unban - (admin only) Unban any user
log - (admin only) Get log file from server
broadcast - (admin only) Broadcast message to bot users
stats - (admin only) check bots stats
```

## License
```
Merge Premium-Bot, Telegram Video-Premium Merge-Bot
Copyright (c) 2021  Tamil Updates <https://github.com/tamilupdates>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
```
