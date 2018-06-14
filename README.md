Updated: 2018.6.14
Supporting Raspbian

# retroflag-picase
RetroFlag Pi-Case Safe Shutdown

Turn switch "SAFE SHUTDOWN" on PCB to ON.

--------------------

Example for RetroPie:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 enter terminal.
4. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/install.sh" | sudo bash

--------------------

Example for RecalBox:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press F4 first. And then press ALT-F2 enter termial.
4. User:root Password:recalboxroot
5. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/RetroFlag/retroflag-picase/master/recalbox_install.sh" | bash

--------------------

Example for Raspbian:
1. Make sure internet connected.
2. Make sure keyboard connected.
3. Press Ctrl + Alt + T to enter terminal.
4. In the terminal, type the one-line command below(Case sensitive):

wget -O - "https://raw.githubusercontent.com/Simon1628623/retroflag-picase/master/installRaspbian.sh" | sudo bash

--------------------

Having trouble with typing | ?
1. Go to the terminal (Ctrl + Alt + T).
2. Type sudo raspi-config.
3. Use the arrow keys to move and enter to select.
3. Select option 4 Localisation Options.
4. Select I3 Change Keyboard Layout.
5. Can select either default model or your specific keyboard here.
6. For Keyboard layout select other and find your region.
7. The rest of the settings can be default or whatever you prefer.
8. Once back at raspi-config select finish using the right arrow key twice and hit enter.
