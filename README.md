# 🤖 Telegram Bot – Daily Goal Tracker

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A Python Telegram bot to **set, track, and monitor daily goals directly through Telegram**, without external integrations.  
Ideal for productivity tracking, support metrics, sales counts, or any daily activity.

---

## ✨ Features

- ✅ Set a daily goal  
- ➕ Register daily progress (+1)  
- 📊 View daily status  
- 👀 Check configured goal  
- 💾 Local storage using JSON  
- 🚀 Lightweight and easy to customize  

---

## 🛠️ Tech Stack

- Python 3.10+  
- python-telegram-bot  
- Telegram Bot API  
- JSON storage  

---

## 📂 Project Structure

```
bot-telegram-daily-goal/
├── bot_diario.py
├── dados_diarios.json
├── README.md
└── .gitignore
```

---

## ⚙️ Requirements

- Python 3.10+  
- Telegram account  
- Bot created with **@BotFather**  

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/youruser/bot-telegram-daily-goal.git
cd bot-telegram-daily-goal
```

Install dependencies:

```bash
pip install python-telegram-bot
```

Edit `bot_diario.py` and set your bot token:

```python
TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
```

Run the bot:

```bash
python bot_diario.py
```

---

## 📲 Available Commands

| Command | Description |
|-------|------------|
| /menu | Show menu |
| /setdiaria 10 | Set daily goal |
| /registrar | Add +1 to today |
| /status | Show today progress |
| /verdiaria | Show current goal |

---

## 💾 Data Storage

Data is stored locally in:

```
dados_diarios.json
```

Example:

```json
{
  "meta": 20,
  "producao": {
    "2026-02-05": 1
  }
}
```

---

## 🧩 Roadmap

- Per-user goals  
- Weekly/monthly reports  
- Goal reached notifications  
- Database support (SQLite/MySQL)  
- Auto-start on Windows  
- 24/7 cloud hosting  

---

## 📄 License

MIT License — free to use, modify, and distribute.
