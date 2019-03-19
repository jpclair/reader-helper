# USB Card Reader / Decoder Tool

![alt Example Page](https://github.com/Alavas/reader-helper/blob/master/images/carddecodertool.png)

This repository contains an Arduino sketch as well as a React SPA to allow for an Arduino with a connected Wiegand RFID reader to interface with a webpage. This allows the user to test cards to determine what the formatting is. When connected the Arduino will send the number of bits as well as the raw Hex value from the card. The webpage will then convert this to a binary string.

This tool can be accessed at https://alavas.github.io/reader-helper/.
