# eyePi
[OpenCV](http://www.robopapa.com/Projects/InstallOpenCVOnRaspberryPi)

[Goal](https://www.youtube.com/watch?v=b2kGPWxJybo)
###install:
```
sudo apt-get update

sudo apt-get upgrade

sudo apt-get install python-picamera

sudo aptitude install python-numpy

sudo apt-get install python-pygame

sudo apt-get install python-pip

sudo apt-get install libjpeg62-dev

sudo apt-get install zlib1g-dev

sudo apt-get install libfreetype6-dev

sudo apt-get install liblcms1-dev

sudo pip install pillow

sudo pip install pil

sudo apt-get -y install build-essential cmake cmake-curses-gui pkg-config libpng12-0 libpng12-dev libpng++-dev libpng3 libpnglite-dev zlib1g-dbg zlib1g zlib1g-dev pngtools libtiff4-dev libtiff4 libtiffxx0c2 libtiff-tools libeigen3-dev

sudo apt-get -y install libjpeg8 libjpeg8-dev libjpeg8-dbg libjpeg-progs ffmpeg libavcodec-dev libavcodec53 libavformat53 libavformat-dev libgstreamer0.10-0-dbg libgstreamer0.10-0 libgstreamer0.10-dev libxine1-ffmpeg libxine-dev libxine1-bin libunicap2 libunicap2-dev swig libv4l-0 libv4l-dev python-numpy libpython2.6 python-dev python2.6-dev libgtk2.0-dev	

wget -O openCV-2.4.11.zip https://github.com/Itseez/opencv/archive/2.4.11.zip

unzip openCV-2.4.11.zip

cd openCV-2.4.11

mkdir release

cd release

sudo ccmake ../ 

sudo make

sudo make install
```
[follow this](https://github.com/tasanakorn/rpi-mmal-demo)

[actually this](https://github.com/mikerr/piVision)
###explanding file system
sudo raspi-config
expand filesystem


