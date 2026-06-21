# Installation

Follow these steps to install and set up this Openbox configuration on your Arch Linux system.

## Prerequisites
Ensure you have the following packages installed:
```bash
sudo pacman -S openbox xfce-power-manager tint2 xorg-xinit  pcmanfm lxterminal nwg-look

Packages installed with trizen (AUR helper)
conky-lua-nv obconf-qt obmenu-generator openbox-themes flat-remix-gtk
Note: conky-lua-nv is strictly required to get the auzia-conky theme working properly
Clone or download this repository.
Copy the configuration files to your ~/.config/ directory:
cp -r configs/openbox/* ~/.config/openbox/
