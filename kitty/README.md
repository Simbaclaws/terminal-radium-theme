# Radium Theme for Kitty

This directory contains the Radium theme configuration for Kitty, a modern, hackable, featureful, OpenGL-based terminal emulator. Follow these instructions to apply the Radium theme to your Kitty terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Kitty
```
### Step 2: Update Kitty Configuration

Kitty uses a configuration file called kitty.conf, typically located in ~/.config/kitty/. If you don't already have this file, you may need to create it.

1. Open your kitty.conf file in your favorite text editor.
2. Add or update the color settings to include the Radium theme:

```
background #101317
foreground #d4d4d5
cursor #d4d4d5

Normal colors
color0 #0a0d11
color1 #f87070
color2 #37d99e
color3 #ffe59e
color4 #7ab0df
color5 #c397d8
color6 #50cad2
color7 #525559

Bright colors
color8 #191d22
color9 #ff8e8e
color10 #79dcaa
color11 #ffeda6
color12 #87bdec
color13 #b68acb
color14 #63b3ad
color15 #d4d4d5
```
3. Save the kitty.conf file and restart Kitty to see the changes.

### Step 3: Verify the Changes

Open Kitty to verify that the new color scheme has been applied correctly. The new Radium theme colors should now be visible, enhancing the visual experience of your terminal.

## Customization

If you wish to further adjust the color values or tweak other settings like font size or window padding:

- You can edit the kitty.conf file to customize the terminal to your liking.
- Kitty supports live configuration reloading, so you can see your changes in real-time by saving the file while Kitty is running.

## Support

For more help or to report issues related to the Kitty configuration, feel free to submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions are welcome! If you have improvements for the Radium theme or additional configurations for Kitty, please fork the repository, make your changes, and submit a pull request with a detailed description of your updates.

Thank you for using the Radium theme for Kitty!