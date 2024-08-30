# Radium Theme for Xorg (X Resources)

This directory provides the Radium theme configuration for X resources, which will affect multiple X-based terminal emulators like xterm and urxvt. Follow these instructions to apply the Radium theme colors to terminals that use X resources.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Xorg
```
### Step 2: Update X Resources

The X resources file, typically named .Xresources or .Xdefaults, is located in your home directory. If it doesn't exist, you can create it.

1. Open the .Xresources or .Xdefaults file in your preferred text editor. If the file does not exist, create it using:
```bash
   touch ~/.Xresources
```
2. Add or update the color settings to include the Radium theme:
```
*.foreground: #d4d4d5
*.background: #101317
*.cursorColor: #d4d4d5
*.color0: #0a0d11
*.color1: #f87070
*.color2: #37d99e
*.color3: #ffe59e
*.color4: #7ab0df
*.color5: #c397d8
*.color6: #50cad2
*.color7: #525559
*.color8: #191d22
*.color9: #ff8e8e
*.color10: #79dcaa
*.color11: #ffeda6
*.color12: #87bdec
*.color13: #b68acb
*.color14: #63b3ad
*.color15: #d4d4d5
```
3. Save the file and merge the resources with X server:
```bash
   xrdb -merge ~/.Xresources
```
### Step 3: Verify the Changes

Open a terminal that uses X resources, like xterm or urxvt, to check if the Radium theme colors are applied correctly. The new color scheme should now be visible.

## Customization

You can further adjust the color values or add other X resource configurations, such as font settings or cursor behavior, by editing the .Xresources or .Xdefaults file.

## Support

For more help or to report issues related to the X resources configuration, please submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions to the Radium theme are welcome! If you have enhancements or additional configurations for X resources, please fork the repository, make your changes, and submit a pull request with a detailed description of your updates.

Thank you for using the Radium theme for X resources!