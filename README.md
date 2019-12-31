# Welle.io-Web-CLI for RTL-SDR dongle

Dependency:

sudo apt-get install libmp3lame-dev libmpg123-dev librtlsdr-dev

Installation: (v2.0-beta1 for last good working version, so remplace by master or next for actual version.)

* cd /usr/src/
* sudo git clone https://github.com/AlbrechtL/welle.io
* cd welle.io/
* sudo git checkout v2.0-beta1
* mkdir build
* cd build/
* sudo cmake .. -DRTLSDR=1 -DBUILD_WELLE_IO=0
* sudo make
* ./welle-cli -w 7979 -c 5B -C 2 -P -u

connect:

http://127.0.0.1:7979/ or copy welleio.conf file in /etc/supervisor/conf.d directory for autostart with the system


sudo /etc/init.d/supervisor restart

