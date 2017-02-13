# viking_bot
#INSTALL

```sh
sudo apt-get update

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev

sudo pip3 install redis
sudo service redis-server restart
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge

git clone https://github.com/RagnarDEV/viking_bot.git


cd viking_bot
chmod +x install
./install
