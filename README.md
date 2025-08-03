# 🗣️ Arabic Text-to-Speech Telegram Bot

A Telegram bot that converts user-input Arabic text into speech using Coqui TTS. The bot allows users to adjust the playback speed and automatically saves user data to `users.json` and `users.xlsx`.

# 🤝 Authors
**Sohaib Essam** — [GitHub Profile](https://github.com/Sohaib010) 

### Project structure
arabic-tts-telegram-bot/

│

├── bot.py                # Main bot script

├── requirements.txt      # Dependencies

├── run.bat               # Windows run script

├── run.sh                # Linux/macOS run script

├── s1.wav                # Speaker voice sample

├── users.json            # User data (auto-generated)

└── users.xlsx            # Excel log of users (auto-generated)

---

## 🚀 Features

- 🎙️ Converts Arabic text to natural speech  
- 🎚️ Allows selection of speech speed (-50%, -30%)  
- 💾 Saves information about new users  
- ⚡ Supports both **GPU (CUDA)** and **CPU** — works even without a graphics card  
- 🔊 Uses a custom speaker voice sample (`s1.wav`)  

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/arabic-tts-telegram-bot.git
cd arabic-tts-telegram-bot

```

### 2. Install dependencies

```bash
pip install -r requirements.txt

```

### 3. Add your Telegram bot token

with your actual token from BotFather.

```bash
bot_token = "YOUR_TOKEN_HERE"
```
### 4. Add the speaker sample 

s1.wav file
a sample Arabic voice recording


### On Windows:
```bash
run.bat
```
### On Linux/macOS:
```bash
./run.sh
```
### ⚠️ Don't forget to make the file executable:
```bash
chmod +x run.sh
```
### Or manually:
```bash
python bot.py
```



### 💡 Ideas for improvement

✅ Support for additional languages

✅ Ability to choose male/female voice

✅ Web interface for text input and audio download



