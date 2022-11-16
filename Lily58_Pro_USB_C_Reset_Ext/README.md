# Lily58 USB C Interconnect and Side-Reset Extension

Small extension board that adds an USB C jack for connecting the two keyboard sides
and a side-facing reset button.
The extension board is soldered onto the TRRS jack and reset button pads of the original Lily58 Pro PCB.

Similar to the main Lily58 board, the extension PCB is reversible,
so the same board can be used for the right and left side of the keyboard.

## Revision ExtUR0

The ExtUR0 revision of the PCB as been sent to the fab on 2022-11-15.

### Rendering

#### Front/Right Side
![Front!](/Lily58_Pro_USB_C_Reset_Ext/revisions/ExtUR0/front.png "Front aka Right Hand Side")

#### Back/Left Side
![Back!](/Lily58_Pro_USB_C_Reset_Ext/revisions/ExtUR0/back.png "Back aka Left Hand Side")

### Holes

| Component | Hole | Pad |
| ----------| ---- | --- |
| TRRS jack | 0.5mm x 1.6mm |1.2mm x 2.1mm|
| R1, R2, P1, P2 | 32mil (0.8128mm) | 55mil (1.3970mm) |
| Reset button | 1.3mm | 2.5mm |

### Bill of Material

| Qty | Part          | Description       | Comment |
| --- | ------------- | ----------------  | --- |
|   2 | TL3330AF130QG | Side-reset button | |
|   2 | USB4110-GF-A  | USB C receptacle  | |
|   4 | 3121-2-00-15-00-00-08-0 | Mill Max pin | TRRS |
|   2 | 3136-1-00-15-00-00-08-0 | Mill Max pin | Reset Button |

### Known Issues

* The part names and the name silk screens are face the other direction. Since the parts are inherited from the Lily58 PCB, the name should be flipped.
* All holes that connect to the Lily58 Pro PCB should probably use the same size for simplicity.
