# Telegram Voice-Chat Bot [ Pytgcalls ]

Telegram Voice-Chat Bot To Play Music With Pytgcalls From Various Sources In Your Group.

<img src="https://telegra.ph/file/a026faf8830906cf9df82.png" width="530" height="400">


# Support

1. All linux based os.


## Requirements

- Telegram API_ID and API_HASH
- Python 3.7 or higher 
- Userbot Needs To Be Admin In The Chat
- Install **ffmpeg**

## Run

Follow this if you are not running on heroku

```sh
$ git clone https://github.com/thehamkercat/Telegram_VC_Bot
$ cd Telegram_VC_Bot
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
$ cp sample_config.py config.py
```
Edit **config.py** with your own values.

```sh
$ python3 main.py
```

## Heroku

#### Generate String session [IMPORTANT]

Download this file [generate_string_session.py](https://raw.githubusercontent.com/thehamkercat/Telegram_VC_Bot/master/generate_string_session.py)


```sh
$ pip3 install pyrogram TgCrypto
$ python3 generate_string_session.py
```
You will get a session string, copy it, Then use heroku commands to push to heroku, DON'T ASK HEROKU SUPPORT IN GROUP FFS. 




Send [commads](https://github.com/thehamkercat/Telegram_VC_Bot/blob/master/README.md#commands) to bot to 
play music.


## Commands
Command | Description
:--- | :---
ابدا | To Start The bot.
مساعده | To Show This Message.
البنج | To Ping All Datacenters Of Telegram.
تخطي | To Skip Any Playing Music.
تشغيل youtube/saavn/deezer [song_name] | To Play A Song.
/play | To Play A Song Directly From Telegram File.
فحص | To Check Queue Status.
انضم | To Join Voice Chat.
اسكت | To Leave Voice Chat.

## Note

1. If you want any help you can ask [here](https://t.me/PatheticProgrammers)

## Credits
1. @wjj_u [For TgCalls]
