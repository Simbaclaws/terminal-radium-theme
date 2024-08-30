# Radium Theme for Konsole (KDE Terminal)

This directory contains the Radium theme configuration for Konsole, KDE's terminal emulator. Konsole is known for its deep integration with the KDE desktop and its high degree of customizability. Follow these instructions to apply the Radium theme to your Konsole terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/Konsole
```
### Step 2: Import the Color Scheme

Konsole uses color scheme files with the extension .colorscheme for easy import of color settings.

1. Locate the Radium.colorscheme file in this directory.
2. To install the color scheme, copy the Radium.colorscheme file to your Konsole color scheme directory, which is usually located at ~/.local/share/konsole/:
```bash
   cp Radium.colorscheme ~/.local/share/konsole/
```
3. Restart Konsole.

### Step 3: Apply the Color Scheme

After copying the file, apply the theme in Konsole:

1. Open Konsole.
2. Go to Settings > Configure Konsole.
3. Under Profiles, select the profile you wish to modify (or create a new one).
4. In the Appearance tab, find and select the 'Radium' theme from the list.
5. Click Apply and then OK to confirm the changes.

### Step 4: Verify the Changes

Open a new tab or window in Konsole to see the Radium theme in action. The new color scheme should now be visible, providing a sleek and modern look.

## Customization

The Radium theme is designed to be both beautiful and functional, but you might want to adjust some colors to better suit your environment or preferences:

- You can fine-tune the color settings directly from Konsole’s settings menu under the Appearance tab after selecting the Radium theme.
- Adjust the color values in the Radium.colorscheme file if you prefer editing text files directly.

## Support

For additional assistance or to report any issues with the Konsole configuration, please submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

If you have suggestions for improving or extending the Radium theme within Konsole, please feel free to fork the repository, make your changes, and submit a pull request with a description of your modifications.

Thank you for using the Radium theme for Konsole!