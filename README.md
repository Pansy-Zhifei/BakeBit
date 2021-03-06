# 魔改NanoHatOLED

GitHub [English](https://github.com/Peter-Zhifei/BakeBit/blob/master/README_en.md) | [日本語]()

Gitee [English](https://gitee.com/peter-Zhifei/BakeBit/blob/master/README_en.md) | [日本語]()

## 修改

- 增加OLED熄屏功能-1分钟后自动熄屏

- 熄屏后按任意键即可回到熄屏前的屏幕

- 优化了IP地址的显示，没有连接是显示127.0.0.1

## 安装

- 替换 /Software/Python/bakebit_nanohat_oled.py

```
$ su root
# 使用root账户
$ sudo pkill -f bakebit_nanohat_oled.py
# 终止进程
$ cd NanoHatOLED
# 定向至NanoHatOLED目录下
$ rm -rf BakeBit
# 删除目录下的所有文件
$ git clone https://github.com/Peter-Zhifei/BakeBit.git
# 把我的克隆下来
# 网不好的可以 $ git clone https://gitee.com/peter-zhifei/BakeBit.git
$ cd BakeBit/Software/Python/
# 定向
$ sudo python bakebit_nanohat_oled.py &
# 启动&后台运行
$ sudo reboot
# 重启
```

## 错误反馈

请在issue提交

## 开源许可

依旧遵循MIT开源许可，不作商用

# 原来的README

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
