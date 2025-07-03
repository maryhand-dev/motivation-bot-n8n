# 💬 Motivation Bot - n8n + Telegram

This is a simple automation workflow that sends a **daily motivational message** every day at 7:00 AM via a **Telegram bot**, using the open-source tool [n8n](https://n8n.io).

---

## 🔧 Tools Used

- ✅ **n8n** - No-code workflow automation
- ✅ **Telegram Bot API**
- ✅ **HTTP Request** to fetch motivational quotes
- ✅ **CRON Schedule** to send messages at a fixed time
- ✅ **JSON Parsing**

---

## 📸 Screenshots

> Add your screenshots inside the `screenshots/` folder  
> For example:
- n8n Workflow  
- Telegram message received

---

## 🚀 How It Works

1. The workflow triggers every day at 7:00 AM.
2. It fetches a quote from an external API (like ZenQuotes).
3. It extracts the quote text.
4. Sends the quote via Telegram Bot using `Chat ID`.

---

## 📂 Files Included

- `motivation-workflow.json` → the exported n8n workflow
- `README.md` → project documentation
- `screenshots/` → images of workflow and results (optional)

---

## 🧠 Author

Made with 💡 and ☕ by **Mora**  

