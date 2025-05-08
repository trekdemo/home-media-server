## How to install docker-compose on LibreElec
https://wiki.libreelec.tv/installation/create-media
https://forum.libreelec.tv/thread/13695-docker-compose-on-le/

This *might* work

1) Create NEW folder to contain the executable
mkdir /storage/bin
2) Add this to $PATH

nano /storage/.profile

PATH=$HOME/bin:$PATH


3) Install docker from the LE addons (May not be needed)

4) Download Docker compose (All one line)

curl -L "https://github.com/docker/compose/releases/download/1.23.1/docker-compose-$(uname -s)-$(uname -m)" -o /storage/bin/docker-compose

5) Make it executable

chmod +x /storage/bin/docker-compose

6) Check to see it works

cd /storage/bin

./docker-compose --version


## Kodi skin
https://www.technadu.com/best-kodi-skins/8372/#aeon-nox-silvo
https://forum.kodi.tv/showthread.php?tid=355993
