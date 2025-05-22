# (forked from) eiga's zmk-config

## TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem) **studio enabled**
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle) **unmodified**
- [TOTEM Prospector](https://github.com/eigatech/zmk-config/tree/totem-prospector) **daily driver**

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers.

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.
