# BTT MMB CAN Board

Full information on the BTT MMB CAN board can be found here:
https://github.com/bigtreetech/MMB

# Details
This project requires use of four independently controllable servo motors.

When controlling these via an STM32 or similar micro controller, it is mandatory to use an ADC pin.

There are four accessible ADC pins on this board:

PA0 PA1 PA3 PA4

These will be used in the config for the servos. If you use a different pin your servo will not work.
