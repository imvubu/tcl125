# tcl125

Using a  Raspberry Pi and Mesa 7i96 board to control a TCL125 lathe.

The Mesa board has been reflashed to reduce number of stepper drivers from 5 to 4,
replacing one with a PWM output for spindle control.

Spindle motor controlled by PWM to 10V convertor driving 180V spidle motor board.

Raspberry Pi is running Linuxcnc on Debian. 

https://github.com/imvubu/tcl125/wiki
