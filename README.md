# GolimaarGame
We used Verilog HDL on Vivado to program the board, and the game worked on state transition logic. The input hardware included the Dual Axis PS2 joystick with a communication bus set up through the FPGA JXADC ports, and the FPGA buttons.

The game started off with the start display screen, before going into the animation screen, where enemy and friend characters change color and positions every two seconds. The player must shoot the enemy and save the friends.

The screen was displayed through pixel mapping using VGA to VGA output from the board, and were adequately dynamic in their appearance.
