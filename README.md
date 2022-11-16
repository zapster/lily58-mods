# Lily58 Mods
Modifications and enhancements for the Lily58 keyboard.

This is currently work in progress.

## Firmware
QMK with the `zapster` keymap for the Lily58 keyboard: https://github.com/zapster/qmk_firmware

## USB C Interconnect

Replace the TRRS connection with an USB C receptacle to avoid short curcuits.
The idea is to create a PCB that can be soldered to the TRRS jacks footprint.
Since the USB C is non-standard and might be confused with the USB jacks on the MCU,
the interconnect will likely use a magnetic USB C cable.

Go to [Lily58_Pro_USB_C_Reset_Ext](./Lily58_Pro_USB_C_Reset_Ext/)

### Part Evaluation:
* USB C recaptacle: USB4110-GF-A
* Magnetic USB C cable: https://www.amazon.de/gp/product/B0B76D7L5Q/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&th=1
  * need to check number of wires and connectivity


## Palm Rest

Add a palm rest and potentially 3d print a case that supports it, also wrt. tenting.

### Parts

* first try: [Kensington K52802WW](https://www.kensington.com/p/products/ergonomic-desk-accessories/ergosoft-wrist-rest/kensington-ergosoft-wrist-rest-for-standard-mouse/)
  * not comfortable
* currently testing: non-name "Powcan Memory Foam" https://www.amazon.de/gp/product/B07JGDDCJM/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1
  * until now, rather nice 
