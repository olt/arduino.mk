Arduino.mk
==========

This is a Makefile to build Arduino projects with `make`. It is based on Martin Oldfields Makefile and was adapted to support Arduino 1.0 and user libraries.

Here is an example `Makefile` that includes Arduino.mk

    ARDUINO_DIR  = /Applications/Arduino.app
    USER_LIB_PATH = ~/Documents/Arduino/libraries

    TARGET       = CLItest
    ARDUINO_LIBS = LiquidCrystal
    USER_LIBS    = MyLib

    BOARD_TAG    = uno
    ARDUINO_PORT = /dev/cu.usb*

    include /usr/local/share/Arduino.mk

Place it beside your  `.ino` file and call `make` and `make upload`.