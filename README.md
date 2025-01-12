- 👋 Hi, I’m @sava791
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
sava791/sava791 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from aiogram import Bot, Dispathacher, exeutuor, types
from aiogram.types.web_app_info import WebAppInfo
print('Hello Word')



bot = telebot.TeleBot('8191670024:AAFvd6UwthQxmIS5n5qRpJ_8HlSnPczZkPI')
dp = Dispatcher(bot)

@dp.message_handlers(commands=['start'])
async def start(message : typees.Message):
        markup =  types.ReplayKeyboardMarkup()
        markup.add(types.KeyboardButton('Открыть веб страницу', web_app=WebAppInfo(url='https://www.binance.com')))
        await message.answer(' Заходи и  баготей!', reply_markup=markup)





exutor.start_polling(dp)




