[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/HexacoinBot/wallet?startapp=398750825)

## Recommendation before use

# 🔥🔥 PYTHON version must be 3.10 🔥🔥

> 🇷 🇺 README in russian available [here](README-RU.md)

## Features  
|                          Feature                          | Supported |
|:---------------------------------------------------------:|:---------:|
|                      Multithreading                       |     ✅     |
|                 Proxy binding to session                  |     ✅     |
|                       Auto tap cube                       |     ✅     |
|                      Auto play games                      |     ✅     |
|                  Auto missions complete                   |     ✅     |
|                       Auto referral                       |     ✅     |
| Support for tdata / pyrogram .session / telethon .session |     ✅     |


## Settings
|          Settings          |                                                   Description                                                   |
|:--------------------------:|:---------------------------------------------------------------------------------------------------------------:|
|   **API_ID / API_HASH**    |                    Platform data from which to run the Telegram session (default - android)                     |
|        **AUTO_TAP**        |                                  Auto tap cube at main window (default - True)                                  |
|      **AUTO_MISSION**      |                             Auto completes missions that available (default - True)                             |
|      **AUTO_LVL_UP**       |                                 Auto upgrade your level in bot (default - True)                                 |
|     **PLAY_WALK_GAME**     |                      Auto get reward for playing Hexacore Gaming Universe (default - True)                      |
|    **PLAY_SHOOT_GAME**     |                             Auto get reward for playing Pin Bullet (default - True)                             |
|     **PLAY_RPG_GAME**      |                                Auto get reward for playing Pals (default - True)                                |
|  **PLAY_DIRTY_JOB_GAME**   |                             Auto get reward for playing Dirty Job (default - True)                              |
| **PLAY_HURTMEPLEASE_GAME** |                        Auto get reward for playing Hurt me please game (default - True)                         |
|     **AUTO_BUY_PASS**      |                        Auto buys beneficial tap pass for better earning (default - True)                        |
|         **REF_ID**         | Will allow you to automatically referral your alts to main (default - None, please write here your telegram id) |
|  **USE_PROXY_FROM_FILE**   |                  Whether to use a proxy from the `bot/config/proxies.txt` file (True / False)                   |

## Quick Start 📚

To fast install libraries and run bot - open run.bat on Windows or run.sh on Linux

## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10**

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Installation
You can download the [**repository**](https://github.com/HiddenCodeDevs/HEXACOREbot) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/HiddenCodeDevs/HEXACOREbot.git
cd HEXACOREbot
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/HEXACOREbot >>> python3 main.py --action (1/2)
# Or
~/HEXACOREbot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/HEXACOREbot >>> python main.py --action (1/2)
# Or
~/HEXACOREbot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```
