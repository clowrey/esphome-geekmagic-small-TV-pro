# esphome-geekmagic-small-TV-pro

This board does not have any PSRAM - which is basically necessary for 240x240 resolution with the LVGL component + ESPhome - from what I can tell so far. Planning to replace the module with these: https://www.mouser.com/ProductDetail/356-ESP32WRM32EN8R2

I have asked about an upgraded version from the manufacturer and they responded that they will create one with the S3 16MB + 8MB PSRAM! So I would wait for that version for ESPhome use https://github.com/GeekMagicClock/smalltv-pro/issues/44

static shows it does not load LVGL
![smallTVpro-lvgl](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/dac09d62-dfbb-40f6-a41d-26fb225005dc)

works with default older lambda display methods in ESPhome
![smallTVpro-lambda](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/d775ecc8-17b4-4f8c-88b6-391e46f03dc1)

works at 160x160 resolution
![smalltvLVGL160](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/08fcb36b-ec0c-4536-8dc2-74ee0688883d)
