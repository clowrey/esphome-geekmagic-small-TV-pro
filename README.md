# esphome-geekmagic-small-TV-pro



By default this product does not have any PSRAM - which is basically necessary for 240x240 resolution with the LVGL component + ESPhome - from what I can tell so far. I have now replaced some of the modules with these: https://www.mouser.com/ProductDetail/356-ESP32WRM32EN8R2

I have asked about an upgraded version from the manufacturer and they responded that they will create one with the S3 16MB + 8MB PSRAM! So I would wait for that version for ESPhome use as removing and replacing the WROOM module is a little time consuming... https://github.com/GeekMagicClock/smalltv-pro/issues/44


![geek_psram3](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/1fdc9e2b-47fd-4b6e-977b-85750b69c947)

![geek_psram4](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/9772359a-9c05-4097-82f5-c06b855eb192)

![geek_psram2](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/79a1c3a8-da3e-443b-93fd-42c934041e9d)

![geek_psram5](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/ad22d69b-c36b-4708-a54e-dc3af056e522)

![geek_psram6](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/fdfe5702-3306-4ad9-95ce-fd54b24404d1)

![geek_psram1](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/231e46d1-497c-4549-b8fe-3d33d9f484f3)



-- OLD before replacing WROOM with PSRAM version --

static shows it does not load LVGL
![smallTVpro-lvgl](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/dac09d62-dfbb-40f6-a41d-26fb225005dc)

works with default older lambda display methods in ESPhome
![smallTVpro-lambda](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/d775ecc8-17b4-4f8c-88b6-391e46f03dc1)

works at 160x160 resolution
![smalltvLVGL160](https://github.com/clowrey/esphome-geekmagic-small-TV-pro/assets/6935928/08fcb36b-ec0c-4536-8dc2-74ee0688883d)
