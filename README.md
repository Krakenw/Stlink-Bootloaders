The 2 protected files were extracted from an ebay clone stlink and a nucleo pcb.
The 2 Unprotected files are the protected files with the call to the flash protection 
routine nop'd out at addresses 0x21B2 for V2.0 & 0x2A44 for V2.1

The Unprotected-2-0-Short-Bootloader.bin file "appears" to be either the "true" bootloader
file or at least "closer" to it's real size. This file does not "appear" to contain any 
any information about any previous runtime software, and when a completely erased device 
is loaded with this "Short" bin file, the STLinkUpgrade.jar will offer you a comprehensive
choice of software that you load into your device.

