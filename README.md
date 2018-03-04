# sh-f103-network-bootloader
It's an attempt to make bootloader for STM32F103C8 board (blue pill?). It should check for and get new version from local TFTP.

It's work in progress!!! Don't use in critical projects.

## specs
STM32 board is from ebay (around $3).
w5500 board is from ebay (around $8).
Programing with Visual Studio + [VisualGDB](https://visualgdb.com/)

## lib
Project uses wiznet [IOlib](https://github.com/Wiznet/ioLibrary_Driver) 