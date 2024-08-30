# Radium Theme for GNOME Terminal

This directory contains the Radium theme configuration for the GNOME Terminal, which is a popular terminal emulator on Linux distributions that use the GNOME desktop environment. Follow these instructions to apply the Radium theme using the provided shell script.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Gnome
```

### Step 2: Run the Shell Script

A shell script is provided to automate the process of applying the Radium theme to your GNOME Terminal. This script adjusts the dconf settings directly.

1. Make the Script Executable:
   Before running the script, make it executable with the following command:
```bash
   chmod +x gnome.sh
```
2. Execute the Script:
   Run the script to apply the Radium theme:
```bash
   ./gnome.sh
```
   This script will automatically set the color palette, background, and foreground colors in your GNOME Terminal to match the Radium theme.

### Step 3: Verify the Changes

After running the script, open a new instance of GNOME Terminal to see the changes. The new color scheme should be in effect. If not, you might need to restart the terminal or log out and back in for the changes to take full effect.

## Customization

If you wish to adjust the color values further or tweak other settings, you can modify the apply_radium_theme.sh script or use the GNOME Terminal preferences GUI:

- Open GNOME Terminal.
- Go to Preferences.
- Select your profile and navigate to the Colors tab.

## Support

For more help or to report issues related to the GNOME Terminal configuration, feel free to submit issues in the main repository issue tracker.

## Contributing

Contributions are welcome! If you have improvements or fixes for the script or the theme, please fork the repository, make your changes, and submit a pull request.