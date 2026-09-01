# Atlona AT-UHD-CLSO-601 Firmware Dump
This is a flash dump of the AT-UHD-CLSO-601 (Rev C) HDMI switch's flash ICs.
These can be used to recover from a failed firmware update, which would normally leave the device non functional, flashing an LED on the front panel and unresponsive via every method
The only Flash IC not included is the Microchip 25LC04AI, which is normally blanked (All 0xF) and used to store custom EDIDs.

## Larger board
- **Winbond_25Q32FVSIG_1**: U#, located near 
- **Winbond_25Q32FVSIG_2**: U#, located near 
- **Winbond_25Q80DVSIG**: U55, on the bottom of the board located near the ethernet jack

## Smaller board
- **Winbond_25Q32FVSIG_3**: U24, located near the large CSK IC
- **AMIC_A25L040AO-F**: U11, located near the Altera FPGA near the edge of the board
