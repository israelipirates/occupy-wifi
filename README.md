![Occupy WiFi](http://i.imgur.com/jIIo7jV.png)

## Image Generate

Linux is required for image generation (no, OS X won't jive). These steps assume a TP-Link TL-MR3040 device. Change the `PROFILE` variable if you are using any other device (see [this link](http://pastebin.com/WbudpBDJ) for more `ar71xx` options.)

```bash
$ cd occupy-wifi 
$ wget http://downloads.openwrt.org/attitude_adjustment/12.09/ar71xx/generic/OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486.tar.bz2
$ tar -xvjf OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486.tar.bz2
$ cd OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486
$ make image PROFILE=TLMR3040 PACKAGES="nodogsplash" FILES=files/
```
