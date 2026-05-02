# ⚡ FastKeno — Telegram Mini App

Dark cosmic Keno game inspired by Atlas V, built for Telegram Mini Apps.

## 🎮 Features
- 80-ball Keno grid (pick 1–10 numbers)
- Animated draw sequence with glow effects
- Dynamic paytable (updates per pick count)
- Bet chips: $0.20 → $50
- Speed modes: Slow / Fast / Turbo
- Auto-play mode
- Win overlay with collect animation
- Mobile-optimised for Telegram WebApp

## 🚀 Deploy to Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → Web Service
3. Connect your GitHub repo
4. Render auto-detects `render.yaml` — hit **Deploy**
5. Your game URL: `https://fastkeno.onrender.com`

## 📱 Telegram Bot Setup

In `@BotFather`:
```
/newbot → name it → get token
/mybots → your bot → Bot Settings → Menu Button → set URL to your Render URL
```

Or use inline keyboard with Web App button:
```python
InlineKeyboardButton("🎰 Play FastKeno", web_app=WebAppInfo(url="https://fastkeno.onrender.com"))
```

## 🏗 Local Dev
```bash
npm install
npm start
# open http://localhost:3000
```
