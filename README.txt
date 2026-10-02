# 💍 Wedding Telegram Mini App

Demo: Aziz & Malika — 15.11.2026, 18:00.

## Papkalar
- `index.html` — taklifnoma Web App
- `images/` — demo rasmlar
- `music/` — MP3 shu yerga
- `bot/bot.py` — Telegram bot

## 1. Web App
`index.html`, `images/` va `music/` papkalarini HTTPS hostingga joylang.

Masalan:
https://sizning-domeningiz.uz/

## 2. Bot
Python 3 o'rnating:
```bash
pip install pyTelegramBotAPI
```

Bot tokenini `BOT_TOKEN` environment variable orqali bering va `WEBAPP_URL` ni o'zgartiring.

Windows:
```cmd
set BOT_TOKEN=123456:ABC...
set WEBAPP_URL=https://sizning-domeningiz.uz/
python bot/bot.py
```

Linux:
```bash
export BOT_TOKEN="123456:ABC..."
export WEBAPP_URL="https://sizning-domeningiz.uz/"
python bot/bot.py
```

## 3. Muhim
Telegram Web App uchun HTTPS URL ishlating.
BotFather orqali bot yarating va botni ishga tushiring.

## 4. O'zgartiriladigan joylar
`index.html` ichida:
- Aziz
- Malika
- 15.11.2026
- 18:00
- “Navro'z” to'yxonasi
- Toshkent
- Google Maps havolasi

Rasmlarni `images/photo1.svg` va boshqalar o'rniga JPG/WEBP bilan almashtirish mumkin.
Musiqani `music/wedding.mp3` nomida joylashtiring.
