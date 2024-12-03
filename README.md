# eiga's zmk-config

Refer to the original repository [here](https://github.com/eigatech/zmk-config).

## Table of contents

Branches  

- [TOTEM](#totem)
- [Dongle Flashing](#dongle-flashing)
- [ZMK Keymap Editor](#zmk-keymap-editor)

## Hello

This is my fork of Eigatech's zmk config for the [TOTEM keyboard](https).

[Here](https://www.youtube.com/watch?v=YwsutNf1WRA&list=PL1E2ddJCbc13DvCGYXX9jVVX1BqNGKE5D&index=2) is the link to the reference video.

This repository hosts the zmk-config as seen in the YouTube video linked above.

Please refer to the [Dongle Flashing](#dongle-flashing) chapter for
instructions on using an extra microcontroller as a dongle.

> [NOTE]  
> These configurations are meant to be used with builds that are identical to the ones featured in the videos, otherwise they should be used as reference only.

## TOTEM

- [TOTEM](https://github.com/LargeCrowd/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/LargeCrowd/zmk-config/tree/totem-dongle)

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!

## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

Documentation and guides:

- [ZMK Firmware Documentation](https://zmk.dev/docs)
