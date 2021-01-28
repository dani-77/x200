# x200 Coreboot and Libreboot rom's.
The ukqwerty_newmac_x200.rom and x200_8mb_ukqwerty_vesafb.rom are Libreboot roms.

The x200m4rc0.rom is a Coreboot rom.

With coreboot or libreboot already flashed, flash using:

sudo flashrom -p internal -w nameofthe.rom -V


With stock bios, you should use an external flasher (Rpi, BBB or 
another). Find instructions at coreboot.org or libreboot.org or 
retroboot.org.

