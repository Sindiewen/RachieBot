# RachieBot - The Universal Bot!
I'm building a shitposting Bot that can be used in many places!
Currently
Telegram - WIP but works
Discord - in prods

Too play with RachieBot, search her in telegram. The name is RachieBot.

Commands she can do, Commands with arguments afterwards:
- /caps ANYTHING YOU TYPE HERE WILL BE IN ALL CAPS
- /WeIrD AnYtHiNg YoU TyPe HeRe WiLl Be SpElT In WeIrD CaSe WhErE EaCh ChArAcTeR AlTeRnAtEs CaSe. LiKe ThE SpOnGeBoB MeMe
- /owoify Huohhhh. anythng uu type hewe wiww become vewy owoifyed ;3
- /echo Anything you type here, i'll repeat!

Commands without arguments:
- /start - recites the starting text when you first launched her
- /rp - Prints the infamous furry owo whats this copypasta
- /tragedy - prints the amazing farth plageus the wise copypasta
- /navyseal - prints the legendary navyseal copypasta

have fun!

Created by @Sindiewen


Now this is for my own telegram bot @rachiebot, but any of the code could be used for your own bot as long as you bring your own bot.
Here's the steps:
- Make sure pip is installed (for something like Ubuntu, apt install python3-pip, idk about other os's)
- For Telegram: Get the Python Telegram bot library here ---> https://github.com/python-telegram-bot/python-telegram-bot (if python 3, use pip3 instal ...)
  - python3 -m pip install -U python-telegram-bot
- Create the file "createTelegramBot.py", import telegram, and create a function 'def createTelegramBot()' that returns the bot with it's token 'return telegram.bot(token='token for your bot goes here')

- For Discord: wip...
  - Install the python library: python3 -m pip install -U discord.py

- run program as following, Manual Method
  - Run as is within terminal, and seeing stuff in the terminal (idk what it's called)
    -  'python3 rachiebot.py'
  - Run in the background: 
    - 'nohup python3 rachibot.py &' (this prevents some weird issues with it trying to create multiple instandces of the bot?) thks https://askubuntu.com/questions/396654/how-to-run-a-python-program-in-the-background-even-after-closing-the-terminal <3
    - Since it's in the background, you'll need to get it's process id and kill is
    - run 'ps -ax | grep rachiebot.py' then kill it's process id
- OR run with rachiebot.sh
- ./rachiebot.sh <arg>
    - Arguments include:
        - start : starts the bot
        - startBG : starts bot, runs in background
        - getPID : gets the pid of the program so you can kill it
- to kill the bot, kill the pid
- shitpost
