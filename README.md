# Digispark-RubberDucky

Digispark is a development board with the ATMEL AVR ATTINY85 microcontroller, which can be plugged directly into the computer's USB and programmed using the Arduino IDE.

The intention is to use Digispark as a replacement for the Rubber Ducky which is very expensive.

## Installation Instructions

- [Digistump](https://digistump.com/wiki/digispark/tutorials/connecting)

> WARNING: Use the Arduino IDE in super user mode

## Pin outs

- All pins can be used as Digital I/O
- Pin 0 → I2C SDA, PWM (LED on Model B)
- Pin 1 → PWM (LED on Model A)
- Pin 2 → I2C SCK, Analog In
- Pin 3 → Analog In (also used for USB+ when USB is in use)
- Pin 4 → PWM, Analog (also used for USB- when USB is in use)
- Pin 5 → Analog In

## Digikeyboard Library Keystrokes

### Special Keys

- MOD_CONTROL_LEFT – Left Ctrl key
- MOD_SHIFT_LEFT – Left Shift key
- MOD_ALT_LEFT – Left Alt key
- MOD_GUI_LEFT – Left Windows key
- MOD_CONTROL_RIGHT – Right Ctrl key
- MOD_SHIFT_RIGHT – Right Shift key
- MOD_ALT_RIGHT – Right Alt key
- MOD_GUI_RIGHT – Right Windows key

### Alphabets

- KEY_A
- KEY_B
- KEY_C
- KEY_D
- KEY_E
- KEY_F
- KEY_G
- KEY_H
- KEY_I
- KEY_J
- KEY_K
- KEY_L
- KEY_M
- KEY_N
- KEY_O
- KEY_P
- KEY_Q
- KEY_R
- KEY_S
- KEY_T
- KEY_U
- KEY_V
- KEY_W
- KEY_X
- KEY_Y
- KEY_Z

### Numbers

- KEY_1
- KEY_2
- KEY_3
- KEY_4
- KEY_5
- KEY_6
- KEY_7
- KEY_8
- KEY_9
- KEY_0

### Functions

- KEY_F1
- KEY_F2
- KEY_F3
- KEY_F4
- KEY_F5
- KEY_F6
- KEY_F7
- KEY_F8
- KEY_F9
- KEY_F10
- KEY_F11
- KEY_F12

## Links

- [Rubber Ducky Payloads](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads)
- [digiQuack](https://github.com/CedArctic/digiQuack)