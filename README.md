# Occupy Wi-Fi

## Image Generate

```bash
$ cd occupy-wifi 
$ wget http://downloads.openwrt.org/attitude_adjustment/12.09/ar71xx/generic/OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486.tar.bz2
$ tar -xvjf OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486.tar.bz2
$ cd OpenWrt-ImageBuilder-ar71xx_generic-for-linux-i486
$ make image PROFILE=TLMR3040  # Assuming TP-Link MR3040, or use any other profile you like
```

