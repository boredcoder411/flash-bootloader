# Flash-bootloader
Just some notes for me to remember how to flash the micronucleus bootloader on to my digispark attiny85 when they inevitably get wiped
## Pinout:
Note: this is noted arduino to digispark
```
5V -> 5V
GND -> GND
10 -> P5
11 -> P0
12 -> P1
13 -> P2
```
## Steps:
1. Flash "Arduino as ISP" to arduino uno.
2. Copy the .bat and .hex to the root of the arduino IDE.
3. Link the digispark to the arduino with the pinout listed above.
4. Edit the .bat file so that the -PCOM<COM port number> matches the COM port the arduino is on.
5. Run the .bat file as admin
6. Pray
