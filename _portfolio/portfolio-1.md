---
title: "Persistence of Vision Display"
excerpt: "*Scrappy rotating LED display built on bare-metal Raspberry Pi... 
and a disassembled Honeywell fan.*<br/><img src='/images/pov2.png' width='400'>"
collection: portfolio
---

![POV](/images/pov.png){: .align-right width="290"}
A spherical persistence of vision (POV) LED Display that works by spinning a circular array of LEDs and relies on the eyes' natural “refresh rates” to create the illusion of a solid, continuous image on a sphere. Equipped with an LED strip, a hall sensor, 3 battery packs and framed in a disassembled desk fan, it creates patterns by reacting to magnets spaced across the circular base.

This was my final project for [CS107E](https://cs107e.github.io/about/), Stanford's intensive systems programming course taught on Raspberry Pi. Although my group was inspired by online resources (namely [this one](https://youtu.be/g7_VKGsEKeA)), we coded every module for the project ourselves in C on Raspberry Pi, including the hall sensor driver, the LED driver, and the timing algorithm.

This project was made possible by my awesome project partners (shoutout Didi and Aanya!), many nights in Stanford's Lab64, and my friend Frances' loaned Honeywell fan. We were on a tight deadline and had to source parts quickly—hence our mangling of the Honeywell fan for its motor-but we were quite satsfied with the final product as we managed to display a soccer ball!

You can view photos, code, and further descriptions of our work on [the project GitHub, hosted on Didi's repository](https://github.com/didikamalova/POV-Display-RaspberryPi). Unfortunately, videos of the project do not compliment the "persistence of vision" effect as camera frame rates are faster than those of our eyes.

<br/>

![POV](/images/hall.png){: .align-center width="300px"}
*Hall sensor that detects changes in the nearby magnetic field to trigger different LED patterns.*
