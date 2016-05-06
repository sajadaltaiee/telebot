تلكرام بوت المجموعات
============
طريقة التثبيت
------------
يجب ان يكون لديك سيرفر يمكنك لحصول عليه من موقع c9.io
ثم اكتب هذا الامر
sudo apt-get update
..
ثم اكتب هذا
```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```
------------
```bash
# ظع هذه الاوامر في السيرفر تدريجيا
cd $HOME
git clone https://github.com/sajadaltaiee/telebot.git
cd telebot
./launch.sh install
./launch.sh # هنا سوف يطلب منك رقم البوت وبعدها الباسورد.
```
------------------
تثبيت الغة العربية الان
```
#install arabic_lang
#lang ar
```

-------------
لتعطيل وتفعيل البلاجنس

لتفعيل `#plugins enable [اسم الامر]`.

لتعطيل `#plugins disable [اسم الامر]`.

