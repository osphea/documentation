# set up your dahlia iso

## linux-builds

most of the work has been done on the [grub builds](https://github.com/HexaOneOfficial/dahliaos)

**Dahlia OS** has support for booting on 32 bit uefi. more info can be found [here](https://github.com/HexaOneOfficial/documentation/blob/master/hardware/Modecom/Freetab/8025/32_uefi.md)

**Dahlia OS** has support for freetab 8025 touchscreen. more info can be found [here](https:)

### 32 bit uefi

**how can dahlia grub boot on 32 uefi**

[dahlia grub](https://github.com/HexaOneOfficial/dahliaos) has a file called [bootia32.efi](https://github.com/HexaOneOfficial/dahliaos/blob/master/BOOT/bootia32.efi) stored in /EFI/boot/ this allows the system to a boot 64 bit iso.

**add support to other linux distro's**

first flash your distro of choice with [Rufus](https://rufus.ie/) it allows you to modify your usb file's.

then [download](https://github.com/HexaOneOfficial/dahliaos/blob/master/BOOT/bootia32.efi?raw=true) bootia32.efi.

copy the file to /EFI/boot on your usb device. **!** you may need to [disable secure boot](https://github.com/HexaOneOfficial/documentation/blob/master/assets/secure-boot/Disable-Secure-Boot.md)
