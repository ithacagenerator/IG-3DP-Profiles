
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
  - [RailCore 300 ZL](#railcore) <br>
    - [RailCore Usage](https://ithacagenerator.github.io/IG-3DP-Profiles/railcore/) <br>
  - [Xinkebot *Jon Sanders Edition*](#xinkebot) <br>
    - [Xinkebot Usage](https://ithacagenerator.github.io/IG-3DP-Profiles/xinkebot/)<br>
  - [Prusa i3 MK2.5S](#prusa) <br>
    - [Prusa Usage](https://ithacagenerator.github.io/IG-3DP-Profiles/prusa/)<br>
  - [Ender 3 Fleet](#ender) <br>
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
└── xinkebot
│   ├── <User>/
│   └── README.md  # IG Xinkebot usage instructions
└── IG_config_bundle.ini # misc. default profiles
```

- - -


<h4 id="hardware"> </h4>  

## 3d Printer Hardware Available @ IG:


<h4 id="railcore"> </h4>  


### RailCore

#### [*Read the IG RailCore Usage instructions here*](/railcore)

While the RailCore can sort of be controlled from its  touchscreen, it is best to interact with the Railcore from the duet web interface.  You may connect to the printer using its mDNS name `railcore.local` or its locally assigned ip address.



|**RailCore II 300 ZL**|[*Project Website*](https://railcore.org/)|
|--|--|
|Controller|[Duet 3d Ecosystem](https://www.duet3d.com/)|
|Firmware|[RepRapFirmware](https://github.com/Duet3D/RepRapFirmware)|
|Hotend|[E3D V6 Ecosystem](https://e3d-online.zendesk.com/hc/en-us/articles/360017139517-V6-Drawings)|
|Usual Nozzle | .4|
|Extruder | Direct Drive, [Bondtech BMG](https://www.bondtech.se/product/bmg-extruder/))|
|Filament Diameter| 1.75, run out sensor|
|Surface Equipment|[PEI](https://reprap.org/wiki/PEI_build_surface), [BLTouch](https://all3dp.com/2/bltouch-sensors-guide/)|
|HID|Duet Web Interface|



- - -


<h4 id="xinkebot"> </h4>  


### Xinkebot *Jon Sanders Edition*

#### [*Read the IG Xinkebot Usage instructions here*](/xinkebot)

While the Xinkebot can kinda be controlled from its  touchscreen, it is best to interact with the Xinkebot from the duet web interface.  You may connect to the printer using its mDNS name `xinkebot.local` or its locally assigned ip address.



|**Xinkebot**| *Jon Sanders Edition* |
|--|--|
|Controller|[Duet 3d Ecosystem](https://www.duet3d.com/)|
|Firmware|[RepRapFirmware](https://github.com/Duet3D/RepRapFirmware)|
|Hotend|[E3D Volcano Ecosystem](https://e3d-online.zendesk.com/hc/en-us/articles/360017243818-Volcano-Drawings)|
|Usual Nozzle | .8|
|Extruder |Quick release DB25, Direct Drive, [Bondtech BMG](https://www.bondtech.se/product/bmg-extruder/))|
|Filament Diameter| 1.75, run out sensor|
|Surface Equipment|[Borosilicate](https://reprap.org/wiki/PCB_Heatbed/Aluminium_Bed_Mount_Plate/Borosilicate_glass#Borosilicate_glass), [BLTouch](https://all3dp.com/2/bltouch-sensors-guide/)|
|HID|Duet Web Interface|



- - -


<h4 id="prusa"> </h4>  


### Prusa i3 MK2.5S  

#### [*Read the IG Prusa Usage instructions here*](/prusa)

This is a legit Josef Průša printer running the OEM Marlin [1.x fork, Prusa Firmware](https://github.com/prusa3d/Prusa-Firmware).  Interact with this printer via an SD card and the clicky button Marlin graphical display.


<h4 id="prusa-overview"> </h4>  


|**Prusa i3**|  |
|--|--|
|Controller|[mini Rambo](https://reprap.org/wiki/MiniRambo)|
|Firmware|[Prusa's Marlin 1.x fork](https://github.com/prusa3d/Prusa-Firmware)|
|Hotend|Stock|
|Usual Nozzle | .4|
|Extruder |Stock, Direct Drive|
|Filament Diameter| 1.75|
|Surface Equipment|[Spring Steel PEI](https://shop.prusa3d.com/en/accessories-mk3s-mk25s-mini/1013-mini-spring-steel-sheet-with-smooth-double-sided-pei.html), [SuperPINDA](https://shop.prusa3d.com/en/spare-parts/1396-superpinda.html)|
|HID|Marlin Graphical Interface|


- - -


<h4 id="ender"> </h4>  


#### Creality Ender 3 Fleet

Ithaca Generator has a fleet of three [Creality Ender 3](https://www.creality3dofficial.com/products/official-creality-ender-3-3d-printer) printers.  These are easy to use and thoughtfully maintained machines used for teaching, training and can be rented out for extended use.  These Enders run the original Creality Marlin fork.  Interact with these  printers via a Micro SD card and the clicky button Marlin graphical display.


|**Ender 3**| [Website](https://www.creality3dofficial.com/products/official-creality-ender-3-3d-printer) |
|--|--|
|Usual Nozzle | .4|
|Extruder |Bowden|
|Filament Diameter| 1.75|
|HID|Marlin Graphical Interface|
