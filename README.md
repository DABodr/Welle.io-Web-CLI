# Welle.io-Web-CLI

Dependency:

sudo apt install libmp3lame-dev
sudo apt install libmpg123-dev
sudo apt install librtlsdr-dev


git clone https://github.com/AlbrechtL/welle.io
cd welle.io/
git checkout next
mkdir build
cd build/
cmake .. -DRTLSDR=1 -DBUILD_WELLE_IO=0
make
./welle-cli -h
./welle-cli -c 12A -D -w7979

connect:

http://127.0.0.1:7979/
