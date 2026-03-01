<p align="center">
  <img src="img/banner.png" alt="PostOrbit Banner" width="800">
</p>

<p align="center">
  <b>Post to Telegram channels and groups directly from your terminal — fast, secure, and developer friendly.</b>
</p>

<h1 align="center">PostOrbit — Telegram Terminal Poster</h1>

<p align="center">
  <b>Terminal → Telegram Post in Seconds</b><br>
  Developed by <a href="https://www.amitdas.site/">Amit Das</a>
</p>

---

## Overview
PostOrbit is a lightweight Python CLI tool designed for developers, bot owners, and automation users who want to **post messages, images, GIFs, or documents to Telegram channels and groups directly from the terminal**.

It supports inline buttons, media uploads, HTML formatting, and admin preview confirmation for safe publishing.

No complex frameworks required — simple, fast, and reliable.

---

## ⚡ Core Features

- Post to Telegram channels and groups
- Send text, photo, GIF, or document
- Inline button support (JSON config)
- HTML caption formatting
- Admin preview before posting
- Confirmation prompt for safety
- Supports username, URL, or chat ID
- Lightweight and fast
- No database required

---

## 📦 Requirements

- Python 3.7+
- requests library

Install dependency:

```bash
pip install requests
````

---

## 🛠 Setup

### 1. Clone repository

```bash
git clone https://github.com/AmitDas4321/PostOrbit.git
cd PostOrbit
```

---

### 2. Edit config.py

```python
BOT_TOKEN = "YOUR_BOT_TOKEN"
ADMIN_ID = YOUR_TELEGRAM_CHAT_USER_ID
```

---

### 3. Edit message.txt

Example:

```txt
📢 <b>Official Announcement</b>

PostOrbit is now live.

Click the button below to view the repository.

Thank you 💙
```

---

### 4. Edit message.json

Example:

```json
{
  "photo_enable": true,

  "photo": "5348285704398963795.png",
  "parse_mode": "HTML",

  "effect_enable": true,
  "message_effect_id": "5107584321108051014",

  "has_spoiler": false,

  "buttons_enable": true,
  "button_count": 2,

  "buttons": [
    { "text": "View Repository 💻", "url": "https://github.com/AmitDas4321/PostOrbit" },
    { "text": "Join Channel 📢", "url": "https://t.me/BlueOrbitDevs" }
  ]
}
```

---

## ▶️ Usage

Run the script:

```bash
python main.py
```

Enter target:

```
@your_channel_username
```

Preview will be sent to admin.
Type:

```
Y
```

To confirm posting.

---

## 🎯 Supported Targets

You can use:

```
@channelusername
t.me/channelusername
https://t.me/channelusername
-100xxxxxxxxxx
```

---

## 🧩 Use Cases

### Channel Automation

Post updates instantly from terminal.

### Developer Workflows

Integrate posting into scripts or pipelines.

### Content Management

Quickly publish announcements or media.

### Bot Systems

Use as backend publishing utility.

---

## 🔒 Security

* No data storage
* No external tracking
* Uses official Telegram Bot API
* Runs locally on your machine

---

## ⚠️ Important

Bot must be admin in channel with permission:

* ✅ Post Messages

---

## 📬 Support

<p align="center">
  <a href="https://t.me/AmitDas4321">
    <img src="https://img.shields.io/badge/Contact%20on%20Telegram-@AmitDas4321-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
</p>

---

## 📜 License

MIT License © 2026 Amit Das

---

<p align="center">
  <b>Made with ❤️ by <a href="https://amitdas.site">Amit Das</a></b><br>
  ☕ Support development: <a href="https://paypal.me/AmitDas4321">PayPal.me/AmitDas4321</a>
</p>
