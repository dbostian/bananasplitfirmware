# Banana Split Firmware

![imgur](https://i.imgur.com/WrQvyal.jpg)

## Intro
This is the ZMK firmware config for the Banana Split macropad. Find that project here: [https://github.com/dbostian/bananasplit](https://github.com/dbostian/bananasplit)

## ZMK
Instructions on how to install ZMK are available here: [https://zmk.dev/docs/user-setup](https://zmk.dev/docs/user-setup)

## Config
After cloning this repo, you will want to change key assignment in `/main/config/boards/shields/banana_split/banana_split.keymap`

Defaults in this config are (left to right):
1) Lock Screen (Command Control Q)
2) "github.com/dbostian/bananasplit"
3) Screenshot, entire screen (Command Shift 3)
4) Screenshot, selection (Command Shift 4)

5) Tab Left, Chrome (Command Alt Left)
6) Desktop Left (Control Left)
7) Desktop Right (Control Right)
8) Tab Right, Chrome (Command Alt Right)

Hold 1) and press 8) to enter bootloader mode for flashing new firmware
