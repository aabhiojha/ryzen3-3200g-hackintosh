
# Specification

**CPU:** AMD ryzen 3 3200g 

**GPU:** Vega 8 integrated

**Motherboard:** MSI b450 Tomahawk Max

**RAM:** 2*8 GB


## Screenshots

![App Screenshot](https://preview.redd.it/f2phkwoqfrmb1.png?width=1920&format=png&auto=webp&s=d8ba4ddea3258654e2f75be212456ea104609f72)


## BIOS settings

Its crucial part of success. These are recomended settings for running MacOS on regular beige PC. 
#### DO NOT FORGET TO MAKE THESE SETTINGS.

**Disable:**

- fast boot
- com/serial/parallel
- secure boot
- resize bar

**Enable:**

- 4G decoding
- SATA operations to AHCI

# Issues

Nothing! Although you might have to swap out the APPLEALC kext as I am using the unofficial patched version for microphone support. Use official kext instead after you install mac on your machine.


## Installation

Use debug efi to install and don't forget to generate a unique serial id for your machine. 

Refer to this link
https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo
