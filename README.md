
<table>
 <thead>
  <tr>
   <th><a href="https://github.com/ithacagenerator/IG-3DP-Profiles">Repository</a></th>
   <th><a href="https://ithacagenerator.github.io/IG-3DP-Profiles/" rel="nofollow">Pages</a></th>
  </tr>
 </thead>
</table>

*Profiles, hardware and notes*



[![](https://avatars.githubusercontent.com/u/3699732?s=200&v=4)](https://ithacagenerator.org/)


The goal of this repo is to aggregate slicer profiles, resources and hardware / firmware notes pertinent to 3d printing at the Ithaca Generator.  Pull requests are welcome and encouraged!  


- [**Hardware**](#hardware) <br>
  - [IG RailCore](#railcore) <br>
    - [RailCore Usage](https://ithacagenerator.github.io/IG-3DP-Profiles/railcore/) <br>
  - [IG Prusa](#prusa) <br>
    - [Prusa Usage](https://ithacagenerator.github.io/IG-3DP-Profiles/prusa/)<br>
  - [IG Ender 3 Fleet](#ender) <br>
- **Slicer Links** <br>
  - [PrusaSlicer](https://www.prusa3d.com/drivers/) (Linux AppImage, Mac, Windows) <br>
  - [PrusaSlicer Source](https://github.com/prusa3d/PrusaSlicer) <br>
  - [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura) (Linux AppImage, Mac, Windows) <br>


- - -  

All default IG PrusaSlicer printers & profiles found on the 3d printing laptop in the makerspace can be imported from the `./IG_config_bundle.ini` file.  

```
├── ...
├── prusa
│   ├── <User>/
│   └── README.md  # IG Prusa usage instructions  
├── railcore
│   ├── <User>/
│   └── README.md  # IG RailCore usage instructions  
└── IG_config_bundle.ini # misc. default profiles
```

- - -


<h4 id="hardware"> </h4>  

## 3d Printer Hardware Available @ IG:


<h4 id="railcore"> </h4>  


### RailCore

#### [*Read the IG RailCore usage instructions here*](/railcore)

While the RailCore can sort of be controlled from its  touchscreen, it is best to interact with the Railcore from the duet web interface.  You may connect to the printer at it's locally assigned ip address (use `M552` on the touchsceen to view it's address).  

|**RailCore II**|[*Project Website*](https://railcore.org/)|
|--|--|
|Controller|[Duet 3d Ecosystem](https://www.duet3d.com/)|
|Firmware|[RepRapFirmware](https://github.com/Duet3D/RepRapFirmware)|
|Hotend|[E3D Revo Mini](https://e3d-online.com/blogs/news/rapidchangerevo)|
|Usual Nozzle | .25mm or .4mm|
|Extruder | Direct Drive, [Bondtech LGX](https://www.bondtech.se/product/lgx-lite-extruder-custom/), [36STH20-1004AHG 36mm NEMA 14 Stepper](https://www.printedsolid.com/collections/ldo-motors/products/ldo-nema14-36mm-round-pancake-motor-ldo-36sth20-1004ahgxh)|
|Filament Diameter| 1.75, run out sensor|
|Surface Equipment|G10 FR4 bonded to aluminum, [BLTouch](https://all3dp.com/2/bltouch-sensors-guide/)|
|HID|Duet Web Interface|


- - -


<h4 id="prusa"> </h4>  


### IG Prusa

#### [*Read the IG Prusa Usage instructions here*](/prusa)

This is a heavily modified Josef Průša printer that started life as an i3 MK2.5S.  It currently uses an [Einsy Rambo](https://reprap.org/wiki/EinsyRambo_development) [v1.2](https://ultimachine.com/products/einsy-rambo-1-2?variant=32554065756269) motherboard running [Prusa MK3S Firmware](https://github.com/prusa3d/Prusa-Firmware).  IG's Prusa currently has an E3D Revo Six hotend and .4mm Revo nozzle.  Interact with this printer via an SD card and the clicky button Marlin graphical display.  


<h4 id="prusa-overview"> </h4>  


|**Prusa i3**|  |
|--|--|
|Controller|[Einsy Rambo 1.2](https://reprap.org/wiki/MiniRambo)|
|Firmware|[Prusa Firmware 3.11 MK3S](https://github.com/prusa3d/Prusa-Firmware)|
|Hotend|[E3D Revo Six Ecosystem](https://e3d-online.com/blogs/news/rapidchangerevo)|
|Usual Nozzle | .4mm|
|Extruder |Mostly Stock NEMA 17 Direct Drive|
|Filament Diameter| 1.75|
|Surface Equipment|[Spring Steel PEI](https://shop.prusa3d.com/en/accessories-mk3s-mk25s-mini/1013-mini-spring-steel-sheet-with-smooth-double-sided-pei.html), [Latest SuperPINDA](https://shop.prusa3d.com/en/spare-parts/1396-superpinda.html)|
|HID|Marlin Graphical Interface|


- - -


<h4 id="ender"> </h4>  


#### Creality Ender 3 Fleet

Ithaca Generator has a fleet of three fairly modified [Creality Ender 3](https://www.creality3dofficial.com/products/official-creality-ender-3-3d-printer) printers.  These are easy to use and thoughtfully maintained machines used for teaching, training and can be rented out for extended use.  Most of our Enders run the original Creality Marlin fork.  Interact with these printers via a Micro SD card and the clicky button Marlin graphical display.


|**Ender 3**| [Website](https://www.creality3dofficial.com/products/official-creality-ender-3-3d-printer) |
|--|--|
|Hotend|stock|
|Usual Nozzle | .4|
|Extruder |bowden (dual gear, all aluminum, shortend PTFE path)|
|Filament Diameter| 1.75|
|Surface Equipment|G10 FR4 bonded to aluminum|
|HID|Marlin Graphical Interface|



- - -


<h4 id="xinkebot"> </h4>  


### Xinkebot *Jon Sanders Edition*

#### *Jon Sander's RepRapFirmware Xinkebot is waiting for its next adventure!  It is currently offline.*


|**Xinkebot**| *Jon Sanders Edition* |
|--|--|
|Controller|[Duet 3d Ecosystem](https://www.duet3d.com/)|
|Firmware|[RepRapFirmware](https://github.com/Duet3D/RepRapFirmware)|
|Hotend|[E3D Volcano Ecosystem](https://e3d-online.zendesk.com/hc/en-us/articles/360017243818-Volcano-Drawings)|
|Usual Nozzle | .8|
|Extruder |Quick release DB25, Direct Drive, [Bondtech BMG](https://www.bondtech.se/product/bmg-extruder/))|
|Filament Diameter| 1.75, run out sensor|
|Surface Equipment|G10 FR4 bonded to aluminum, [BLTouch](https://all3dp.com/2/bltouch-sensors-guide/)|
|HID|Duet Web Interface|

