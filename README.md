# GrandTeam_inline-
سلام امروز یه سورس خوب رو براتون اپن کردیم حتما حتما ستاره بدین :)

___________________________________________________________ 
قدم اول بریم برای نصب ربات API INLINE 
فایل API.LUA رو باز کنید 
به خط 5 برید و توکن رباتی که ساختید  و میخواید از اون اینلاین دریافت بشه رو بزارید 
البته یادتون نره اینلاین ربات Api  رو از بات فادر حتما فعال کنید. 
__________________________ 
حالا برید به خط های 10 و 12 و شناسه خودتون رو به عنوان سودو قرار بدید 
___________________________________________ 
حالا بیاید به خط 162 
و بجای شناسه اول شناسه ربات cli رو قرار بدید. 
و بجای شناسه دوم شناسه خودتون رو قرار بدید 
________________________________________ 
خوب کار ما با ربات api تمام شد. 
نحوه اجرای اون هم بسیار ساده هست: 
طبق مراحل زیر پیش برید: 
فایل api.lua + launch.sh 
رو تو یه پوشه تو سرور اپلود کنید. 
بعد یه ترمینال باز کنید و وارد پوشه بشید 
cd اسم پوشه 
بعد  
chmod +x launch.sh 
و بعد برای اجرا اون 
./launch.sh 
و اگر میخواید هیچ وقت افلاین نشه دستور 
screen ./launch.sh 
رو بزنید 
_______________________________________________ 
حالا بریم سراغ اموزش نصب ربات cli 
دقت کنید 2 ربات تو یه یوزر نباشن 
تو یه یوزر جدید دستورات زیر رو بزنید: 
sudo apt-get update 
 
sudo apt-get upgrade 
 
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev tmux subversion 
_______________________________________________ 
پیش نیاز های ضروری 
 
wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz 
 tar zxpf luarocks-2.2.2.tar.gz 
 cd luarocks-2.2.2 
 ./configure; sudo make bootstrap 
 sudo luarocks install luasocket 
 sudo luarocks install luasec 
 sudo luarocks install redis-lua 
 sudo luarocks install lua-term 
 sudo luarocks install serpent 
 sudo luarocks install dkjson 
 sudo luarocks install lanes 
 sudo luarocks install Lua-cURL 
sudo luarocks install luaxmlrpc 
_____________________________________ 
_____________________________ 
کد های زیر هم پیش نیازه حتما نصب کنید اکثرا ارور میده: 
sudo apt-get install libstdc++6 
sudo add-apt-repository ppa:ubuntu-toolchain-r/test  
sudo apt-get update 
sudo apt-get upgrade 
sudo apt-get dist-upgrade 
________________________________ 
حالا مثل ربات قبلی عمل کنید.تو یه پوشه بریزید و اپلود کنید فایل های سورس رو تو اون 
بعد ترمینال باز کنید وارد پوشه ربات بشید 
cd اسم پوشه 
و بعد 
chmod +x tg 
و بعد 
chmod +x launch.sh 
و بعد دستور زیر رو برای اجرای اون بزنید: 
./tg -s bot.lua 
بعد از شما شماره میخواد و بعد که شماره و کد رو زدید ربات ران میشه 
و اگر میخواید هیچ وقت افلاین نشه کد زیر را وارد کنید 
screen ./launch.sh 
یادتون باشه اگر با دستور ./tg -s bot.lua ربات رو ران کردید 
و خواستید افلاینش کنید با دستور 
quit 
رو تو ترمینال بزنید افلاین میشه 
ctrl +c ya x نزنید. 
یادتون نره تو فایل BOT.LUA 
مسیر خط های 1 و 2 و 9 رو درست کنید مطابق با مسیر سرور خودتون 
همچنین توی فایل API.LUA 
 هم تو خط 4 مسیر رو درست کنید. 
_____________________________________ 
قبل از این که ران بشه برید توی فایل bot.lua 
تو خط 10 شناسه خودتون رو به عنوان سودو بزارید 
الان برید به خط 801و بجای شناسه قرار داده شده شناسه ربات api رو بزارید. 
بعد ذخیره کنید اطلاعات رو و اگر درست پیش رفته باشید اگر دستور 
settings 
رو در گروه بزنید تنظیمات شیشه ای میاد 
___________________________________________ 
 
موفق باشید
@GrandTeam
