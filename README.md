# Quasar-67 | kbd67 replacement:

A Lumberjack-like ortho keyboard for the kbd67-lite and possibly **further 65%** keyboards.
by Bonk, ScatteredDrifter.

The used license for this project :: [Cern Open Hardware](/LICENSE)

Measurements of Pcb and Plate cutouts were taken from Elmo's [Drop-In replacement board](https://github.com/kb-elmo/67mk_E)


---

## Current Status
**Revision V² is currently planned** and will fix most issues present in V¹.

- Revision V¹: pcbs prototyped and validated working well
  - fit into kbd67-lite case 
  - front-leds were working 
  - encoders and breakout for Cirque Trackpoint untested 
  - laser-cut blocker were able to mount, however had some lightbleeding 
  - further layout options are missing 
- Revision V²: pcb in review, will likely be ordered in **november 2023**
  - will feature breakouts for the unified daughterboard 
  - usb-port can be cut of to fit other cases --> ought to be tested tho 
  - moved leds further down to compensate for lightbleed (hopefully)

---

## Quasar-67: 
A quasar defines the center of a galaxy that emits a bright  light, creating the mirage that it is a larg star. However they are actually black holes which _emit_ light, due to th massive amount of amtter that sourrounds their event horizon, which they consume constantly. 
Being heavily inspired by the lumberjack [find it here](https://github.com/peej/lumberjack-keyboard) this keyboard aims to fit within the affordable kbd67-lite while getting rid of the present 65% keyboard it is.

With the **second revision** it should also be fine to be used with a **unified daughterboard**. 
Further this revision aims to add compatibility to (almost) any _default_ 65% keyboard. 


### Features: 
- RP2040 
- USB-C connector (or daughterboard with V²)
- pcb outlines that match the kbd67-lite 
- base layout is **basekit compatible**
- **5x6** cluster for both left and right side or optionally **5x5**
- VIAL / QMK support 


#### Layout: 

![Image displaying all available layouts of Rev²](/images/quasar_layout_options.png)

---

## Build-Guide: 

### Requirements:
Building Quasar yourself requires the following:
- suitable case (kbd67 or other)
  - optionally daughterboard 
- pcb 
  - if not soldered already: **6x WS28B leds** to solder onto the pcb 
- **further information needed** X m3 screws to mount the blocker 
- the correct plate from [here](/plate/)
- the correct blocker from [here](/plate/)
- everything else to build a keyboard ( keycaps, switches, stabs ...)
  - **optionally** 2 encoders
  - **optionally** a cirque trackpad (**untested**)

### Instructions:
Not yet done, once we have the new parts, we will make a detailed instruction-set

---
### Images:
Once we have **Revision V²** in person, we will update these images. 


**Images** taken from KiCad:

![image of pcb front](images/pcb_front.jpg)
![image of pcb back](images/pcb_back.jpg)
