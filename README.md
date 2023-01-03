# Telegram-To-Discord
Mirrors all messages from Telegram and translates them if they are not English and sends them to the webhook with all the media. Only works for photos and videos not longer than 60 seconds (imgur limit) in which case it displays a link to the message in Telegram.
translation part have been commented out in the main just remove the comments to enable.
# Requirements

- Python 3.11 or later
- Python pip -> requirements.txt
- Discord bot token
- Telegram API tokens
- (rest of the requrements are in the txt file.)
# How to run
```py
#Download the repo and extract to an empty folder
#Open a CLI ex. CMD,PS,GitBash in the directory
pip3 install -r requirements.txt
#Rename example.env to .env
#Edit info in .env
#APPID and HASH are created here https://core.telegram.org/api/obtaining_api_id
python3 main.py
```
