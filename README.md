# ⚡ PRIME KHALED BOT ⚡

Prime Khaled Bot is a powerful Multi-Device WhatsApp Bot built with Node.js and Baileys, designed for automation, moderation, entertainment, AI assistance, and advanced group management. It provides a fast, secure, reliable, and customizable experience for WhatsApp users and communities.

## ✨ Features

- 🤖 AI Chat Assistant
- 🧠 Smart Replies & Conversations
- 🛡️ Anti-Link Protection
- 🚫 Anti-Spam System
- 🔒 Auto Moderation
- 👋 Welcome & Goodbye Messages
- 🎨 Custom Welcome Cards
- 👑 Admin Commands
- 📢 Group Management Tools
- 🎮 Dice, Trivia & Fun Games
- 🖼️ Sticker Maker
- 📥 Media Downloader
- 📊 XP & Rank System
- 👤 User Profiles
- 🔍 Search Tools
- 🌐 Translation Commands
- 🧮 Calculator
- 📱 Multi-Device Support
- ⚙️ Customizable Settings

## 📦 Termux Installation

### Update Packages

```bash
pkg update && pkg upgrade -y
```

### Install Requirements

```bash
pkg install nodejs git ffmpeg imagemagick -y
```

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/prime-khaled-bot.git
```

### Open Project Folder

```bash
cd prime-khaled-bot
```

### Install Dependencies

```bash
npm install
```

### Start The Bot

```bash
node index.js
```

## 🔐 Pairing Code Setup

1. Run the bot using:

```bash
node index.js
```

2. Enter your WhatsApp number in international format.

Example:

```text
2348012345678
```

3. A pairing code will be generated.

Example:

```text
ABCD-1234
```

4. Open WhatsApp.

5. Navigate to:

```text
Settings → Linked Devices → Link a Device
```

6. Select:

```text
Link with Phone Number Instead
```

7. Enter the generated pairing code.

8. Wait for successful connection.

## 💾 Session Information

After linking, authentication files are automatically generated and stored locally.

Example:

```text
session/
├── creds.json
├── keys/
```

These files allow the bot to reconnect without generating a new pairing code.

**Important:** Keep your session files private. Anyone with access to them may be able to connect as your bot.

## ⚙️ Environment Variables

Create a `.env` file and configure:

```env
OWNER_NUMBER=YOUR_NUMBER
BOT_NAME=Prime Khaled Bot
PREFIX=.
```

## ☁️ Deployment

Prime Khaled Bot can be deployed on:

- Replit
- Railway
- Render
- VPS Servers
- Termux
- Bot Hosting Panels
- Self-Hosted Servers

## 🚀 Running With PM2

Install PM2:

```bash
npm install -g pm2
```

Start Bot:

```bash
pm2 start index.js --name PrimeKhaledBot
```

Save Process:

```bash
pm2 save
```

## 📜 Disclaimer

This project is intended for educational purposes and legitimate WhatsApp automation. Users are responsible for complying with WhatsApp Terms of Service and all applicable laws. The developer is not responsible for misuse, abuse, spam, or unauthorized activities performed using this software.

## 👨‍💻 Developer

**𓉳 PRIME KHALED DEV 🐐**

- Advanced WhatsApp Bot Developer
- Automation Enthusiast
- Open Source Contributor

## ⭐ Support

If you enjoy this project:

- ⭐ Star the Repository
- 🍴 Fork the Project
- 📢 Share with Friends

---

### ⚡ PRIME KHALED BOT — Fast • Secure • Powerful • Reliable ⚡
