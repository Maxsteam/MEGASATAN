# Base [W_SaTaN_W](https://telegram.me/WilSoN_DeVeLoPeR) 

# Developer: [BadBoy](https://telegram.me/bad_bo0y)

## put [lua-tg.c](https://github.com/Maxsteam/megasatan/blob/master/lua-tg.c) in [/root/megasatan/tg/](https://github.com/maxsteam/megasatan/tg) then reboot the server

# Update

### Added [Ultimate Help](https://github.com/Maxsteam/megasatan/plugins/help.lua) 

### Added Lock All & Unlock All & Bugs Fix.

###Added copyright For Set Your Abouts. 

### Add res[Reply] & id @username 

### Set Limit For Help (Only Mods & Owners)

### Add Helper.lua | If User Send A Command With ! Bot Return Use Without Any Symbols.

# How Can I Install It?

## Installation 

```bash
# Tested on Ubuntu 14.04, for other OSs check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```
### Paste [lua-tg.c](https://github.com/maxsteam/megasatan/lua-tg.c)
```bash
# lets install the bot
cd $HOME
git clone https://github.com/maxsteam/megasatan.git
cd megasatan
chmod +x launch.sh
./launch.sh install
cd tg 
rm lua-tg.c && cat > lua-tg.c # Paste Lua-tg.c
make && cd .. # For Support Sticker Operation
./launch.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command on debian-based distros, use: (useful for VPS deployment)
```sh
#https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make unzip git redis-server g++ -y --force-yes && git clone https://github.com/Maxsteam/MEGASATAN.git && cd MEGASATAN && chmod +x launch.sh && ./launch.sh install && ./launch.sh
```
