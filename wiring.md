# 1 basic
## 1TT, 7BTN, 0EXT, 0LED
              _______________
Bourns A --- -| TX1     RAW |-
Bourns B --- -| TX0     GND |-
Bourns C --- -| GND     RST |-
GND -------- -| GND     VCC |-
GND --- BTN1 -| 2    A3(21) |-
GND --- BTN2 -| 3    A2(20) |-
GND --- BTN3 -| 4    A1(19) |-
GND --- BTN4 -| 5    A0(18) |-
GND --- BTN5 -| 6        15 |-
GND --- BTN6 -| 7        14 |-
GND --- BTN7 -| 8        16 |-
             -| 9        10 |-
              ---PRO MICRO---


# 2 flashy but functional
## 1TT, 7BTN, 2EXT, 7LED
              _______________
Bourns A --- -| TX1     RAW |-
Bourns B --- -| TX0     GND |- -------- GND
Bourns C --- -| GND     RST |-
GND -------- -| GND     VCC |-
GND --- BTN1 -| 2    A3(21) |- EXT2 --- GND 
GND --- BTN2 -| 3    A2(20) |- EXT1 --- GND 
GND --- BTN3 -| 4    A1(19) |- LED7 --- GND 
GND --- BTN4 -| 5    A0(18) |- LED6 --- GND 
GND --- BTN5 -| 6        15 |- LED5 --- GND 
GND --- BTN6 -| 7        14 |- LED4 --- GND 
GND --- BTN7 -| 8        16 |- LED3 --- GND 
GND --- LED1 -| 9        10 |- LED2 --- GND 
              ---PRO MICRO---


# 3 pure functionality
## 1TT, 7BTN, 4EXT, 0LED
              _______________
Bourns A --- -| TX1     RAW |-
Bourns B --- -| TX0     GND |- -------- GND
Bourns C --- -| GND     RST |-
GND -------- -| GND     VCC |-
GND --- BTN1 -| 2    A3(21) |-
GND --- BTN2 -| 3    A2(20) |-
GND --- BTN3 -| 4    A1(19) |-
GND --- BTN4 -| 5    A0(18) |-
GND --- BTN5 -| 6        15 |-
GND --- BTN6 -| 7        14 |- EXT4 --- GND
GND --- BTN7 -| 8        16 |- EXT3 --- GND
GND --- EXT1 -| 9        10 |- EXT2 --- GND
              ---PRO MICRO---


# 4 everything
## 1TT, 7BTN, 4EXT, 11LED
              _______________
Bourns A --- -| TX1     RAW |-
Bourns B --- -| TX0     GND |- -------- GND
Bourns C --- -| GND     RST |-
GND -------- -| GND     VCC |-
GND --- BTN1 -| 2    A3(21) |-
GND --- BTN2 -| 3    A2(20) |-
GND --- BTN3 -| 4    A1(19) |- 74HC959 latch
GND --- BTN4 -| 5    A0(18) |- 74HC959 clock
GND --- BTN5 -| 6        15 |- 74HC959 data
GND --- BTN6 -| 7        14 |- EXT4 --- GND
GND --- BTN7 -| 8        16 |- EXT3 --- GND
GND --- EXT1 -| 9        10 |- EXT2 --- GND
              ---PRO MICRO---
