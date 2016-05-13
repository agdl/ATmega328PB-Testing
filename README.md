# ATmega328PB - Testing

This package is based on: https://github.com/watterott/ATmega328PB-Testing

## Software

### Boards Package
Add the following URL to the Arduino Boards Manager (*File->Preferences*):
```
https://raw.githubusercontent.com/agdl/ATmega328PB-Testing/master/package_ATmega328PB-Testing_index.json
```
and install the *ATmega328PB Boards* via the Boards Manager (*Tools->Boards->Boards Manager*).

### Manual Installation
The current Arduino avr-gcc toolchain (4.8.1) does not support the ATmega328PB.
To get support you can replace it with the below Atmel avr-gcc toolchain (4.9.2) and update the files in ```/arduino/hardware``` with the files from [this repository](https://github.com/agdl/ATmega328PB-Testing/raw/master/ATmega328PB-Testing.zip).

**Atmel Toolchain**
* Windows: http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx

* Linux: http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORLINUX.aspx

* Mac: http://distribute.atmel.no/tools/opensource/Atmel-AVR-GNU-Toolchain/3.5.1/
