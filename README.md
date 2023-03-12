# ppm2usb


## What

Port of https://github.com/ciorceri/ppm2usb to cheap and fast RP2040 so that you can play FPV sims using an old controller. 


## How to connect

Add PPM input from your radio to PIN 5, make sure you do voltage divider as the input is 3v3.


## How to flash

Run ```pio flash``` or downlaod u2f from Actions tab.


## How to test

Attach to computer and go to the https://gamepad-tester.com/, you should see the inputs.
