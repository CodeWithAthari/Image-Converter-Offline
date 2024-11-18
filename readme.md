# 🎮 AI Chat History Extension

A browser extension that saves your chat history with AI assistants like ChatGPT, Claude, and more! Never lose your important conversations again.

## ✨ Features

- 💾 Automatically saves your chat history locally
- 🔄 Works offline thanks to service workers
- 🔍 Easy search through past conversations
- 🎨 Clean and simple interface
- ⚡ Lightweight and fast
- 🔒 Privacy focused - all data stays on your device

## 🛠️ How It Works

### Core Functions

#### `saveChat()`
📝 Saves the current chat conversation to browser storage when you send/receive messages

#### `loadHistory()`
📚 Loads and displays your saved chat history when you open the extension

#### `searchChats()`
🔎 Filters through your saved chats based on keywords

#### `clearHistory()`
🗑️ Lets you delete your saved chat history if needed

### Service Worker & Caching

This extension uses service workers to:
- 🔄 Work offline
- ⚡ Load faster
- 💾 Cache important files

To customize the caching behavior:
1. Open `service-worker.js`
2. Modify the `CACHE_NAME` and `urlsToCache` array
3. Adjust cache duration in `maxAgeSeconds`

To disable service worker:
1. Delete or rename `service-worker.js`
2. Remove the service worker registration from `manifest.json`

## 🎨 Customization

You can easily customize:
- Theme colors in `styles.css`
- Cache settings in `service-worker.js`
- Supported chat platforms in `content.js`

## 📝 License

This project is free to use under the MIT License. You can:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Use privately

Just remember to give credit! 😊

## 🔗 Links

Created by [Dev Atrii](https://atrii.dev)
- 📺 [YouTube Channel](https://youtube.com/YourChannel)
- 🌟 Star this repo if you find it helpful!

## 💝 Support

If you like this tool, consider:
- Starring the repo
- Sharing with friends
- Subscribing to my YouTube channel
