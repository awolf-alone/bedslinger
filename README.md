# bedslinger
Ender 3 V2 with mods

In late 2021 I purchased an Ender 3 V2 as a first 3D printer. Within a month, it was being modified as I discovered a new world. This repo will record what I have done with my machine.

I never set out with a distinct plan. I modded as I went based on what I discovered. Some choices were misguided or not well thought through. It is hard to make judgments on what to do based on peer experience. All-in-all, this has been a learning experience, and is ongoing. There is a lot one can do with a basic Ender 3 unit, and the directions to take are many depending on what is desireable to the end user.

For myself, I am interested in quality and speed as target outcomes. As well as trying new things, and learning how different components work. Here is what I have done so far, and plan to do in the future.

Most parts have been sourced via [Aliexpress](https://www.aliexpress.com/) and models via [Thingiverse](https://www.thingiverse.com/).

I will share Klipper config files shortly.

# Current modifications:
- [Haldis Black Knight linear rail kit](https://www.banggood.com/Haldis-3D-Black-Knight-Ender-3-V2-or-Ender-3-Pro-3D-Printer-Upgraded-Timing-Belt-and-Screws-Kit-for-Genuine-with-or-without-Linear-Rail-p-1914748.html) + additional [Y axis MGN12](https://www.aliexpress.com/item/1000007480470.html) on [custom bed mount](https://www.thingiverse.com/thing:4627011)
- [Triangle Labs DDE V6 direct drive](https://www.aliexpress.com/item/4000006762144.html)
- [Klipper](https://www.klipper3d.org/) via [Mainsail](https://docs.mainsail.xyz/) on [Raspberry Pi 3B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)
- PEI magnetic build plate
- [Silicone bed mounts](https://www.aliexpress.com/item/1005001823789355.html)
- [AXDL245 accelerometer](https://www.aliexpress.com/item/32452794842.html)
- [V slot covers](https://www.thingiverse.com/thing:4579489)
- eSun drybox with [hygrometer](https://www.thingiverse.com/thing:4650052)

# Future modifications:
- [Manta MK2](https://www.thingiverse.com/thing:4943125) fan shround ([2x 4010 fan](https://www.aliexpress.com/item/32798634077.html) [1x 3010 fan](https://www.aliexpress.com/item/4000990517858.html)
  - [ADXL345 mount](https://www.thingiverse.com/thing:5029699)
  - [MGN12 carriage mount](https://www.thingiverse.com/thing:5139694)
- [BTT SKR 2.0 mainboard with TMC2209](https://www.aliexpress.com/item/1005002399360105.html)
- [External electronics enclosure](https://www.thingiverse.com/thing:4615105) with the following:
  - [Heatbed mosfet](https://www.aliexpress.com/item/32819689994.html)
  - XL4015 DC-DC converter for Raspberry Pi
- [External PSU enclosure](https://www.thingiverse.com/thing:4123532)
- Rewire entire unit:
  - [UL1332 wire (24AWG, 20AWG, 18AWG)](https://www.aliexpress.com/item/1005001611628766.html)
  - Fused IEC input
  - XT60HF
- Raspberry Pi Camera V1.3 + [mount](https://www.thingiverse.com/thing:4566940)
- Mellow NF Crazy LF
- [Cable chain](https://www.aliexpress.com/item/33000014666.html)
- [2GT idlers](https://www.aliexpress.com/item/32726309946.html) for belt tensioners
- [Second Z motor and lead screw](https://www.aliexpress.com/item/1005003150599924.html)
- [POM nut anti-backlash nuts](https://www.aliexpress.com/item/1005001623816690.html)
- [Belted dual Z axis](https://github.com/kevinakasam/BeltDrivenEnder3)
- XL4016 DC-DC converter for Raspberry Pi
