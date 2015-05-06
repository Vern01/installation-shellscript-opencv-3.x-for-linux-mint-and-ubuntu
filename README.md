# OpenCV 3.x Installation Script 


This script works on Linux Ubuntu 14.04.2 LTS (Trusty Tahr) and Mint 17.1 (Rebecca) and probably other version and OS.

I wrote this script because it's quite long and difficult to install OpenCV correctly.

Launch the script:

`sudo sh opencv-mint_ubuntu.sh`

Modify the parameters of the script if the latest version > 3.0.0-rc1

After all was installed, test if OpenCV works with the little program image-conversion.cpp:

`cd Example`

`sudo cmake .`

`sudo make`

`./image-conversion lena.jpg lena.png`

For run your own program you should just modify CMakeLists.txt and replace image-conversion by the program's name.






