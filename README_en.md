# Modified NanoHatOLED

GitHub [中文](https://github.com/Peter-Zhifei/BakeBit/blob/master/README.md)[日本語]()

Gitee [中文](https://gitee.com/peter-Zhifei/BakeBit/blob/master/README.md)[日本語]()


## Changed

- You can turn off the display after 1 minute automatically.

- When you press any key you can back to the previous display.

- Optimize the IP display.

## Setup

- Exchange /Software/Python/bakebit_nanohat_oled.py

```
$ su root
# use root account
$ sudo pkill -f bakebit_nanohat_oled.py
# End the process
$ cd NanoHatOLED
# To /NanoHatOLED
$ rm -rf BakeBit
# Delete all file
$ git clone https://github.com/Peter-Zhifei/BakeBit.git
# Clone my git
# For Chinese you can $ git clone https://gitee.com/peter-zhifei/BakeBit.git
$ cd BakeBit/Software/Python/
# To thefile
$ sudo python bakebit_nanohat_oled.py &
# Start and backgrounder
$ sudo reboot
# Reboot
```

## Issues

Please put issues to the previous issues

# Previous README

## **BakeBit**

BakeBit is an open source platform for connecting BakeBit Sensors to the NanoPi NEO/NEO2. It is based on the GrovePi.

Currently supported boards: NanoPi NEO, NanoPi NEO2, NanoPi NEO Air.

## License

The MIT License (MIT)

BakeBit: an open source platform for connecting BakeBit Sensors to the NanoPi NEO.
Copyright (C) 2016 FriendlyARM

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
