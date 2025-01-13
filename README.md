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
- 1x 3D-printed cover ([left]() or [right]())		<!-- include links -->
- 1x [3D-printed case]()		<!-- include links -->
- 1x [3D-printed turntable]()		<!-- include links -->
- 4x 1x1 keycap
- 7x 1x1.25 keycap
- 6x Rubber feet

### Electronic Parts
- 1x Pro Micro Arduino
- 1x Bourns PEC16-2015F-N0024 Encoders
- 11x Gateron Yellow Switches (or any other MX-style switch)
- 1x Micro USB Male to USB A Male
- 11x 3mm LEDS		<!-- check size -->

### Other Parts
- Solder
- Wire
- Glue

### Recommended Tools
- Soldering iron
- 3D printer
- Wire stripper
- Wire cutter
- Soldering fume fan (optional)
- Solder sucker (optional)



## Build
1. 3D print the cover ([left]() or [right]()), [case](), and [turntable]()		<!-- include links -->
> [!TIP]
> Skip to the steps 2-6 to save time while waiting for the 3D prints to finish.
> Print the parts in the order above
2. Attach LEDs into the switches. Make sure the LED pins are in this position: ![]()		<!-- img -->
> [!TIP]
> ![]() The negative pin is the shorter leg or the side with the larger metal inside the transparent plastic		<!-- img --> 
3. Connect and solder the negative pin of the LED to the lower switch pin with a wire: ![]()		<!-- img -->
4. Cut the legs of each LED to 1cm		<!-- check size -->
5. Connect and solder wire (~10cm long) to the pins of each switch, as well as the positive LED leg: ![]()		<!-- img & check wire length -->
> [!TIP]
> Color code or label wires for organization and convenience
> ![]()		<!-- example -->
6. Connect and solder wire (~10cm long) to the pins of the encoder		<!-- check wire length -->
> [!NOTE]
> If you are using different encoders from the ones listed in the [Assembly List](), note that the Bourn pin names are different to most other encoders.
> For reference the Bourne pins are equal to most other encoders in this way: A = clock, B = data, C = ground 
7. Slot the Gateron switches into the cover. Make sure the wires go through the cover
8. Glue Gateron switches into the cover. 
> [!NOTE]
> Make sure all of the switches are aligned correctly in terms of the direction the LED is facing.
> Most people choose north facing (LEDs face toward you) or south facing (LEDS face away from you).
> Do some research and choose what you prefer
9. Secure the encoder to the cover with a hex nut (it should be included with the encoder)
10. Plug the Pro Micro into your computer and upload [PocketIIDX.ino]() into the Pro Micro through the [Arduino IDE](https://www.arduino.cc/en/software)		<!-- link -->
11. Unplug the Pro Micro
![]()		<!-- wiring diagram -->
12. Refer to the wiring diagram above and connect the wires on the switches and LEDs to the Pro Micro
13. Secure the Pro Micro to the case
14. Secure the cover to the case
15. Put the keycaps on the switches and attach the turntable to the encoder: ![]()		<!-- img -->
16. Plug the Pro Micro back into your computer and test the keys and turntable. Check if the keys output properly: ![]()		<!-- img -->
17. Done!
