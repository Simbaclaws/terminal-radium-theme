# Radium Theme for Microsoft Terminal

This directory contains the Radium theme configuration for Microsoft Terminal, a modern, fast, efficient, and powerful terminal application for users of command-line tools and shells like Command Prompt, PowerShell, and WSL (Windows Subsystem for Linux). Follow these instructions to apply the Radium theme to your Microsoft Terminal.

## Installation Instructions

### Step 1: Clone the Repository

Ensure you have the latest version of the theme files:
```bash
git clone https://github.com/simbaclaws/terminal-radium-theme.git
cd terminal-radium-theme/MicrosoftTerminal
```
### Step 2: Update Microsoft Terminal Configuration

Microsoft Terminal uses a JSON configuration file, which can be accessed directly through the terminal settings UI.

1. Open Microsoft Terminal.
2. Click on the dropdown arrow next to the tabs and select Settings. This opens the `settings.json` file in your default JSON editor.
3. Integrate the Radium theme colors into your settings. Below is the JSON snippet to add under the profiles section in the list of schemes:

```JSON
{
  name: Radium,
  background: #101317,
  foreground: #d4d4d5,
  cursorColor: #d4d4d5,
  black: #0a0d11,
  red: #f87070,
  green: #37d99e,
  yellow: #ffe59e,
  blue: #7ab0df,
  magenta: #c397d8,
  cyan: #50cad2,
  white: #525559,
  brightBlack: #191d22,
  brightRed: #ff8e8e,
  brightGreen: #79dcaa,
  brightYellow: #ffeda6,
  brightBlue: #87bdec,
  brightMagenta: #b68acb,
  brightCyan: #63b3ad,
  brightWhite: #d4d4d5
}
```
4. Save the changes to `settings.json` and restart Microsoft Terminal to see the Radium theme in action.

### Step 3: Verify the Changes

Reopen Microsoft Terminal and open a new tab to see if the Radium theme colors are applied correctly. You should notice the change immediately in the appearance of the terminal.

## Customization

If you would like to further customize the terminal colors or settings:

- You can modify the color values or any additional settings like font or cursor style in the same `settings.json` file.
- Microsoft Terminal allows for customization of each terminal profile individually, so you can apply the Radium theme selectively to different profiles.

## Support

For more help or to report issues related to the Microsoft Terminal configuration, feel free to submit issues directly to the GitHub repository at:

https://github.com/simbaclaws/terminal-radium-theme/issues

## Contributing

Contributions to enhance or expand the Radium theme across different platforms and terminals are welcome! If you have improvements or additional themes, please fork the repository, make your changes, and submit a pull request detailing your contributions.

Thank you for using the Radium theme for Microsoft Terminal!