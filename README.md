# Motherboard-for-3d-printer-using-Rp2040-microcontroller
This is a motherboard using Raspberry pi RP2040 microcontroller with tmc2208 driver

The functions of this motherboard include:

- Reverse polarity protection.

- Expansion port for BLtouch.

- Can control up to 5 motors.

- Motor control driver is Tmc2208.

- 4 cooling fans including 3 24v fans and 1 pwm controlled fan.

- Hotend and bed are controlled by mosfet.

- Protection fuse is located at the 24v power supply, Hotend, Bed, Speaker.

- 5 logic switches to adjust the driver's operating mode

- The smd resistor often used to adjust the current limit has been replaced by a trimmer potentiometer which is more sturdy and easier to adjust

- To limit the current, I designed two holes for the user to measure directly from a multimeter.

- I added the Max98357 audio module that allows users to play sounds, music, not just melodies like other motherboards

- Due to the limitation of the number of Gpio pins, I have to share that pin with thermistor number 3 and two control pins of driver number 5, but I added a switch so you can switch between the two sound playback functions or add another driver.

- I use a 1.3 inch oled display module combined with an encoder module for control because I want to use I2c for communication to save pins

- Here is the product link: https://www.amazon.com/Display-Combined-Encoder-Interface-arduino/dp/B0DMYQHM9J

- This is a motherboard designed by me according to my preferences so it will not be compatible with existing firmware so I may have to find a way to tweak the firmware to suit it

- This is a project developed by me alone so there will be mistakes and limitations so I hope you will give me your comments in the comment section so I can improve further.
