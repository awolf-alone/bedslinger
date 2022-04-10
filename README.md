# bedslinger
Ender 3 V2 with mods

In late 2021 I purchased an Ender 3 V2 as a first 3D printer. Within a month, it was being modified as I discovered a new world. This repo will record what I have done with my machine.

I never set out with a distinct plan. I modded as I went based on what I discovered. Some choices were misguided or not well thought through. It is hard to make judgments on what to do based on peer experience. All-in-all, this has been a learning experience, and is ongoing. There is a lot one can do with a basic Ender 3 unit, and the directions to take are many depending on what is desireable to the end user.

For myself, I am interested in quality and speed as target outcomes. As well as trying new things, and learning how different components work. Here is what I have done so far, and plan to do in the future.

Most parts have been sourced via [Aliexpress](https://www.aliexpress.com/) and models via [Thingiverse](https://www.thingiverse.com/).

I will share Klipper config files shortly.

# Current modifications:
- [SuperSlicer](https://github.com/supermerill/SuperSlicer)
- [Haldis Black Knight linear rail kit](https://www.banggood.com/Haldis-3D-Black-Knight-Ender-3-V2-or-Ender-3-Pro-3D-Printer-Upgraded-Timing-Belt-and-Screws-Kit-for-Genuine-with-or-without-Linear-Rail-p-1914748.html) + additional [Y axis MGN12](https://www.aliexpress.com/item/1000007480470.html)(https://www.thingiverse.com/thing:4627011)
- Y axis conversion/mounts from the [Ender Switchwire conversion project](https://github.com/boubounokefalos/Ender_SW)
- ~~[Triangle Labs DDE V6 direct drive](https://www.aliexpress.com/item/4000006762144.html)~~
- Pheatus Dragon SF hotend
- LDO Sherpa Mini extruder with LDO-36STH17-1004AH(G8T) 
- Modified Satsana mini duct - based on [this design](https://www.thingiverse.com/thing:5170276) which I modified to use thread inserts and adjust Sherpa Mini mounting location as the original design was too narrow
- [Klipper](https://www.klipper3d.org/) via [Mainsail](https://docs.mainsail.xyz/) on [Raspberry Pi 3B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)
- [BTT SKR 2.0 mainboard with TMC2209](https://www.aliexpress.com/item/1005002399360105.html)
- PEI magnetic build plate and G10 build plate
- [Silicone bed mounts](https://www.aliexpress.com/item/1005001823789355.html)
- [AXDL245 accelerometer](https://www.aliexpress.com/item/32452794842.html)
- [V slot covers](https://www.thingiverse.com/thing:4579489)
- eSun drybox with [hygrometer](https://www.thingiverse.com/thing:4650052)
- [2GT idlers](https://www.aliexpress.com/item/32726309946.html) for belt tensioners
- [Second Z motor and lead screw](https://www.aliexpress.com/item/1005003150599924.html)
- [POM nut anti-backlash nuts](https://www.aliexpress.com/item/1005001623816690.html)
- Raspberry Pi Camera V1.3 + [mount](https://www.thingiverse.com/thing:4566940)
- [External electronics enclosure](https://www.thingiverse.com/thing:4615105) with the following:
  - [Heatbed mosfet](https://www.aliexpress.com/item/32819689994.html)
  - Fused IEC input
  - XT60HF
  - [PCB mounts](https://www.thingiverse.com/thing:2083883)
- [External PSU enclosure](https://www.thingiverse.com/thing:4123532) 
# Future modifications:
  - XL4015 or XL4016 DC-DC converter for Raspberry Pi
- Rewire entire unit:
  - [UL1332 wire (24AWG, 20AWG, 18AWG)](https://www.aliexpress.com/item/1005001611628766.html)
- Mellow NF Crazy
- [Cable chain](https://www.aliexpress.com/item/33000014666.html)
- [Belt driven dual Z axis](https://github.com/kevinakasam/BeltDrivenEnder3)
- [KlackEnder ABL probe mod](https://github.com/kevinakasam/KlackEnder-Probe)

# Things I've tried and do not recommend:
- Squash ball feet
  - These are often recommended in Ender groups as a way to reduce noise of the printer. This may be so, but it negatively effects the resonance of the machine. I have     since removed these and advise placing your machine on a solid flat surface (currently using a thick foam tile ontop of a wooden table).
- Noctura fans
  - These are often recommended in Ender groups as a way to reduce noise of the printer. This may be so, but are not ideal for air flow on the hotend, even with custom     mounts. It is far easier to use a good 24V fan and remove the need for a DC-DC (buck) converter. If noise is a major problem, then perhaps this mod is for you. But     for propper cooling, do not use. For cooling other components such as the mainboard these would be sufficient.
- Haldis Black Knight linear rail kit
  - I have this installed and will keep it given it is quite expensive. I do think it is a nicely built kit, but if I had my time over, I would source the rails myself     and print the required mounts. I would seriously consider either a full [Switchwire conversion](https://github.com/boubounokefalos/Ender_SW) or [Belt driven Ender](https://github.com/kevinakasam/BeltDrivenEnder3) with rail modification.
- Stock Ender 3 V2 glass build plate
  - This is a nice surface to print on. However, it adds a lot of weight to the Y axis which negatively effects resonance of the machine. The bed slinging aspect of      these i3 style machines is one of the reasons they are falling out of favour for many 3D printing ethusiasts. To get the best from these machines, minimal weight is    ideal. Go with a PEI or G10 sheet instead.
