تلكرام بوت المجموعات
============
طربقة التثبيت
------------
```bash
# After those dependencies, lets install the bot
cd $HOME #Do not write this if you are using c9 or not root accounts
git clone https://github.com/Josepdal/DBTeam.git
cd DBTeam
./launch.sh install
./launch.sh # Will ask you for a phone number & confirmation code.
```
You can also use this command to install the bot in just one step.
```bash
sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get autoremove && sudo apt-get autoclean && sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev tmux subversion -y && cd $HOME && rm -rf DBTeam && rm -rf .telegram-cli && git clone https://github.com/Josepdal/DBTeam.git && cd DBTeam && ./launch.sh install && ./launch.sh
```
تثبيت الغة العربية الان
```
#install arabic_lang
#lang ar
```

-------------
لتعطيل وتفغيل امر للمطور فقط`#plugins`  

لتفعيل `#plugins enable [اسم الامر]`.

لتعطيل `#plugins disable [اسم الامر]`.

