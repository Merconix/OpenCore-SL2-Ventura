# OpenCore EFI folder for MacOS 13 Ventura on the Surface Laptop 2 (i5)
Inspired by [MattKC](https://github.com/itsmattkc/OpenCore-SL3-BigSur/blob/master/README.md)

Made possible by [BigSurface](https://github.com/Xiashangning/BigSurface)

Just about everything that can work, works: Audio, boot chime, keyboard (+ backlight), touchpad, GPU Acceleration, brightness controls, battery readout, USB

What doesn't work:
- Touchscreen, [though BigSurface apparently has a fix](https://github.com/Xiashangning/BigSurface)
- Caps lock LED [I don't think this can be fixed]
- Webcam [Currently impossible]
- Built-in Wi-Fi + Bluetooth [Currently impossible]

Quirks:
- USB Tethering driver included courtesy of [HoRNDIS](https://github.com/jwise/HoRNDIS)
- Unsure if MiniDP-out works, un-tested
