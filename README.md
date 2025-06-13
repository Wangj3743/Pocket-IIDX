> [!WARNING]  
> This repository is UNDER CONSTRUCTION. Many aspects of the project are missing and unfinished. Thank you for your understanding 

# Pocket-IIDX
a DIY mini rhythm game controller compatible with games such as LR2, Beatoraja, Infinitas, osu!, etc.

Inspired by speedpotato's [Pocket-SDVX](https://github.com/speedypotato/Pocket-SDVX)


## Features


## Usage


## Customization


## Assembly List
### Structural Parts
- 1x [3D-printed keyplate]()	<!-- include links -->
- 1x [3D-printed case]()		<!-- include links -->
- 1x [3D-printed turntable]()		<!-- include links -->
- 7x 1x1.25 keycaps (4 white, 3 black)     <!-- include links -->
- 6x Rubber feet

### Electronic Parts
- 1x Pro Micro Arduino
- 1x Bourns PEC16-2015F-N0024 encoders
- 7x Gateron Yellow switches (or any other MX-style switch)
- 7x 3mm LEDs (4 white, 3 black)		<!-- check size -->
- 2x push buttons <!-- these have an actual name but i forgot what they are -->
- 1x Micro USB Male to USB A Male

### Other Parts
- Solder
- Wire
- Glue

### Tools
- Soldering iron
- 3D printer
- Wire stripper
- Wire cutter
- Heat shrink (optional but recommended for safety)
- Soldering fume fan (optional)
- Solder sucker (optional)



## Build
1. 3D print the [keyplate](), [case](), and [turntable]()		<!-- include links -->
> [!TIP]
> Jump to the steps 2-6 while you wait for the 3D prints to finish
> Print everything in the order above as this is the chronological order that parts will be used
2. Attach LEDs into the switches. Make sure the LED pins are in this position: ![]()		<!-- img -->
> [!TIP]
> ![]() The negative pin is the shorter leg and/or the side with the larger metal inside the transparent plastic		<!-- img --> 
3. Connect and solder the negative pin of the LED to the lower switch pin with a wire: ![]()		<!-- img -->
4. Cut the legs of each LED to 1cm		<!-- check size -->
5. Connect and solder wire (~10cm long) to the pins of each switch, as well as the positive LED leg: ![]()		<!-- img & check wire length -->
> [!TIP]
> Color code or label wires for organization and convenience
> ![]()		<!-- example -->
6. Connect and solder wire (~10cm long) to the pins of the encoder		<!-- check wire length -->
> [!NOTE]
> If you are using different encoders from the ones listed in the [Assembly List](), note that pin orders and names may be different
> For reference, the Bourns pins are A = clock, B = data, C = common ground 
7. Slot the Gateron switches into the keyplate. Make sure the wires go through the keyplate
8. Glue Gateron switches into the keyplate
> [!NOTE]
> Make sure all of the switches are aligned correctly based on LED position (I recommend having the LEDs face towards you so that you see the light)
> ![]()   <!-- img -->
9. Secure the encoder to the keyplate with a hex nut (it should be included with the encoder)
![]()		<!-- wiring diagram -->
10. Refer to the wiring diagram above and connect the wires on the switches and LEDs to the Pro Micro
11. Install the [Arduino IDE](https://www.arduino.cc/en/software)
12. Plug the Pro Micro into your computer, choose the right port and model (Arduino Leonardo) and upload [PocketIIDX.ino](). When its finished uploading unplug the Pro Micro from your computer		<!-- link -->
14. Secure the Pro Micro to the case
15. Secure the keyplate to the case
16. Put the keycaps on the switches and attach the turntable to the encoder: ![]()		<!-- img -->
17. Plug the Pro Micro back into your computer and test the keys and turntable. Check if the keys output properly: ![]()		<!-- img -->
18. Done!
