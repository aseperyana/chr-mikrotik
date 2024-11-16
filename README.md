# CHR Mikrotik
```sh
Mikrotik CHR Versiona: 7.16.1
```
This script is used to install Mikrotik CHR on VPS Ubuntu versions 18.04, 20.04, 22.04, and 24.04

## Installation

Please access your VPS using the remote control application, and follow these steps:.

```sh
sudo su
sudo apt update
sudo apt upgrade
sudo apt-get install git
git clone https://github.com/aseperyana/chr-mikrotik
cd chr-mikrotik
chmod +x install.sh
bash install.sh
```
