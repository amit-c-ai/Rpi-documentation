# Wireless Connection of RPi to PC :

* __Required :__ 
  * _Raspberry pi_
  * _Power supply_
  * _PC_
  * _SD-Card/Pen-drive_

* __Flashing OS :__
  * _Download Raspberry Pi imager_ :
    * [Windows](https://downloads.raspberrypi.org/imager/imager_latest.exe)
    * [Linux](https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb)
    * [Mac Os](https://downloads.raspberrypi.org/imager/imager_latest.dmg)
    
  *_Wireless Connection Setting_:
    * Open Raspberry Pi Imager
    * Hit 'Ctrl+Shift+x' for advanced options
    * Choose image customisation option
    * Click on 'Set hostname' and enter a hostname of your choice
    * Click on 'Enable SSH' and check password authentication option
    * Set username and password accroding to your choice
    * Configure your wifi and don't forget to change wifi country with your respective country
    * Click on save option to save changes
    * Choose OS then choose usb and then write
      
* __Install Putty and Vnc viewer :__
  * [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
  * [Vnc viewer](https://www.realvnc.com/en/connect/download/viewer/)

* __Connecting rpi :__
  * _First put sd card/pendrive in rpi_
  * _Give power supply to rpi_

* __Putty :__
  * Now open putty and type your hostname
  * Click on Open
  * Login using username and password provided by you
  * Enter command : vncserver :8

* __Vnc viewer :__
  * Open Vnc viewer
  * Type and open `169.254.126.99:8`
      
