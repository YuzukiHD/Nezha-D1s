# Nezha-D1s
Official D1s EVB board

![Nezha D1s](Bitmap/Nezha_D1s.jpg)

## About

The Nezha D1s development board is a EVB based on the Allwinner D1s chip design.

- Support RGB display interface;
- Support DSI interface;
- Support TP interface;
- Support LINEIN interface, support HPOUT interface;
- Support TVIN/TVOUT interface;
- Support FM radio;
- Integrated Allwinner XR829 WiFi/BT chip;
- Support JATG/UART debug;
- Support SD Card / NOR / NAND Flash Boot;
- Support USB Host/Device;
- Tina Linux / Buildroot(YuzukiSBC) / RTOS

It can be used for chip evaluation, program pre-research and personal DIY, and can be applied to product forms such as game consoles, smart commercial displays, HMI, and smart central control.

## Guides



## D1s

D1s is a cost-effective AIoT chip designed by Allwinner for the intelligent decoding market. It uses a 64bit RISC-V ISA Alibaba T-Head C906 CPU, built-in 64M DDR2, supports Linux system, and integrates a large number of self-developed audio and video related IP, which can support full format decoding such as H.265, H.264, MPEG-1 /2/4, JPEG. D1s supports ADC/DAC/I2S/PCM/DMIC/OWA and other audio interfaces. It can be widely used in smart home panels, HMI, industrial control, smart cars and other products.

### CPU

```
Alibaba T-Head C906 RISC CPU, 1008MHz (RV64IMAFDCVX, Imp M-mode, S-mode, U-mode)
32 KB I-cache + 32 KB D-cache
```

### Memory

```
SIP 64 MB DDR2
SD3.0/eMMC5.0, SPI Nor/NAND Flash
```

### Video Engine

```
Video decoding
    H.265 up to 1080p@60fps
    H.264 up to 1080p@60fps
    MPEG-1/2/4, JPEG, VC1 up to 1080p@60fps
Video encoding
    JPEG/MJPEG up to 1080p@60fps
    Supports input picture scaler up/down
```

### Display Engine

```
CVBS OUT interface, supporting NTSC and PAL format
RGB LCD output interface up to 1920 x 1080@60fps
Dual link LVDS interface up to 1920 x 1080@60fps
4-lane MIPI DSI interface up to 1920 x 1200@60fps
```

### Video IN

```
8-bit parallel CSI interface
```

### Audio

```
2 DACs and 3 ADCs
Analog audio interfaces: MICIN1P/N, MICIN2P/N, MICIN3P/N, FMINL/R, LINEINL/R, LIEOUTLP/N, LINEOUTRP/N, HPOUTL/R
Digital audio interfaces: I2S/PCM, DMIC, OWA IN/OUT
```

### Connectivity

```
USB2.0 DRD, USB2.0 Host
SDIO 3.0, SPI x 2, UART x 6, TWI x 4
PWM (8-ch), GPADC (2-ch), LRADC (1-ch), TPADC (4-ch), IR TX&RX
10/100/1000M EMAC with RMII and RGMII interfaces
```

### Package

```
eLQFP128, 14 mm x 14 mm
```

### Chip process

```
22nm
```






Documents: https://d1s.docs.aw-ol.com/



