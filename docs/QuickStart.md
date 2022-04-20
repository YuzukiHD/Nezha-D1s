# Quick Start
## Download Tina Firmware
Get the firmware in [Firmwares](https://github.com/YuzukiHD/Nezha-D1s/tree/main/Software/Firmware). Extract the tarball and you will get a card image. 

Then, Open PhonixCard and follow those step to make a bootable sd card.

![Flash](/.github/assets/Flash.PNG)

## Access The Shell via ADB
The firmware is preconfigured so that it works as an ADB USB gadget after booted up. Connect the board via the otg port and if your computer has installed ADB and corresponding drivers, the shell should be prompted after entering
```bash
adb shell
```

## Debugging via Serial
The serial prints boot log and kernel messages in addition to the shell prompt. The default debug serial is `UART0` at `UART GPIO`. It can be easily connected with a pinheader at the bottom right of the board.

## Debugging via CKLink
Before you start, you need to have a CKlink. Since RV DM is not yet supported during chip development, it is necessary to use CKLink for debugging.

![cklink](/.github/assets/cklink.jpg)

Of course, you can also make a CKLink by yourself. Like https://oshwhub.com/ZZZXXJ/cklink-tiny

Once you have a CKLink, convert the wiremap to the wiremap on the Nezha D1s board, here I used a very simple adapter board.

![cklink_ada](/.github/assets/CKLink_Adapter.jpg)

When the connection is completed, use T-HeadDebugServer to connect, you can debug.

![T-HeadDebugServer](/.github/assets/T-HeadDebugServer.png)
