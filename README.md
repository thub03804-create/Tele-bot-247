# Telegram Bot 24/7 Starter

Bot mẫu dùng `python-telegram-bot` (long polling). Triển khai 24/7 trên Railway/Render.

## Chạy local
1. Cài Python 3.11+
2. `pip install -r requirements.txt`
3. Đặt biến môi trường `BOT_TOKEN` (token từ BotFather)
4. `python bot.py`

## Triển khai Railway
- Tạo repo GitHub, push toàn bộ file.
- Railway -> New Project -> Deploy from GitHub.
- Add Variables: `BOT_TOKEN=<token>`
- Deploy -> kiểm tra logs thấy "Bot is running..."
