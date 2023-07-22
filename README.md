# PS3-Drive-Tool
Tool to help manage PS3 Hard drive 

After Much work of nearly 70 Hours I have created my first script with the help from chatGPT and am looking for feedback. Another option to Mount/Unmount and decrypt PS3 Hard drive of FAT-NAND without otherOS . (though this can be modified to include other models) Made to compliment @Berion Scripts. (https://www.psx-place.com/resources/ps3-hdd-decryption-helper.1293/updates)

Still needs compiled UFS and BSWAP16 (for now) until more testing is done by larger audience.
Place script anywhere, give permission to run as executable, run initial configuration. Enjoy.


This tool will:

*check if needed modules are installed in kernel or loaded and if not loaded will load them from configuration path.

*auto-unmount upon second run of script.


Notes: This is tested using Linux Mint 21 and should work on most Linux Mint or Ubuntu machines. UFS & Bswap16 are not included.
*include ata_key.bin in ATA key path.
*include full modules name and .ko extension in Initial setup.
*creates .config in whatever directory script is in.
**for some reason there is are instances of file manager open selecting read-write I cannot figure out how to suppress the lower level instance. It's mostly just an annoyance. (if anyone knows how to fix let me know)
