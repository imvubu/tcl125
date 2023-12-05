# tcl125

Using Mesa 7i96 board to control a TCL125 lathe.

Mesa board reflashed to reduce number of stepper drivers from 5 to 4,
replacing one with a PWM output for spindle control.

Spindle motor controlled by PWM to 10V convertor driving 180V spidle motor board.

Running on a Raspberry Pi 4.

When manually configuring the IP address of the RPi to that necessary
to communicate with the Mesa board
use the ip command rather than ifconfig in order to get the correct
routing table entry made automatically.

https://github.com/imvubu/tcl125/wiki
