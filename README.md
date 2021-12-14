# Dell-7348-hackintosh

|            | Specs                                            |
|------------|--------------------------------------------------|
| Type       | Dell Inspiron 7348                               |
| Bootloader | OpenCore 0.7.6                                   |
| OS         | macOS Big Sur 11.4                               |
| CPU        | Intel i7 5500U @ 2.40Ghz x2                      |
| GPU        | Intel HD Graphics 5500 (platform-id: 0x16260006) |
| Memory     | 8GB (built-in 1600Mhz)                           |
| SSD        | Crucial MX500 500GB                              |
| Display    | 13' 1920x1080                                    |
| Sound      | ALC3234 (ALC255, layout-id: 3/17/18/28/30).      |
| WIFI+BT    | DW1820A (14E4:43A3 with subsystem-id 0x0023)     |

# NOTE

## Using Siri/iMessage/etc

- using [Hackintool](https://github.com/headkaze/Hackintool) to generate your MLB, SerialNumber and UUID.

## Enable HiDPI

- add custom resolutions to [SwitchResX](https://www.madrau.com/index.html) to enable HiDPI. For example, 3072x1728 and 1536x864 resolutions are very nice for me :)

# Working

- Touchpad works.
- WIFI/BT works.
- Sound works.
- F11/F12 backlight keys work.
- USB2/3 works.

# Not Working

- No Hibernate.

# Other Problem

- The screen will show 8 apples when booting MacOS, which you can enable legacy mode to fix.
- Sometimes laptop will boot into DELL ePAS diagnosis mode.

# Thanks

Thanks to acidanthera, daliansky etc.
