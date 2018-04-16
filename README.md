# CHIP_Lapse
C.H.I.P. powered camera timelapse slider

This project will use a CHIP to control a camera slider.

The rail length will be variable.

A belt and stepper will drive the camera along the x axis with an H-Bridge.
A gear and stepper will turn the camera around the Y axis with an easyDriver.
The CHIP will control the camera using the GPhoto2 commands.
Limit switches will prevent over-travel and be used in setup.


UI:
• detect camera
• set X track
• set Y rotation
• preview move
• set duration & shots
