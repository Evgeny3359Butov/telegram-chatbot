# telegram-chatbot

This Bot is written in Python with the help from the pyTelegramBotAPI.

Our official Channel on Telegram:
[@danjol](https://telegram.me/danjol)

Let's start by installing everything you need.

# The first thing that you need is: Python
```
sudo apt-get install python3
```

This also may helps you:
```
sudo apt-get install idle-python3.4
```

# Installing Python Package Manager

*For Ubuntu 10.10 Maverick and newer*
```
sudo apt-get install python-pip python-dev build-essential 
```
```
sudo pip install --upgrade pip 
```
```
sudo pip install --upgrade virtualenv 
```

*For older ubuntu versions*
```
sudo apt-get install python-setuptools python-dev build-essential
```
```
sudo easy_install pip 
```
```
sudo pip install --upgrade virtualenv
```

# Installing The Bot

After that you need to install the pyTelegramBotAPI.
```
sudo pip install pyTelegramBotAPI
```
Finally clone the repo

```
git clone https://github.com/danjol/telegram-chatbot
```

# Starting The Bot

```
cd telegram-chatbot
```
```
python launch.py
```

# Screen

If you want to let the bot work even without SSH connection try this command:
```
screen -S tChatBot
```
```
cd telegram-chatbot
```
```
python launch.py
```

This isn't recommend when you are still working on your chatbot,
but it's deffenaly recommended when you're done with it.

# Credits
[Installing Python Package Manager](http://www.saltycrane.com/blog/2010/02/how-install-pip-ubuntu/)

[pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI/)

# Contact
[Telegram](http://telegram.me/useless)
