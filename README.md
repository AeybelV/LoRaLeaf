# LoRaLeaf

LoRaLeaf is a compact, open-source LoRa module built around the STM32WLE5, which is STMicroelectronics’ all-in-one MCU + LoRa radio SoC.
LoRaLeaf is a Open Hardware design that aims to make LoRa integration easy and accessible for makers, engineers, and researchers.

The board is a castellated-edge module that can be dropped directly into your PCB design, just like a QFN package or Wi-Fi module.
It provides a fully functional LoRa transceiver and MCU subsystem in a small form factor, making it perfect for compact or power-constrained applications.

## Features

- *MCU:* STM32WLE5xx (ARM Cortex-M4 + integrated LoRa radio)
- *Frequency Band:* US915 MHz at up to +22dBm (sorry non-Americans, 🇺🇸 🇺🇸 🦅 🦅)
- *Antenna Options:* (depending on board variant) 
  - u.FL connector
  - Spring Antenna (WIP)
  - PCB Antenna (Maybe in the future?)
- *Open Source:* Hardware, schematics, and layout released under a permissive open hardware license

## Fabrication

LoRaLeaf is a 4-layer PCB which emphasizes small for factor but also manafacturability. The board can be manafactured
at JLCPCB and the component selection is such that PCBA shouldn't be too expensive. The component selection is also such
that the board can also be hand assembled by a **skilled** hand and some reflow/hot air.

## Tuning

To accomodate the variety of antennas, there is a Pi-filter network for antenna load matching.

## Reference Firmware

I plan to write some reference firmware based around the AT command set for those who desire just LoRa comms.

# License

Copyright © 2025 Aeybel Varghese

LoraLeaf is open source and released under the CERN Open Hardware Licence Version 2
Contributions, bug reports, and feature requests are welcome.

See the [LICENSE](LICENSE) file for full details.
