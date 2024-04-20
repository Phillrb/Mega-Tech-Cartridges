# Mega-Tech-Cartridges
DIY Sega Mega-Tech game cart designs based on reverse engineering of the original 171-5782/171-5783 cartridges.

## 171-5782 - Mega Drive

This is the original cart for MD based games with a single 4 Megabit ROM.

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5782%20-%20Mega%20Drive/171-5782_front.png" width="500">

### 171-5782 Repro
* 1:1 reverse engineered copy to the original.
* No jumper settings needed for use.
* Only supports 40-pin ROMs.

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5782%20-%20Mega%20Drive/171-5782_Repro/171-5782_Repro_3D.png" width="500">

### 171-5782 Redux
* Removed unused jumpers / capacitors.
* Add 8-32Meg 42-pin EPROM support by jumpers.
* Add 1mm edge connector length for shells with low tolerances.
* Add JLCPCB silkscreen for "Remove Order Number - Specify a location"

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5782%20-%20Mega%20Drive/171-5782_Redux/171-5782_Redux_3D.png" width="500">

## 171-5783 - Master System
This is the original cart for SMS based games with a single 1 or 2 Megabit ROM.

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5783%20-%20Master%20System/171-5783_front.png" width="500">

### 171-5783 Repro
* 1:1 reverse engineered copy to the original.
* Needs JP1 bridged for 1 Megabit ROMs.
* Needs GND knot on IC1 drilled out as is done on original carts.

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5783%20-%20Master%20System/171-5783_Repro/171-5783_Repro_3D.png" width="500">

### 171-5783 Redux
* Removed unused jumpers / capacitors.
* Removed GND knot.
* Add 1mm edge connector length for shells with low tolerances.
* Add JLCPCB silkscreen for "Remove Order Number - Specify a location"

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/9d65a29b1b896c6a0aec2a9f6fe7d80724a76bec/171-5783%20-%20Master%20System/171-5783_Redux/171-5783_Redux_3D.png" width="500">

## Mega-Tech - Mega Drive Converter

This allows original Sega Mega Drive carts to be played on your Mega-Tech.

<img src="https://github.com/mourix/Mega-Tech-Cartridges/blob/07a9f1c8c08252d68696b7d9c46cd9a38ecbab17/Mega-Tech%20-%20Mega%20Drive%20Converter/MT_MD_Converter_front.png" width="500">

## Manufacturing Notes
The gerber zip files in each project folder can be uploaded directly to most suppliers.
### JLCPCB
* PCB specifications: standard 2 layer PCB, 1.6mm thickness. Select "Gold Fingers" and "30°finger chamfered".
* Redux/Converter PCBs: select "Remove Order Number - Specify a location".
