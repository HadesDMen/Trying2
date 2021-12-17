# Trying2
##Setting rpi
First went to website https://core-electronics.com.au/tutorials/face-identify-raspberry-pi.html run 1st code...result, this device is not rpi or something similar.
Second went to https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/.. Installing depedencies directly...
1)CMAKE error
  404  Not Found [IP: 199.232.22.132 80]
  E: Failed to fetch http://ftp.debian.org/debian/pool/main/libu/libuv1/libuv1_1.24.1-1_i386.deb  404  Not Found [IP: 199.232.22.132 80]
  404  Not Found [IP: 199.232.22.132 80]
  E: Failed to fetch http://ftp.debian.org/debian/pool/main/libu/libuv1/libuv1_1.24.1-1_i386.deb  404  Not Found [IP: 199.232.22.132 80]
  Proceed
2)
  E: Unable to locate package libjasper-dev
  **E: Package 'libpng12-dev' has no installation candidate**
  Proceed
3) sudo apt-get install libgtk2.0-dev libgtk-3-dev
   While running this code...many errors as 404 not found ip address errors..
   Proceeded
4) 
   export WORKON_HOME=$HOME/.virtualenvs
   export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3
   source /usr/local/bin/virtualenvwrapper.sh
