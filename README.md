# Adblock Magisk Module

This is a simple adblock module for Magisk that blocks ads system-wide on magisk-rooted Android devices. 

## Description

This module uses the AdAway hosts file to block known ad and tracking domains. By blocking ads at the domain level, this prevents ads from being downloaded and displayed in apps and browsers on your device. This saves data usage and speeds up your device by reducing unnecessary network requests.

## Features

- Blocks ads across all apps and browsers
- Lightweight and efficient 

## Usage

  ![](adblock.gif)

- Flash the module in Magisk Manager.
- Type `su -c adblock` in terminal emulator (Termux recommended) to select an option, no need to reboot for changes to take effect
- Update hosts files regularly for best results

## Credits

- [Magisk](https://github.com/topjohnwu/Magisk) by topjohnwu
- [AdAway](https://adaway.org) open source project

## License

This module is released under the GNU General Public License v3 (GPL-3). All module code is open source. Hosts files are property of their respective maintainers.
