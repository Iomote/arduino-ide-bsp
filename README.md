# arduino-ide-bsp
This repository contains the board support packages to program and control the **Iomote devices** using the **Arduino IDE**. It contains the libraries to access the basic hardware functions and top communicate with the cloud.

To add the X400 gateway (and future Iomote devices) in the Arduino IDE follow these steps:
* Install the Arduino IDE on your computer. (you can download it form www.arduino.cc Windows - Linux - Mac)

> WARNING: (for Windows users) download the installer from arduino website, not the app from the Windows store (we had problem with that version of the IDE).

Once the Arduino IDE is installed you have to add the X400 libraries:
* Go to menu File -> Preferences
* On the Additional board manager URLs, add: https://github.com/iomote/arduino-ide-bsp/raw/master/package_iomote_index.json  (use comma if there are other addresses) and confirm.
* Open the Board manager (menu Tools -> Board:xxx -> Board Manager)
* Search and install the package Arduino SAMD Boards (32.bits ARM Cortex-M0+) by Arduino
* Search and install the package Iomote X400 by Iomote
* Open the Library Manager  (menu Sketch -> Include Library -> Manage libraries)
* Install the library RTCZero by Arduino
* Select X400 from Tools -> Board:xxx -> Iomote X400

**Now the IDE is ready to create Apps for X400**.

You can find all the docs, API references and tutorial here: [https://iomote.github.io/](https://iomote.github.io/).