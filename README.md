# Dan16
*A 16 key macropad with a rotary encoder*

![IMG_20211023_211752](https://user-images.githubusercontent.com/66566995/138569063-d7529213-9c71-4e8c-82f8-e084b6d467f3.png)

The dan16 is a handwired 3d printed macropad with a rotary encoder.
It is based ont the [Void16](https://github.com/victorlucachi/void16) case files by [Victor Lucachi](https://github.com/victorlucachi)
It is powered by QMK runnung on a Pro micro controller

# Wiring
```
ROW0    ROW1    ROW2    ROW3
F4      F5      F7      B3


COL0    COL1    COL2    COL3
D3      D1      D4      E6


Encoder Pad A           Encoder Pad B
D2                      B2
```
*The encoder has a push button that acts as a switch at row 0, col 0*

# QMK
[Here](https://github.com/loic-berland/qmk_firmware/tree/dev_branch/keyboards/handwired/dan16) is my fork of the QMK firmware, it includes everything you need to build your own keymap, including VIA support.

# Build Specs
* JWICKS Yellow switches
* EC11 encoder
* GMK oblivion clone 
* 3D printed case, encoder adapter and knob
