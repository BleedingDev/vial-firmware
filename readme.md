## Vial configuration for the Bastard keyboards

Those are the files you need to make vial work on your Bastard Keyboard.

### How to use

- download vial: https://get.vial.today/
- flash the hex file found in the release that matches your keyboard
- sideload the json in vial and configure your keyboard !

### Advanced configuration

If you want to modify the firmware, you can fork vial's QMK fork, and copy the `bastardkb` folder inside the `keyboards` folder from the fork.

Then, modify the layouts or other options, compile with the appropriate command, and flash.
You can find more info in the [bastardkb qmk folders](https://github.com/qmk/qmk_firmware/tree/master/keyboards/bastardkb).