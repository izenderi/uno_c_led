# Arduino Uno Pure C LED Blink
reference: https://github.com/tderflinger/arduino-blink-purec/tree/master
## Pre-requisite
* avr_gcc
* avr_dude
### Linux:
```
sudo apt-get install gcc-avr binutils-avr gdb-avr avr-libc avrdude make
```

### MacOS (Apple Silicon):
* avr_gcc: https://github.com/osx-cross/homebrew-avr
https://formulae.brew.sh/formula/avrdude
* avr_dude: https://formulae.brew.sh/formula/avrdude

## Make and Upload
```
make
make deploy
```
For clean:
```
make clean
```

## Start with your own project
Change the led.c and Makefile