# VeElecrowDisplay - Victron VenusOs package for 5" HDMI 800 x 480 Capacitive Touch LCD Display

## Introduction

This packages provides the configuration settings needed to operate the a 5" TFT touchscreen display with Venus OS. Take a look at the [wiki](https://github.com/herrfrei/VeElecrowDisplay/wiki) for information about the hardware I used.

## Installation

You need to install [SetupHelper](https://github.com/kwindrem/SetupHelper) before to install/uninstall this package.
As a bonus, it provides also the automatic reinstallation of the package after a VenusOs update.

### Installaton via GUI

When installing with the Package Manager GUI, the default display settings apply. These are:

- **unrotated** mounting (HDMI connector is in top right corner when looking from the display side)
- backlight in connected to **GPIO pin 23** on Raspberry Pi

