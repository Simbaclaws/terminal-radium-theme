# Radium Theme for XFCE4 Terminal

This directory contains the Radium theme configuration for XFCE4 Terminal, the default terminal emulator for the XFCE desktop environment. Follow these instructions to apply the Radium theme to your XFCE4 Terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/XFCE4Terminal
```
### Step 2: Update XFCE4 Terminal Configuration

XFCE4 Terminal uses a configuration file named terminalrc, located in ~/.config/xfce4/terminal/. If this file doesn't exist, it will be created the first time you run XFCE4 Terminal.

1. Open the terminalrc file in your preferred text editor.
2. Add or update the color settings to include the Radium theme:
```
ColorForeground=#d4d4d5
ColorBackground=#101317
ColorCursor=#d4d4d5
ColorPalette=#0a0d11;#f87070;#37d99e;#ffe59e;#7ab0df;#c397d8;#50cad2;#525559;#191d22;#ff8e8e;#79dcaa;#ffeda6;#87bdec;#b68acb;#63b3ad;#d4d4d5
```
3. Save the terminalrc file and close your editor.

### Step 3: Reload XFCE4 Terminal

Restart XFCE4 Terminal to apply the changes. You can do this by closing and reopening the terminal, or you can use the following command in XFCE4 Terminal:
```bash
xfce4-terminal --reload-settings
```
### Step 4: Verify the Changes

Open a new terminal window to check if the Radium theme colors are applied correctly. You should immediately see the updated color scheme.

## Customization

If you wish to further adjust the color values or tweak other settings:

- You can modify the terminalrc file to customize various aspects of the terminal's appearance, such as font size and scrollbar behavior.
- XFCE4 Terminal also supports multiple profiles, allowing you to apply the Radium theme selectively.

## Support

For additional help or to report issues related to the XFCE4 Terminal configuration, please submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions are welcome! If you have improvements or additional configurations for the XFCE4 Terminal, please fork the repository, make your changes, and submit a pull request detailing your contributions.

Thank you for using the Radium theme for XFCE4 Terminal!