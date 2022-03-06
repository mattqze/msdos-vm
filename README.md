# msdos-vm
A preconfigured and preinstalled with MSDOS 6.22, Windows 95 and games.
# To use:
Download ZIP. <br>
Extract the ZIP file. <br>
Open Command Prompt, or, (recommended) [CMDER](cmder.net) <br>
cd into the folder you just extracted. <br>
Paste this into CMDER, or Command Prompt:
qemu-system-i386 -hda MSDOS.img -boot c -cpu pentium2 -m 128 -monitor stdio
