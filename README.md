### Прошивки Вотериуса
[Вотериус](https://github.com/dontsovcmc/waterius)

[Основная статья по прошивке](https://github.com/dontsovcmc/waterius/blob/master/Firmware.md)

# 0.4.4
## Attiny85
### Arduino as ISP programmer
#### avrdude
[homes-smart.ru](http://homes-smart.ru/index.php?option=com_content&view=article&id=34&Itemid=171)

## ESP8266
### Утилита esptool
#### Как пакет Python

`$ python -m esptool --baud 115200 --port COM7 write_flash --flash_freq 40m --flash_size 1MB --flash_mode dio --verify 0x0 esp.bin`

```
esptool.py v2.5.0
Serial port COM7
Connecting........_____.....____
Detecting chip type... ESP8266
Chip is ESP8266EX
Features: WiFi
MAC: 68:c6:3a:a4:75:b0
Uploading stub...
Running stub...
Stub running...
Configuring flash size...
Flash params set to 0x0220
Compressed 359840 bytes to 253754...
Wrote 359840 bytes (253754 compressed) at 0x00000000 in 23.1 seconds (effective 124.8 kbit/s)...
Hash of data verified.

Leaving...
Verifying just-written flash...
(This option is deprecated, flash contents are now always read back after flashing.)
Flash params set to 0x0220
Verifying 0x57da0 (359840) bytes @ 0x00000000 in flash against esp.bin...
-- verify OK (digest matched)
Hard resetting via RTS pin...
```

# Контакты
Чат проекта Вотериус: [Gitter.im/waterius](https://gitter.im/waterius)
 



