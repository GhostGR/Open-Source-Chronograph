# Open-Source-Chronograph
 An open source chronograph used to measure the speed and energy of projectiles. Mainly intended for airsoft.
 ![finished](https://github.com/GhostGR/Open-Source-Chronograph/blob/da559c730b0adc7d982dfd7f53b529fddc37f72e/Photos/finished.jpg)

## Notes
* If you use phototransistors instead of photodiodes, you will need less components

## Donations :smiley:
Did you find the project useful ? feel free to buy me a cofee :coffee:

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=XSP59UAQV3676)


No hard feeling if you dont :wink:

## Instructions
To upload the firmware to the pi pico
1. Unplug the usb cable
2. Press the "BOOTSEL" button and hold it
3. Plug the usb cable
4. Copy the "Open_Source_chronograph.ino.uf2" to the drive that showed up

## Components used
* TP4056 module with BMS
* 18650 battery
* 1x small power switch  (I used a generic 10x15mm switch)
* SSD1306 128x64 I2C OLED display
* Pi pico with headers soldered
* 4pin right angle male header
* 2x 20pin female headers
* 5v buzzer
* 3 tactile switches
* 2 IR LEDs (and appropriete resistors)
* 1A fuse

### If using phototransitors
* 2x phototransistors

### if using photodiodes
* 2x photodiodes
* 2x 2n3904 BJT or similar
* 2x 330Ω resistors
* 2x 2.2kΩ resistors

## PCB
I used a protoboard and cut it down to fit the enclosure, you can see the dimensions and hole locations in the photos bellow
**NOTE: ** Both PCBs needed to be trimed 1-2mm more tio fit the enclosure, i will design a better enclosure in the future.

### Main PCB
![Mainpcb 1](https://github.com/GhostGR/Open-Source-Chronograph/blob/bf926e40d05efec4db9b234e9c52c35f1d220e2f/Photos/1.jpg)
![Mainpcb 2](https://github.com/GhostGR/Open-Source-Chronograph/blob/bf926e40d05efec4db9b234e9c52c35f1d220e2f/Photos/2.jpg)
![Mainpcb 3](https://github.com/GhostGR/Open-Source-Chronograph/blob/bf926e40d05efec4db9b234e9c52c35f1d220e2f/Photos/3.jpg)

### Buttons PCB
![buttonspcb 1](https://github.com/GhostGR/Open-Source-Chronograph/blob/bf926e40d05efec4db9b234e9c52c35f1d220e2f/Photos/4.jpg)
![buttonspcb 2](https://github.com/GhostGR/Open-Source-Chronograph/blob/bf926e40d05efec4db9b234e9c52c35f1d220e2f/Photos/5.jpg)
