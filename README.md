# corne-keymap

I flash my custom firmware using [QMK](https://qmk.fm/). You should read the [docs](https://docs.qmk.fm/#/newbs_building_firmware) to build your own firmware.

I have Elite-C2's as my keyboard micros.

To flash the firmware it's actually very easy:

```shell
# ivanovskyOrtega is the name of the custom firmware I created
# "-e CONVERT_TO=elite_pi" is for Elite PI conpatible micros, read the QMK docs to use the one that suits to your hardware.
> qmk flash -kb crkbd -km ivanovskyOrtega -e CONVERT_TO=elite_pi  
> qmk compile -kb crkbd -km ivanovskyOrtega
```
