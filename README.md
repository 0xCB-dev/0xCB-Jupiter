# Jupiter
## An 1800-sized through-hole keyboard with various layout options

Licence | OSHWA
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-Jupiter/blob/main/LICENSE.svg) | [![]()](https://certification.oshwa.org/.html)

### QMK

[keyboards/0xcb/jupiter/](https://github.com/qmk/qmk_firmware/tree/master/keyboards/0xcb/jupiter)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or the reset button)
* `make 0xcb/jupiter:via:flash`

### Assembly:

You can use the [humanpnp](https://files.0xcb.dev/0xCB-Jupiter/humanpnp.html) to easily place components.

### PCB:
KiCad 6 stable release - using these [libs](https://github.com/0xCB-dev/0xcb-libs)


### CAD files:


#### BOM:

