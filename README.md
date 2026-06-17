# telegram-bot
Bot
from telegram import Update
from telegram.ext import Application, CommandHandler, ContextTypes

TOKEN = "8988730894:AAGo1Q5emEDxKRH6Tn95pgLCNkTlCxWoRTE"

async def startupdatee: Update, context: ContextTypes.DEFAULT_TYPE):
    await update.message.reply_text("🤖 Bot Online!")

app = Application.builder().token(TOKEN).build()
app.add_handler(CommandHandler("start", start))
app.run_polling()
python-telegram-bot
python-3.11.9
