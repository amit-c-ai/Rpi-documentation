# Required :

* __Required :__ 
  * _Raspberry pi_
  * _LAN cable_
  * _Power supply_
  * _PC_
  * _SD-Card/Pen-drive_

* __Flashing OS :__
  * _Download rpi imager_ :
    * [Windows](https://downloads.raspberrypi.org/imager/imager_latest.exe)
    * [Linux](https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb)
    * [Mac Os](https://downloads.raspberrypi.org/imager/imager_latest.dmg)

  * _Choose OS then choose usb then flash__

* __Enabling SSH :__
  * Connect sd card/pendrive to pc
  * Open boot drive and create empty file name SSH
  * Open cmdline file and add "ip=ip_address_of_your_choice"
      Ex: ip=169.254.126.99
      
* __Install Putty and Vnc viewer :__
  * [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
  * [Vnc viewer](https://www.realvnc.com/en/connect/download/viewer/)

* __Connecting rpi :__
  * _First put sd card/pendrive in rpi_
  * _Connect rpi with pc through LAN cable_
  * _Give power supply to rpi_

* __Putty :__
  * Now open putty and type "ip_address_of_your_choice"
  * In side tab : SSH > X11 > Enable X11 forwarding
  * Click on Open
  * Login using default username : pi and password : raspberry
  * Enter command : vncserver :8

* __Vnc viewer :__
  * Open Vnc viewer
  * Type and open `169.254.126.99:8`
      
