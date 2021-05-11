# Instructions

1. Enter BOOT drive by double-tapping RESET button.

- It can be tricky to get the double tap right; when successful, you'll see a 'BOOT' drive appear.

2. Copy the relevant Circuitplayground .UF2 file onto the BOOT drive.

- Board will 'reset' automatically, and should re-mount as a 'CIRCUITPY' drive.

3. Copy your 'config.txt' file onto the CIRCUITPY drive.

- In this example, only enter a single digit, no spaces or return characters, into the file. E.g.:

```
3
```

4. Enter BOOT drive by double-tapping RESET button

5. Copy the arduino firmware .UF2 file onto the BOOT drive

- In this example, the firmware is called 'blinker_firmware.uf2'.  
- The board should automatically reset, and run the arduino code. (If it doesn't, you can reset it automatically with a single tap).
- The arduino code should read the config.txt file and blink the associated # of times each loop.


