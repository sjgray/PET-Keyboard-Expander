PET/CBM Keyboard Expander
=========================

http://www.6502.org/users/sjgray/projects/petexpkbd/index.html

This is a pcb to expand the PET/CBM keyboard from it's normal 10x8 matrix
to a larger 16x8 matrix. It does this by mounting on the keyboard's VIA
chip socket and using a SN74159 4-to-16 decoder to give the extra line.

The extra matrix lines can be used to support larger matrix keyboards
(such as the CBM-II 16x6 matrix or C128 keyboard etc) or just additional
key switches for added functions, or even a joystick interface.

To add additional keyboards to the PET/CBM it would also be necessary to
modify the PET's Editor ROM keyboard scanning routine and key matrix.
Look on Github for my own Editor ROM project.

