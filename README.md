
import telegram

bot = telegram.Bot(token='የአንተ telegram bot token')

def send_signal(signal):
    chat_id = 'የአንተ ራስ chat_id ወይም group id'
    bot.send_message(chat_id=chat_id, text=f'SIGNAL: {signal}')

signal = generate_signal()
send_signal(signal)
