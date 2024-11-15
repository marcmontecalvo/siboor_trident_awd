# Siboor Trident AWD June 2024 Mods

| Emoji | Description         |
| ----- | ------------------- |
| 💯     | Highly recomended   |
| 👍     | Nice to have        |
| 🤷‍♂️     | Could go either way |
| 👎     | Not recomended      |
| ❓     | Unknown             |
| ✔     | Yes                 |
| ❌     | No                  |

## Hardware Mods
### Flip Rear Motors Downwards
| Extra Parts: ❌ | Recommended: 💯 |
| -------------- | -------------- |

Helps with wiring and gives additional space for other mods.
- [ ] Install the motors upside-down from what is shown in the manual.
- [ ] **Invert** the motor step direction for x1 and y1

### Remove Cable Chain
| Extra Parts: ✔ | Recommended: 💯 |
| -------------- | -------------- |

Vastly improves input shaper graphs and allows for greater accelerations. In place of the cable change I used PG7 cable glands on both ends of the CAN bus cable.
  - [ ] [Bowden PTFE Tube Guide Arm and Can Bus Cable Support](https://www.printables.com/model/978123-voron-bowden-ptfe-tube-guide-arm-and-canbus-cable)
  - [ ] [SB2240 PG7 USB Strain Relief](https://www.printables.com/model/676208-sb2209-sb2240-pg7cnlinko-usb-strain-relief)
  - [ ] [2040 Bracket PG7 Mount](https://www.printables.com/model/1000097-2040-bracket-pg7-mount)

### Disco On A Stick
| Extra Parts: ✔ | Recommended: 💯 |
| -------------- | -------------- |

Huge quality of life improvement to have built in lights that provide plenty of light on the build plate.
- [ ] [Daylight on a Stick](https://github.com/VoronDesign/Voron-Hardware/tree/master/Daylight)
	- There are various retailers that sell premade versions. You ideally want 1 for each side and optionally 1 for the front. 
- [ ] [Mounting Brackets and Diffusers](https://www.printables.com/model/795364-voron-discodaylight-on-a-stick-led-mount-tray-with)


### Panel Clips
| Extra Parts: ✔ | Recommended: 💯 |
| -------------- | -------------- |

#### Filament Latch
These are an improvement over the standard Voron panel clips but can be a bit brittle with their filament hinges. The actual force applied to the panel does not relay on the filament however.
- [ ] [Filament Latch](https://www.printables.com/model/172368-voron-24-filament-latch-or-any-2020-extrusion)
	- Kit comes with 3mm panel and 3mm foam tape. Print a few test sizes before committing to a full set but the size I ended up on were 5.5mm


### Nozzle Brush
| Extra Parts: ✔ | Recommended: 👍 |
| -------------- | -------------- |

On paper a nozzle brush seems like a great idea however after installing one it seemed to make everything worse. This is likely due to me not using it right but I didn't want to spend any more time on trying to make it work after trying out the line purge from [KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging/tree/main). 
- [ ] Bambu Lab A1 Silicon Brush
- [ ] [Nozzle Scrubber & Decontaminator](https://www.printables.com/model/796563-nozzle-scrubber-decontaminator-for-voron-24-using)
- [ ] [Nozzle Scrubber Arm Extension](https://www.printables.com/model/298565-nozzle-scrubber-arm-extension-voron-trident)


### Archetype Breakneck Toolhead
| Extra Parts: ✔ | Recommended: ❓ |
| -------------- | -------------- |

Printing this now (Fiberon PPS-CF) - will report back once I have it installed and fully tested.

### Top Hat with CPAP mount and umbilical / PTFE access
| Extra Parts: ✔ | Recommended: 👍 |
| -------------- | -------------- |

Needed if you want umbilical and cpap and a stealthmax.

### Nevermore Stealthmax with UV light and other mods
| Extra Parts: ✔ | Recommended: 👍 |
| -------------- | -------------- |

Clean air is good.

## Possible ToDo Mods:

### Add 2040 Corner Brackets
| Extra Parts: ✔ | Recommended: ❓ |
| -------------- | -------------- |

Simple addition that improves frame rigidity.
- [ ] 16x 2040 Brackets
- [ ] m4x10mm BHSC
- [ ] m4 roll-in 2020 nuts

## Software Changes

### Additional Plugins
- [ ] [Motors Sync](https://github.com/MRX8024/motors-sync/blob/main/wiki/EN.md)
	- This plug-in is ran prior to every print to get the motors synced as close as possible.
- [ ] [Survey Touch](https://docs.cartographer3d.com/cartographer-probe/survey-touch)
- [ ] [TMC Auto-tune](https://github.com/andrewmcgr/klipper_tmc_autotune)
- [ ] [LED Effects](https://github.com/julianschill/klipper-led_effect)


# Other useful links
- [ ] [Siboor Docs](https://docs.siboor.com/siboor-trident-june)
- [ ] [Siboor github](https://github.com/Lzhikai/SIBOOR-Voron-Trident-June)
- [ ] [Esoterical - Canbus / Flashing MCU and EBB guide](https://canbus.esoterical.online/Getting_Started.html)
- [ ] [Klipper install script](https://github.com/dw-0/kiauh)
- [ ] [SB LED stuff - used as a base for what I have now](https://github.com/VoronDesign/Voron-Stealthburner/blob/main/Firmware/stealthburner_leds.cfg)
- [ ] [KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging/tree/main)