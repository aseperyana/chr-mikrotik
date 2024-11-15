CHR Ubuntu

Script berikut ini digunakan untuk melakukan install Mikrotik CHR di VPS Ubuntu versi 20.04, 22.04, and 24.04.
Ikuti langkah-langkah di bawah ini!

sudo su

git clone https://github.com/aseperyana/chr

cd chr

chmod +x install.sh

sudo apt-get install dos2unix

dos2unix install.sh

bash install.sh
