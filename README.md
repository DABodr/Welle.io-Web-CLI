# Welle.io-Web-CLI

Dependency:

sudo apt-get install libmp3lame-dev libmpg123-dev librtlsdr-dev


* git clone https://github.com/AlbrechtL/welle.io
* cd welle.io/
* git checkout next
* mkdir build
* cd build/
* cmake .. -DRTLSDR=1 -DBUILD_WELLE_IO=0
* make
* ./welle-cli -w 7979 -c 5B -C 2 -P -u

connect:

http://127.0.0.1:7979/
