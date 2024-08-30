# Radium Theme for Terminator

This directory contains the Radium theme configuration for Terminator, a powerful terminal emulator that supports tabs and grids, making it ideal for heavy terminal users. Follow these instructions to apply the Radium theme to your Terminator terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Terminator
```
### Step 2: Update Terminator Configuration

Terminator uses a configuration file called config, which is typically located in ~/.config/terminator/. If you don't have this file, it will be created the first time you run Terminator.

1. Open the config file in your preferred text editor.
2. Add or update the color settings to include the Radium theme:

```
[profiles]
  [[default]]
    background_color = "#101317"
    foreground_color = "#d4d4d5"
    cursor_color = "#d4d4d5"
    palette = "#0a0d11:#f87070:#37d99e:#ffe59e:#7ab0df:#c397d8:#50cad2:#525559:#191d22:#ff8e8e:#79dcaa:#ffeda6:#87bdec:#b68acb:#63b3ad:#d4d4d5"
```
3. Save the config file and restart Terminator to see the changes.

### Step 3: Verify the Changes

Open Terminator to verify that the new color scheme has been applied correctly. The new Radium theme colors should now be visible, enhancing the visual experience of your terminal.

## Customization

If you wish to further adjust the color values or tweak other settings like font size or window preferences:

- You can edit the config file to customize the terminal to your liking.
- Terminator supports multiple profiles, so you can apply the Radium theme to specific profiles if desired.

## Support

For more help or to report issues related to the Terminator configuration, feel free to submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions are welcome! If you have improvements for the Radium theme or additional configurations for Terminator, please fork the repository, make your changes, and submit a pull request with a detailed description of your updates.

Thank you for using the Radium theme for Terminator!