# Radium Theme for Alacritty

This directory contains the Radium theme configuration for the Alacritty terminal. Alacritty is a GPU-accelerated terminal emulator focused on performance and simplicity. Follow these instructions to apply the Radium theme to your Alacritty terminal.

## Installation Instructions

### Step 1: Clone the Repository

First, ensure you have the latest version of the theme files:

```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Alacritty
```

### Step 2: Update Alacritty Configuration

Alacritty uses a configuration file called alacritty.yml typically located in ~/.config/alacritty/. If you don't already have this file, you may need to create it.

1. Copy the Theme Configuration:
   Copy the radium.yml file from this folder to your Alacritty configuration directory:

   bash
   cp radium.yml ~/.config/alacritty/alacritty.yml

   If you already have an existing configuration and just want to update the colors, you can merge the color settings from radium.yml into your existing alacritty.yml.

2. Edit Your Configuration:
   Open your alacritty.yml with a text editor to ensure the colors are correctly set. It should look something like this under the colors: key:

   ```yaml
   colors:
     Default colors
     primary:
       background: '0x101317'
       foreground: '0xd4d4d5'

     Normal colors
     normal:
       black:   '0x0a0d11'
       red:     '0xf87070'
       green:   '0x37d99e'
       yellow:  '0xffe59e'
       blue:    '0x7ab0df'
       magenta: '0xc397d8'
       cyan:    '0x50cad2'
       white:   '0x525559'

     Bright colors
     bright:
       black:   '0x191d22'
       red:     '0xff8e8e'
       green:   '0x79dcaa'
       yellow:  '0xffeda6'
       blue:    '0x87bdec'
       magenta: '0xb68acb'
       cyan:    '0x63b3ad'
       white:   '0xd4d4d5'
    ```
### Step 3: Reload Alacritty

After you've updated and saved your configuration file, restart Alacritty to apply the new theme. Changes should take effect immediately.

## Customization

Feel free to tweak the color values in the alacritty.yml file to better suit your preferences or adjust for your display's characteristics.

## Support

For more help, feel free to submit issues in the main repository issue tracker if you encounter problems specifically related to the Alacritty configuration.
