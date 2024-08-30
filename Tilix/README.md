# Radium Theme for Tilix

This directory contains the Radium theme configuration for Tilix, a tiling terminal emulator for Linux that supports multiple sessions in a single window or tabs. Follow these instructions to apply the Radium theme to your Tilix terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Tilix
```
### Step 2: Import the Color Scheme

Tilix uses JSON files for color schemes. The Radium theme is provided in a file named Radium.json within this directory.

1. Copy the Radium.json file to your Tilix schemes directory, which is usually located at ~/.config/tilix/schemes/:
```bash
   cp Radium.json ~/.config/tilix/schemes/
```
2. If the schemes directory does not exist, you may need to create it first:
```bash
   mkdir -p ~/.config/tilix/schemes
```
### Step 3: Apply the Color Scheme

After copying the theme file, you can apply it through Tilix:

1. Open Tilix.
2. Right-click on the terminal area and go to Preferences.
3. In the Preferences window, navigate to Profile and then to the Color tab.
4. From the Color Scheme dropdown, select Radium to apply the theme.

### Step 4: Verify the Changes

Open a new session in Tilix to see the changes. The Radium theme colors should now be visible, enhancing the aesthetic of your terminal.

## Customization

The Radium theme colors are designed to provide a comfortable and modern look, but you may adjust the colors as per your needs:

- Modify the Radium.json directly if you wish to tweak the color palette.
- Changes can be seen immediately in Tilix after reloading the profile.

## Support

For more help or to report issues related to the Tilix configuration, please submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions to the Radium theme are welcome! If you have enhancements or additional configurations for Tilix, please fork the repository, make your changes, and submit a pull request with a detailed description of your updates.

Thank you for using the Radium theme for Tilix!