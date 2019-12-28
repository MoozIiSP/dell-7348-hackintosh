# Dell-7348-hackintosh

|         | Specs                                            |
|---------|--------------------------------------------------|
| Type    | Dell Inspiron 7348                               |
| OS      | macOS Catalina 10.15.2                           |
| CPU     | Intel i7 5500U @ 2.40Ghz x2                      |
| GPU     | Intel HD Graphics 5500 (platform-id: 0x16260006) |
| Memory  | 8GB (built-in 1600Mhz)                           |
| SSD     | Crucial MX500 500GB                              |
| Display | 13' 1920x1080                                    |
| Sound   | ALC3234 (ALC255, layout-id: 3/17/18/28/30).      |
| WIFI+BT | DW1820A (14E4:43A3 with subsystem-id 0x0023)     |

# Some BUGS
- The touchpad works but sometimes will cause kernel panic when booting.

# TODO-List

- [ ] DSDT/SSDT patch
- [x] Freeze issue of DW1820A
- [x] F11/F12 backlight control, [solution](https://pqrs.org/osx/karabiner/)
- [x] USB port custom*
- [x] Touchpad works
- [ ] No hibernate
- [ ] 8 apples glitch when start up, but you can enable legacy mode to fix it
- [ ] several reboot will into DELL ePAS diagnosis mode

