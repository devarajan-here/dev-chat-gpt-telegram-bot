# dev-chat-gpt-telegram-bot
Introducing the Telegram Chatbot for GitHub, the ultimate tool for seamless collaboration on your open-source projects. Our bot allows you to easily manage pull requests, issues, and commits right from Telegram. Don't miss out on this convenient and time-saving feature!


How Will This Work
This is very simple, we are using OpenChat gpt api to post request and get answer. So as you send your message to bot , the bot will send request to chatgpt. And it also post answer from them. How soon you will get the answer depends on your plans. If you are a free user then it may take some time. But if you are a premium user then you will get the answer very soon. 
The bot will send you all the messages at once so it might take a while. 
Starting 
Today we will make our own Chat GPT bot. 
You will need some important things 
1. Hosting For bot 
2. Telegram Bot Api 
3. Open Chat Gpt Api 

1. Hosting :-  To Run your bot you need a hosting service you can use any free service like render , railway, koyeb , replit etc. 
you can also host this bot on your computer and phone. To host this bot in computer you will need terminal and to host in mobile you will need termax app. 

2. Telegram Bot Api :- To get your bot api 
1. Open the Telegram app on your device.
2. Search for the BotFather user. Or open https://telegram.me/BotFather
3. Type /newbot in the chat window and hit enter.
4. Enter a name for your bot.
5. Enter a username for your bot.
6. Copy the access token provided by the BotFather.
7. Use the access token to access the HTTP API.

3. Open Chat GPT Api :- open https://platform.openai.com/account/api-keys
Login your account , then click on create api id. 
Save it anywhere. 

Let's begin the Hosting process
I am going to host this bot on replit.com , you can host it anywhere 

Open replit.com and create account and then click on pluse + Icons. Click on import from GitHub. Now paste this git url 
https://github.com/devarajan-here/dev-chat-gpt-telegram-bot

Choose language node.js 
Click on import wait some seconds, 
write run command node index.js
Click on commands >>secrets>>edit api id and tg api , out your values and save 
Now click on console and click on round play button. 
Wait some seconds then start your telegram bot whose api id was given. 

How To Use 
Your telegram chat gpt bit is ready 
Send command /ask "your question" 

Replit stops working after every 5 minutes as long as you keep its pages open. 

You can host this bot on railway.app or Where you have the facility to keep the boat running at all times. 

To install in Mobile or computer , fork this repo then edit .env values then , you need to install node first then git. 
Clone this repo from:-  git clone https://github.com/devarajan-here/dev-chat-gpt-telegram-bot

Then :-  node index.js



How to Install:

npm i

nano .env (ADD TELEGRAM API AND OPENAI API)

node index.js
