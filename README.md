# Saitek X52 driver v6.5

This fork from XHOTAS driver has some important differences:
- Only Saitek X52 joysticks (no pro) are supported.
- Most parts of the drivers now use WDF.
- The Windows service and the keyboard/mouse filters are not required. All work is done under the virtual minidriver.
