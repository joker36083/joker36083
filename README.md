
#!/usr/bin/python

# This is a simple echo bot using the decorator mechanism.
# It echoes any incoming text messages.

import telebot

API_TOKEN = 1784405428:AAEdQ8kjhrsX4-7dezxalfp04iqC5UAixzc

bot = telebot.TeleBot(API_TOKEN)


# Handle '/start' and '/help'
@bot.message_handler(commands=['help', 'start'])
def send_welcome(message):
    bot.reply_to(message, """\
Ciao io sono un bot
I am here to echo your kind words back to you. Just say anything nice and I'll say the exact same thing to you!\
""")


# Handle all other messages with content_type 'text' (content_types defaults to ['text'])
@bot.message_handler(func=lambda message: True)
def echo_message(message):if message.text==''ciao:
    bot.reply_to(message ciao io sono un bot
  bot.reply_to(message benvenuto su gruppo di unknownxarmy23
     ot.polling()
