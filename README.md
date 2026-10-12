# 3A-UPS-module
made for hack club half life in 1 week. cut me some slack

This is supposed to be a UPS (uninterruptible power supply) module to power portable diy electronics projects.

It was inspired by the adafruit powerboost 1000c, but I wanted usb C connection and to be able to provide higher current to power devices such as a rapsberry pi.

It uses a BQ25306 for battery charging and load sharing, and a TPS61089 to boost the lithium ion battery to a 5V output. both chips are by Texas instruments. 

<img width="1038" height="615" alt="Screenshot 2026-10-11 203945" src="https://github.com/user-attachments/assets/cb8f06f6-29cc-4d14-9b9e-2e0804e55732" />
*kicad render*

<img width="1278" height="602" alt="Screenshot 2026-10-11 203904" src="https://github.com/user-attachments/assets/8e5199f0-8b94-4a19-ae91-e812e1c8afc9" />
*schematic*


I have not actually built this yet so I'm not sure if it even works
