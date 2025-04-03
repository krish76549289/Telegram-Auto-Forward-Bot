

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SudoR2spr/Telegram-Auto-Forward-Bot)

# Telegram Auto Forward Bot 🤖

A Telegram bot that automatically forwards content from one channel to another with watermark support and full customization options.

## 📌 Requirements

- Node.js 16.x or higher
- Git
- Telegram Bot Token
- Try Vercel/Render/Koyeb/Heroku/Zeet account (or any other hosting service)

## 🚀 Deployment Guide

### 1. Fork the Repository
- Click the `Fork` button at the top right of this repository

### 2. Configuration Setup
Create a `.env` file with these variables:

```env
BOT_TOKEN=your_bot_token_from_BotFather
SOURCE_CHANNEL_ID=your_source_channel_id
DESTINATION_CHANNEL_ID=your_destination_channel_id
ADMIN_ID=your_telegram_user_id
VERCEL_URL=your_App_name.vercel.app
```
### Note 
## Replace your webhookUrl `bot.js` file line No `515`

# 📌 Telegram Bot Webhook Setup Guide

## 🔗 One-Click Webhook Setup 

## 🌐 For Vercel/Heroku Users
1. **Vercel**:

```
curl -X POST "https://api.telegram.org/botYOUR_BOT_TOKEN/setWebhook?url=https://YOUR_VERCEL_APP.vercel.app/webhook"
```

## ✅ Verification Command
Check if webhook is set:
```
curl "https://api.telegram.org/botYOUR_BOT_TOKEN/getWebhookInfo"
```

## 🔄 Switch Back to Polling
```
curl -X POST "https://api.telegram.org/botYOUR_BOT_TOKEN/deleteWebhook"
```

2. **Heroku**:
   ```
   curl -X POST "https://api.telegram.org/botYOUR_BOT_TOKEN/setWebhook?url=https://YOUR_APP_NAME.herokuapp.com/webhook"
   ```

## ⚠️ Important Notes
- Must use **HTTPS** (not HTTP)
- URL must end with `/webhook` or your endpoint path
- For security, always use a `secret_token`
- Timeout: Webhook requests timeout after **60 seconds**

## ✨ Key Features

### 🔄 Auto-Forwarding Capabilities
```plaintext
- Automatic content forwarding between channels
- Supports multiple file types (videos, photos, documents, audio)
- Configurable forwarding rules and filters
```

### 🛠️ Customization Options
```plaintext
- Custom watermark text support
- Toggle auto-forwarding on/off
- Silent mode (disable notifications)
- File type filtering (forward only specific media types)
```

### ⚡ Admin Controls
```plaintext
- Manual post forwarding commands
- Bulk forward old posts (/forwardold)
- Real-time configuration changes
- Admin-only command protection
```

### 🌟 Advanced Functionality
```plaintext
- Persistent settings with cache
- Error handling and logging
- Webhook and polling support
- Multi-platform deployment
```

### 📊 Monitoring
```plaintext
- Last forwarded post tracking
- Bot status commands
- Activity logging
```

### 🚀 Deployment Options
```plaintext
- One-click Heroku deployment
- Vercel/Railway/Zeet support
- Local development ready
- Environment variable configuration
```

### 🔒 Security
```plaintext
- Admin ID verification
- Markdown injection protection
- Error rate limiting
```

### 💡 Bonus Features
```plaintext
- Interactive buttons for quick actions
- Help command with visual guide
- Multi-language support ready
```


## 📜 Command List

```plaintext
/start - Show bot status
/help - Show help guide
/forward - Manually forward last post
/forwardold [count] - Forward old posts
/autoforward [on/off] - Toggle auto-forwarding
/silent [on/off] - Toggle silent mode
/settypes [types] - Set file types to forward
/setwatermark [text] - Set watermark text
/togglewatermark - Toggle watermark on/off
```

## 🤝 Support

For help contact:  
[@Support_Username](https://t.me/WD_Request_Bot)  
Or visit our channel:  
[@Channel_Username](https://t.me/Opleech_WD)

![Feature Demo](https://graph.org/file/4e8a1172e8ba4b7a0bdfa.jpg)
```
