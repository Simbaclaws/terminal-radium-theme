# Radium Theme for Termux

This directory contains the Radium theme configuration for Termux, an Android terminal emulator and Linux environment app that works directly without rooting or setup. Follow these instructions to apply the Radium theme to your Termux setup.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Termux
```
### Step 2: Update Termux Configuration

Termux allows customization through a file called colors.properties, which needs to be located in ~/.termux/ directory.

1. If you do not have a colors.properties file, create it using the touch command:

   touch ~/.termux/colors.properties

2. Open the colors.properties file in your preferred text editor within Termux, like vim or nano.

3. Add the following color configurations to the file:
```
color0 = 0a0d11
color1 = f87070
color2 = 37d99e
color3 = ffe59e
color4 = 7ab0df
color5 = c397d8
color6 = 50cad2
color7 = 525559
color8 = 191d22
color9 = ff8e8e
color10 = 79dcaa
color11 = ffeda6
color12 = 87bdec
color13 = b68acb
color14 = 63b3ad
color15 = d4d4d5
background = 101317
foreground = d4d4d5
cursor = d4d4d5
```
4. Save the file and exit the editor.

### Step 3: Reload Termux Settings

To apply the new theme colors, refresh Termux settings:

termux-reload-settings

This command will reload the configuration and apply your new theme immediately.

### Step 4: Verify the Changes

Reopen Termux to see if the new color scheme has been applied correctly. The Radium theme should now be visible, providing a fresh and modern look to your terminal.

## Customization

Feel free to adjust the color values in the colors.properties file to better suit your viewing preferences or specific needs.

## Support

For more help or to report issues related to the Termux configuration, please submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions to the Radium theme are welcome! If you have enhancements or additional configurations for Termux, please fork the repository, make your changes, and submit a pull request detailing what you have modified or added.

Thank you for using the Radium theme for Termux!