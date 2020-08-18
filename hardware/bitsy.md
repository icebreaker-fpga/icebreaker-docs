---
layout: default
title: iCEBreaker Bitsy
parent: Hardware
nav_order: 2
---

# iCEBreaker Bitsy

[Available at 1BitSquared](//1bitsquared.com/collections/fpga/products/icebreaker-bitsy){: .btn}

iCEBreaker Bitsy is the smaller but just-as-capable sibling to iCEBreaker. At just 1.4x0.7in, it is compatible with the Teensy form-factor and can be easily embedded into any project.

![iCEBreaker](/assets/img/icebreaker-bitsy/bitsy_v1.0a.jpg)
  
* iCE40UP5K in QFN48 (SG48) package
  * PLL, two SPI and two I2C hard IPs
* 128M (16MiB) DDR- and QPI-capable Flash Memory
* 64M (8MiB) QPI-capable Pseudo-SRAM
* USB-C interface (comes preloaded with a [RISC-V soft USB bootloader](//github.com/smunaut/ice40-playground/tree/master/projects/boot_stub))
* RGB LED connected to 3x 24mA hard PWM IP pins
* Two user LEDs (one shared with RAM-CS)
* Status LED for CDONE
* 12MHz external clock (on PLL GBIN)
* One user button
* Supply rails: 3.3V and 1.2V
* FPGA SPI/programming header
  * 4 pins for config (SDI, SDO, SCK, CS)
  * 2 extra GPIO pins for QSPI
  * CDONE, CRESET, 3.3V, and GND
* Teensy form-factor compatible
* Compatible with Feather ecosystem using a [Teensy 3.x Feather Adapter](//adafruit.com/product/3200)
* Castellated edges and single-side-load for easy module integration

![iCEBreaker-bitsy info card top](/assets/img/icebreaker-bitsy/info-card-top.svg)
![iCEBreaker-bitsy info card bottom](/assets/img/icebreaker-bitsy/info-card-bot.svg)
