# My-own-Sonoff
Modular PCB to imitate a Sonoff with enhanced connectivity
![My-own-Sonoff](/IMG_2042.JPG)


## Goal
I do like the Sonoff devices but had additional requirements, so I decided to create my own board that would allow the following:
* Flexible configuration of your switching as well as Digital and Analog ports.
* Be powered by 230V AC or 5V DC (If you want to switch 230V devices it makes sense to use AV to also power the Wemos D1 mini)
* Fits into a standard project box (Plastic Project Case 116x68x36mm)
* Is easy to program i.e. with Tasmota or your own code

# Features
The PCB has space for:
* AC/DC transformer 230V to 5V / 3W (0.6A) Hi-Link HLK-PM01
* 5.5MM x 2.5MM Female DC socket for PCB (for 5V input)
* up to 2 x Relais that will switch 230V SRD-05VDC-SL-C
  - each requires a PC817C optocopler, two 1K Ohm resistors SMD 0805, a J3Y or Y1 switching transistor SMD, red LED SMD 1206 and a 
    T4 1N4148 SMD 0805 SOD 123 Switching Diode
* a Wemos D1 mini
* 1000uF capacitor to stabilize Wemos opration
* up to 7 analog ports through a CD74HC4051E (when installed digital pins D1, D2,D4 are used to control this analog multiplexor)
* up to 6 digital ports i.e for PIR sensor, temp sensor etc. (D1, D2, D4, D6, D7, D8)

