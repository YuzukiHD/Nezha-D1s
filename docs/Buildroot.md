## Start up

### Download Buildroot 

```
git clone https://github.com/YuzukiHD/Buildroot-YuzukiSBC
cd Buildroot-YuzukiSBC
```

### Apply Build Environment and Defconfig

```
source envsetup.sh    # Set the build environment and check update
lunch                 # lunch the buildroot envrionmnet

make awol_nezha_d1s_defconfig 
```

### Build

```
make
```

### Flashing Firmware

Once the build process is finished you will have an image called "sdcard.img"
in the output/images/ directory.

Copy the bootable "sdcard.img" onto an SD card with "dd":

```
sudo dd if=output/images/sdcard.img of=/dev/sdX
```

