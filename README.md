CHR Ubuntu

This script is used to install Mikrotik CHR on VPS Ubuntu versions 20.04, 22.04, and 24.04. Follow the steps below!

sudo su

sudo apt update

sudo apt upgrade

apt-get install git

git clone https://github.com/aseperyana/chr-mikrotik

cd chr-mikrotik

chmod +x install.sh

sudo apt-get install dos2unix

dos2unix install.sh

bash install.sh
