# Arduino GC9A01 Display Driver Demo

Simple sketch using the GC9A01 LCD display driver with a 240x240 round display to show some test patterns in 18-bit color mode over SPI. This is deliberately simple and unoptimised example code.

![](demo.gif)

### Pinout

| GC9A01 | Arduino |
|:------:|:-------:|
| SCL | SCK |
| SDA | MOSI |
| RES | 8 |
| DC | 9 |
| CS | 10 |

### Useful documentation

[Breakout Board](https://www.buydisplay.com/1-28-inch-tft-ips-lcd-display-module-240x240-spi-for-arduino-raspberry-pi) - [GC9A01 Datasheet](https://www.buydisplay.com/download/ic/GC9A01A.pdf) - [STC12C5A driver](https://forum.arduino.cc/index.php?action=dlattach;topic=690899.0;attach=368944)
