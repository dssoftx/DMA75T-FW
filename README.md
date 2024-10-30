# DMA75T-FW
Firwmare for the Artix 7 75T Based DMAs. Blackmagic Design DeckLink Mini Monitor HD-based.


# FLASHING

Install the CH347 FLASH Utility and install the CH341 driver package
Open the tool, set to BIN and flash, its ok if it seemingly gets stuck at Sector 35, just wait till it completes flashing with the chinese message flashing has been completed preceded by bin and something in chinese.

SuperIO FIFO Bridge drivers get installed by windows automatically and are wrong. Pcileech wont ever discover the DMA because of the FWTI driver. Install WinUSB with Zadig and then UNINSTALL the driver and attempt to remove device driver software too. then you should be able to do pcileech probe.

# FW IS UNTESTED BUT WORKS 

Use at own risk...
