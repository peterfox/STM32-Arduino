
# STM32-Arduino
---

Arduino board package origin files for the STM32 MCU based target boards, including the RedBear Duo. There are many examples included in the board package under **"arduino/libraries/RedBear_Duo/examples"**. Any contributions to this repository are really appreciated.

## Directories and Files

* `arduino/avrdude_conf/`: AVRDUDE configuration file
* `arduino/cores/`: Pre-compiled wiring libraries and other core files
* `arduino/firmwares/`: Duo board system firmware images
* `arduino/libraries/`: Arduino examples for the Duo board
* `arduino/system/`: ARM CMSIS files
* `arduino/tools/`: Utils for building and uploading sketch
* `arduino/variants/`: Linker scripts and Open OCD scripts for the Duo board
* `arduino/boards.txt`: Board informations
* `arduino/platform.txt`: Building and uploading rules
* `arduino/programmers.txt`: programmers definition
* `pack.sh`: Script to generate the corresponding board package in `.zip` format
* `test.sh`: Script to replace the previous origin files that are generated by installing the board package using Boards Manager with the current origin files. 

Any features, enhancements and bugfixes to the board package has been documented in this [Change-log](#CHANGELOG.md).

For users only want to playing with the boards need not to clone or download this repository, since the Arduino IDE has provided an easy way (known as **Boards Manager**) for you to install the board package. See the step-by-step [Arduino Board Package Installation Guide](https://github.com/redbear/Duo/blob/master/docs/arduino_board_package_installation_guide.md).

To get started with the boards supported in this board package on Arduino IDE, Please follow the [Getting Started](https://github.com/redbear/Duo/blob/master/docs/getting_started_with_arduino_ide.md) guide.

## License

Copyright (c) 2016 Red Bear

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.