# Waveshare UPS Battery Plugin for Raspberry Pi Zero (2) W

This is a plugin designed for displaying the battery percentage when using the Waveshare UPS HAT (C) on a Raspberry Pi Zero (2) W.

## Requirements

- **Raspberry Pi Zero (2) W**
- **Waveshare UPS HAT (C)**: [Product Page](https://www.waveshare.com/ups-hat-c.htm) | [Wiki](https://www.waveshare.com/wiki/UPS_HAT_(C))
- **Pwnagotchi Image**: You can use this [Pwnagotchi image](https://github.com/jayofelony/pwnagotchi/releases).

**Important**: Make sure to enable I2C on your Raspberry Pi before proceeding with the installation.

## Installation

### Step 1: Enable I2C on your Raspberry Pi

First, ensure that I2C is enabled on your Raspberry Pi. You can enable it using `raspi-config`:

```bash
sudo raspi-config

### Step 2: Enable I2C on your Raspberry Pi

Copy the wavesharebattery.py into /usr/local/share/pwnagotchi/available-plugins and check with

```bash
sudo pwnagotchi plugins list

if the plugin gets detected.

### Step 3: Install the plugin

To install this plugin type:

```bash
sudo pwnagotchi plugins install wavesharebattery

and restart the pwnagotchi. After that you should see the plugin on the webinterface. Enable it and enjoy! :)






