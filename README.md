# Discord-Online-Bot

A minimal Discord bot that stays online but does nothing. Perfect for testing, experiments, or keeping a bot online 24/7.

## Features
- Logs in to Discord
- Stays online continuously
- No commands, messages, or events
- Lightweight and simple

## Requirements
- Node.js v16 or higher
- Discord.js v14
- A Discord bot token

## Setup and Usage (All-in-One Steps)

1. **Clone the repository**
```bash
git clone https://github.com/yatharth691/Discord-Online-Bot.git
cd Discord-Online-Bot
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
   - Copy the `.env.example` file to `.env`:
```bash
cp .env.example .env
```
   - Open `.env` and replace `your-bot-token` with your actual Discord bot token:
```
TOKEN=YOUR_DISCORD_BOT_TOKEN
```
   - Example `.env.example` file content:
```
# Copy this file to .env and replace with your bot token
TOKEN=your-bot-token
```

4. **Start the bot**
```bash
node index.js
```

5. **Deploy the bot**
   - You can deploy the bot on any hosting that supports Node.js, such as:
     - Render (Background Worker)
     - Railway
     - VPS (AWS, Google Cloud, Oracle Cloud)
     - Your own PC or Raspberry Pi
   > Note: Hosting services like Vercel or standard Glitch projects will not keep the bot online 24/7.

6. **Notes**
   - The bot does not respond to messages or commands.
   - Keep your Discord bot token **secret**.
   - This project is intended for educational purposes or as a placeholder bot.

7. **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
