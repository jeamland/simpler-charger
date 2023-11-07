# A "Simpler"[^1] Charger

This is a two-port USB charger design based around the [Texas Instruments TPS25858-Q1](https://www.ti.com/product/TPS25858-Q1) controller. It's designed to be part of a larger project to build some charging infrastructure into a shelf, hence the terminal block connections rather than actual USB-C ports. Input power is intended to be 15V coming from a power brick and the intent is to have several of these providing something like 12 ports in total (so 6 completed boards).

A lot of the layout and component selection was "inspired" by [TI's Evaluation Kit](https://www.ti.com/tool/TPS25858Q1EVM-140) for this device, but I have deviated in a few places, mainly for cost reasons. I hopethink I've validated that these changes are ok.

Full KiCad files, including custom symbols and footprints, are in here along with datasheets, PDF versions of the schematic and PCB layout, and the bill of materials.

[^1]: The original design I made did the full USB-C thing up to 60W and required an actual microcontroller. I may still make that one but, well, I figured I should overcomplicate things in stages.