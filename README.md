# PS2Wrapper

## A user friendly wrapper object for PS2_Controller.spin.

PS2_Wrapper.spin provides a method for each button and joystick on a standard PlayStation 2 controller. Each button method returns a 1 or 0, depending on whether the button is pressed.
Each joystick method returns a value from 0 to 255, where zero is one extreme, 128 is centered, and 255 is the opposite extreme.

This object depends on PS2_Controller.spin, written by Juan Carlos Orozco. It can be found at http://obex.parallax.com/object/555.

The test program in /Tests displays string representations of all the buttons and joysticks on the PS2 controller. It depends on "Parallax Serial Terminal.spin", which can be found at http://obex.parallax.com/object/444.