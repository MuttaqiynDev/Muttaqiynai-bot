# MuttaqiynAI Bot 🤖

_Empowering users with advanced AI conversational capabilities._

![Last Commit](https://img.shields.io/github/last-commit/MuttaqiyinDev/muttaqiynai-bot?label=last%20commit)
![Language](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Aiogram](https://img.shields.io/badge/Aiogram-3.17.0-blue)
![GeminiAI](https://img.shields.io/badge/Google%20GeminiAI-0.4.1-informational)

---

## 📖 Overview

**MuttaqiynAI Bot** is a Telegram bot that leverages Google Gemini AI to provide intelligent conversational experiences. Built with Aiogram 3.17.0, it also manages user data using SQLite for enhanced user management and broadcast features.

### ✨ Key Features

- 🔥 **AI Conversations:** Seamlessly integrates with Google Gemini AI for advanced text generation.
- 🗂️ **User Management:** Uses SQLite to store user IDs and manage broadcasts.
- 🔐 **Admin Commands:** Secure admin-only commands for viewing users and broadcasting messages.
- ⚡️ **Dynamic Commands:** `/start`, `/id`, `/users`, `/sendall` and natural language conversation.
- 📦 **Easy Deployment:** Fast and reliable with minimal dependencies.

---

## 🚀 Getting Started

### 🛠️ Prerequisites

- Python 3.8+
- Pip package manager
- Telegram bot token
- Google Gemini API key

---

### 🔧 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/MuttaqiyinDev/muttaqiynai-bot.git
   cd muttaqiynai-bot
   ````

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the Bot**

   * In `main.py`, set your:

     * `TELEGRAM_BOT_TOKEN`
     * `GEMINI_API_KEY`
     * `ADMIN_ID`

---

## 💻 Usage

Run the bot using:

```bash
python main.py
```

The bot will start polling and is ready to receive messages!

---

## 🧪 Testing

Currently, the project does not have an automated test suite. Testing is done manually by running the bot and interacting with it via Telegram.

---

## 📂 Project Structure

```
.
├── main.py               # Main bot file with handlers and logic
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## 📞 Contact

* **Telegram:** [@MuttaqiynDev](https://t.me/MuttaqiynDev)
* **Channel:** [@Muttaqiyn\_Media](https://t.me/Muttaqiyn_Media)

---


## ✨ Acknowledgements

Thanks to the developers of:

* [Aiogram](https://docs.aiogram.dev/en/latest/)
* [Google Gemini AI](https://ai.google.dev/)
