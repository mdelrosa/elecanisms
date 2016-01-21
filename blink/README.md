blink.c
============

In order to run a program on the PIC24 board, one needs to:

1. Open terminal and navigate to the 'elecanisms/blink' directory (which should include blink.c)

2. Run 'scons' in terminal, which will generate 'blink.hex'

3. Navigate to 'elecanisms/site_scons'

4. Connect PIC24 board to PC with USB cable (the green power LED should be illuminated)

5. Put PIC24 board into 'bootloader mode' (press and hold SW1, press RST, release SW1)

6. Run 'python pybootloadergui.py'

7. Navigate to 'File->Import Hex'

8. Import the 'blink.hex' file generated into the bootloader gui

9. Hit 'Write'

10. Hit RST to bring board out of bootloader mode and execute program