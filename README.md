# Dell-7348-hackintosh

|           | Specs                                            |
|-----------|--------------------------------------------------|
| Type      | Dell Inspiron 7348                               |
| Bootloader| OpenCore 0.6.3                                   |
| OS        | macOS Big Sur 11.1 Beta (20C5048l)               |
| CPU       | Intel i7 5500U @ 2.40Ghz x2                      |
| GPU       | Intel HD Graphics 5500 (platform-id: 0x16260006) |
| Memory    | 8GB (built-in 1600Mhz)                           |
| SSD       | Crucial MX500 500GB                              |
| Display   | 13' 1920x1080                                    |
| Sound     | ALC3234 (ALC255, layout-id: 3/17/18/28/30).      |
| WIFI+BT   | DW1820A (14E4:43A3 with subsystem-id 0x0023)     |

# NOTE

**Please generate your MLB, SerialNumber and UUID after installed.**

# Working

- Touchpad works.
- WIFI/BT works.
- Sound works.
- F11/F12 backlight keys work.
- USB work, but usb 3.0 port only support usb 3.0 device.

# Not Working

- No Hibernate.

# Other Problem

- 8 apples glitch when start up, but you can enable legacy mode to fix it.
- Several reboot will into DELL ePAS diagnosis mode.

# Thanks

Thanks to acidanthera, daliansky etc.