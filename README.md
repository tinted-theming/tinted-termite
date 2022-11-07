# base16-termite

This repository is meant to work with
[tinted-theming/home](https://github.com/tinted-theming/home).
It provides a simple template that can be used with the base16 color schemes to
generate a functional config file for
[thestinger/termite](https://github.com/thestinger/termite),
a keyboard-centric VTE-based terminal.

To use, you can copy one of the config files in themes/ or use curl:

```
mkdir -p ~/.config/termite
curl https://raw.githubusercontent.com/tinted-theming/base16-termite/master/themes/base16-default-dark.config >> ~/.config/termite/config
```
