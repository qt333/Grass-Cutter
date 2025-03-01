# 🌅 GRASS
Software for https://app.getgrass.io/ 

<div align="center">
  <img src="https://i.ibb.co/GfCgJb6y/GRASS-CUTTER.jpg" alt="GRASS-CUTTER">
  <p align="center">
    <a href="https://t.me/qtttttttttttttt">
      <img src="https://img.shields.io/badge/Telegram-Chat-blue?style=for-the-badge&logo=telegram" alt="Telegram Chat">
    </a>
  </p>
</div>

## 📋 Table of Contents
- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Configuration](#%EF%B8%8F-configuration)
- [Usage](#-usage)
- [Troubleshooting](#-troubleshooting)

## 🚀 Features

- ✨ **Points Farm**
- 🤖 **Working even if problem with grass-login servers**
- 🔄 **Unique proxy system and auto recconect after error**
- 📉 **Low trafic usage (0.11mb per connection/day)**
- 🧩 **Pass CloudFlare protection**
- 📊 **Multiple connection launch by 1 line in config**
- ✅ **100% copying extestion work. 0% sybil**
- 🌾 **Available node types: x1 | x1.25**
- 🧩 **Fast launch by one click**
- 📋 **Telegran notification for software status (Active connection | Failed | Pings count)**
- 🔒 **Show current Active connection amount**
- ✨ **No restriction for session|connections**

📋 **Supported Operating System: Windows ✅ | Linux ✅**

## Pricing
💰 $55

🔒 Working by license key (1 PC - 1 Software)

## 💻 Requirements

- Users ids (!)
- Stable internet connection
- Working proxies (HTTP(S)/SOCKS5)

## 🛠️ Installation

1. **Unpack archive**
2. **Setup all nessesary (users.txt/proxies.txt/.env file)**

## ⚙️ Configuration

### 📁 .env

```.env
#TG notification block abount software status (active connectiong count, pings count, failed proxy count) 
TG_BOT_TOKEN = ''
CHAT_ID = ''
TG_NOTIFICATION_FREQUENCY = 1 # how frequent you will receive notify from tg bot. If value is 1 - every 2minutes, 2 - every 4 minutes, 5 - every 10 minutes (default)
TG_TITLE = '[Grass 🌿]' #Title that will shown in the beginning of tg msg

WINDOW_NAME = 'Grass'

NODE_TYPE = 'x1.25' # or 'x1'

DELAY_RANGE = [1, 10] #randomized delay start in seconds for each connection (form 1 to 30 seconds) specify your desire time delay
PROXIES_PER_ACCOUNT = 0 #connection per account. If 1 mean 1 connection for each accounts
PROXIES_PER_ACCOUNT_RANGE = [10, 12] #randomized connection amount (random choose form 1 to 3 connection per account), PROXIES_PER_ACCOUNT should be set to 0, to this feature work. 

LESS_LOG_OUTPUT = False #Set to True if want to see less logs output in the console (only errors will show), usefull when run a lot of connections (500+)
SHOW_ERRORS_LOG = True #Set to False if won't to see any errors in the console | Default True

PROXIES_FILE_PATH = 'proxies.txt'
USER_IDS_FILE_PATH = 'users.txt'
```

### 📁 Input Files Structure

#### users.txt
```
userId0
userId1
```

#### proxies.txt
```
scheme://login:password@host:port
```

## 🚀 Usage

1. Configure all necessary files as described above
2. Start the grass.exe or grass

## 🔧 Troubleshooting

### Common Issues and Solutions

#### 🌐 Advice
- Use good residential proxies

## 📞 Contact

For any question for buying software:
- 💬 [Contact](https://t.me/qtttttttttttttt)
