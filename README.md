#Photocopi
The Photcopi

This is a project that uses a network of Raspberry Pi(3b)s to detect  motion and track an object, try to recognize
their face otherwise notify  user of possible suspicious activity within range of system. It displays  the object's
coordinates,  A/V of target. If facial recognition is  sucessful, Home screen will display with customized feeds of
interest to user. Voice recognition will query internet with search queries, account  contents, and interaction to
devices connected to system.


sudo apt update
sudo apt upgrade
cd Desktop/
nano camera1.py
git config --global user.name "Igmu"
git config --global user.email "IgmuHammerer@gmail.com"
git init
pip3
pip3 install adafruit-circuitpython-neopixel
sudo apt-get -y install git build-essential cmake pkg-config checkinstall
sudo apt-get -y install libjpeg-dev libpng-dev libtiff-dev
sudo apt-get -y install libprotobuf-dev protobuf-compiler
sudo apt-get -y install libv4l-dev
sudo apt-get -y install libavcodec-dev libavformat-dev libswscale-dev
pip3 install numpy
sudo dphys-swapfile swapoff
sudo sed -i 's:CONF_SWAPSIZE=.*:CONF_SWAPSIZE=2048:g' /etc/dphys-swapfile
sudo /etc/init.d/dphys-swapfile stop
sudo /etc/init.d/dphys-swapfile start
cd usr/local/
sudo mkdir -p opencv && cd opencv
sudo mkdir -p build && cd build
git clone https://github.com/opencv/opencv.git
git clone https://github.com/opencv/opencv_contrib.git
sudo reboot
free -m
