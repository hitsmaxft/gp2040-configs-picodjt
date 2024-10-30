# GP2040 Configuration for Raspberry Pi Pico

gp2040-configs-picodjt

![Pin Mapping](assets/PinMapping.png)

Basic pin setup for a stock Raspberry Pi Pico. Combine with a simple GPIO breakout/screw terminal board for an easy DIY arcade stick.


## building


```shell


GP2040_BOARDCONFIG=PicoDJT cmake ./build

cd build
make

```
