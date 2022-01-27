# CPU-MINER
```
termux-setup-storage
```
# OS-INSTALLER
```
termux-setup-storage
```
```
apt update -y
```
```
apt upgrade -y
```
```
apt install git -y
```
```
git clone https://github.com/mantvmass/os-installer
```
```
cd os-installer
```
```
sh build.sh
```
Open Os
```
os-installer
```
# CPU-MINER
```
apt update && apt upgrade
```
```
apt install wget
```
```
apt install proot
```
```
apt install git
```
```
apt-get install libcurl4-openssl-dev -y && apt-get install libssl-dev -y && apt-get install libjansson-dev -y && apt-get install automake -y && apt-get install autotools-dev -y && apt-get install build-essential -y && apt-get install nano -y
```
```
apt install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev
```
```
mkdir cpuminer
```
```
cd cpuminer
```
```
apt install automake autoconf pkg-config libcurl14-openssl-dev libjansson-dev libssl-dev libgmp-dev make g++
```
```
git clone https://github.com/tpruvot/cpuminer-multi
```
```
./build.sh finish.
```
```
Now you can try your pool (eobot account) some like this :
```
```
./cpuminer -a x11 -o stratum+tcp://x11.eobot.com:5555 -u eobot.991010 -p x -t 4 -- -a = algorithm -- -o = pool -- -u = user -- -p = password -- -t = thread / cpu
Then, next time and every time you want mining, because you had finished the installation on your android, you can do just :
```
```
cd termux-ubuntu
```
```
./start-ubuntu.sh
```
```
cd cpuminer/cpuminer-multi
```
```
./cpuminer -a x11 -o stratum+tcp://x11.eobot.com:5555 -u eobot.[Your ID of EoBot] -p x -t [how many cpu you want to allocate]
```
exit for quit 😂

