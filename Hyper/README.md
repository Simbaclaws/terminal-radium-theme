# Radium Theme for Hyper.js

This directory contains the Radium theme configuration for Hyper.js, a JavaScript/HTML/CSS based terminal emulator. Follow these instructions to apply the Radium theme to your Hyper.js terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/yourusername/radium-theme-terminals.git
cd radium-theme-terminals/Hyper
```
### Step 2: Update Hyper.js Configuration

Hyper.js uses a file called .hyper.js for configuration, which is typically located in your home directory.

1. Open the .hyper.js file in your favorite text editor.
2. Locate the colors section in the config object.
3. Update the shell colors with the Radium theme values:

```javascript
colors: {
  black: '#0a0d11',
  red: '#f87070',
  green: '#37d99e',
  yellow: '#ffe59e',
  blue: '#7ab0df',
  magenta: '#c397d8',
  cyan: '#50cad2',
  white: '#525559',
  lightBlack: '#191d22',
  lightRed: '#ff8e8e',
  lightGreen: '#79dcaa',
  lightYellow: '#ffeda6',
  lightBlue: '#87bdec',
  lightMagenta: '#b68acb',
  lightCyan: '#63b3ad',
  lightWhite: '#d4d4d5',
  backgroundColor: '#101317',
  foregroundColor: '#d4d4d5',
  cursorColor: '#d4d4d5',
  borderColor: '#525559'
}
```
4. Save the .hyper.js file and restart Hyper.js to see the changes.

### Step 3: Verify the Changes

Open Hyper.js to verify that the new color scheme has been applied correctly. You should see the Radium theme colors in effect.

## Customization

Feel free to tweak the color values in the .hyper.js file to better suit your preferences or to adjust for your display's characteristics.

## Support

For more help or to report issues related to the Hyper.js configuration, feel free to submit issues in the main repository issue tracker.

## Contributing

Contributions are welcome! If you have improvements or fixes for the Hyper.js configuration or the theme, please fork the repository, make your changes, and submit a pull request.