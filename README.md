# WhatsApp → Google Sheets Bot

This project connects WhatsApp Business Cloud API with Google Sheets.

## 🚀 Setup

1. Clone this repo
   ```bash
   git clone https://github.com/YOUR_USERNAME/whatsapp-google-sheet-bot.git
   cd whatsapp-google-sheet-bot
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Add your `credentials.json` (Google Service Account file).

4. Replace `YOUR_SHEET_ID` in `index.js` with your Google Sheet ID.

5. Deploy to Heroku
   ```bash
   git init
   heroku create your-app-name
   git add .
   git commit -m "first commit"
   git push heroku main
   ```

6. Set webhook in Meta Developer Console
   ```
   https://your-app.herokuapp.com/webhook
   ```

7. Done ✅

Now any WhatsApp message like:
```
02-09-2025, UP14GT4898, 1500, 200
```
will automatically append a new row in your Google Sheet.
