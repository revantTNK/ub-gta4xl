# Ubuntu Touch for Samsung Galaxy Tab S6 Lite (gta4xlwifi)

# Building
To build by hand, run these commands;

```
./build.sh -b bd  # bd is the name of the build directory
./build/prepare-fake-ota.sh out/device_samsung-gta4xlwifi.tar.xz ota
./build/system-image-from-ota.sh ota/ubuntu_command out
```


# Installation
To install, follow these steps;

- Flash the lastest android 10 stock firmware.
- Flash LineageOS Recovery https://archive.org/download/lineageos20210217/recovery/gta4xlwifi/20210217/
- Wipe data
- Copy ubuntu.img onto /data/ 
- Flash boot.img onto boot
