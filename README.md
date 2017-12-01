# arduino-ide-bsp
This repository contains the board support packages to program and control the **Iomote devices** using the **Arduino IDE**. It contains the libraries to access the basic hardware functions and top communicate with the cloud.

To add the X400 gateway (and future Iomote devices) in the Arduino IDE follow these steps:
1. Open the **Preferences** of the Arduino IDE (File-> Preferences)
2. In the "settings" tab, and in the **Additional board manager URL** field, add this URL `https://github.com/iomote/arduino-ide-bsp/raw/master/package_iomote_index.json`, then click OK.
3. Open the **Boards Manager** (Tools->Board:...->Board->Board Manager)
4. Install the IOMote Gateway package
5. Select the desired device under **IOMote devices** in Tools->Board menu
6. Compile and upload your sketches as usual

You can find all the docs, API references and tutorial here: [https://iomote.github.io/](https://iomote.github.io/).