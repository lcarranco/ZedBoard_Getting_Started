# ZedBoard_Getting_Started
Getting started with your ZedBoard

Followed this [Setup Guide](http://zedboard.org/sites/default/files/CY7C64225_Setup_Guide_1_1.pdf)

#5 in the Setup Guide is misleading. Here is the instuction:
> Unzip the driver to a known directory, not a temporary directory that may be deleted later.

The driver is an exe program. NOT a zip file. Download and install the exe
![alt text](https://github.com/lcarranco/zedBoard_getting_started/raw/master/src/images/driver.PNG)

#9 in the Setup Guide shows the ZedBoard listed under Ports (Com & LPT) as "Cypress Serial (COM4)". In my setup, it shows as "USB Serial Port (COM3)"

![alt text](https://github.com/lcarranco/zedBoard_getting_started/raw/master/src/images/device-manager.PNG)

#10 in the Setup Guide shows any Windows operating system not Windows XP needs to download the terminal program Tera Term

After installing Tera Term, need to set up the UART configuration. Make sure the ZedBoard is connected via USB to your computer and the device is powered on. Click File -> New Connection. Then click Serial and ok
![alt text](https://github.com/lcarranco/zedBoard_getting_started/raw/master/src/images/new-connection.png)

Next click Setup -> Serial port...
Change Baud rate to 15200 then click ok.
![alt text](https://github.com/lcarranco/zedBoard_getting_started/raw/master/src/images/port-setup.png)
