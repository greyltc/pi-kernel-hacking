# pi-kernel-hacking
Arch Linux PKGBUILDs for Raspberry Pi 2&amp;3

### Branches here
1. pi2-default
 - holds the files for [my linux-rpi2-default-git AUR package](https://aur.archlinux.org/packages/linux-rpi2-default-git/) 
1. pi2-latest
 - holds the files for [my linux-rpi2-latest-git AUR package](https://aur.archlinux.org/packages/linux-rpi2-latest-git/)
1. pi3-default
 - holds the files for [my linux-rpi3-default-git AUR package](https://aur.archlinux.org/packages/linux-rpi3-default-git/)
1. pi3-latest
 - holds the files for [my linux-rpi3-latest-git AUR package](https://aur.archlinux.org/packages/linux-rpi3-latest-git/)

The PKGBUILDs in these branches describe how the kernel should be built and packaged for a Raspberry Pi (model 2 or 3). All of them fetch code from [raspberrypi/linux](https://github.com/raspberrypi/linux) but I'd love it if one day they were fetched right from kernel.org.

"-latest" means the code is fetched from the most recent branch of [raspberrypi/linux](https://github.com/raspberrypi/linux) (kernel version 4.5.x as of this writing)  
"-default" means the code is fetched from the default branch of [raspberrypi/linux](https://github.com/raspberrypi/linux) (kernel version 4.1.x as of this writing)  
