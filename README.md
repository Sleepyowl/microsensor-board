# Microsensor Board

This is a complete KiCad project of a miniature multiprotocol temperature and humidity sensor based on nRF54 SoC and HDC2080 sensor.

An example firmware for the board can be found here: [microsensor-firmware](https://github.com/Sleepyowl/microsensor-firmware).

# Features

- 2 layer PCB layout
- External RTC allows System Off sleep enabling ultra-low power consumption
- SoC supports BLE, ZigBee and Thread
- Miniature 6-pin Tag-Connect for firmware burning and debugging
- Button and LED
- Backside pads for CR20xx

# Issues

- No reverse polarity or overvoltage protection (I don't need it for my application)

# Manufacturing

I have manufactured working prototypes on PCBWay with the following parameters, though I would really evaluate using ENIG for the panelized version.

| Parameter              | Value            |
|------------------------|------------------|
| Layers                 | 2                |
| Thickness              | 0.8 mm           |
| Min Track / Spacing    | 4 / 4 mil        |
| Min Hole Size          | 0.3 mm           |
| Surface Finish         | HASL (Lead-Free) |
