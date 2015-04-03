# firmware-mod-kit
Automatically exported from code.google.com/p/firmware-mod-kit

using in ubuntu 14.0.5

cd ./src

sudo apt-get install zlib1g.dev
sudo apt-get install liblzma-dev

#安装主要编译工具 gcc, g++, make 
sudo apt-get install build-essential 
sudo apt-get install autoconf automake1.9 
sudo apt-get install flex bison 

./configure
make

# below is error must use ./src/binwalk-1.0/src/setup.py to install the magic
#apt-get install python-setuptools
#easy_install python-magic

