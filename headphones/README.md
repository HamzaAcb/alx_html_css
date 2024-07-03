# Headphones Web Page Project

This project is a responsive web page design for headphones, created using HTML and CSS. The design details and assets are provided in a Figma file.

## Table of Contents
- [Figma Access](#figma-access)
- [Important Notes](#important-notes)
- [Fonts](#fonts)
- [Responsive Design](#responsive-design)
- [Interactions](#interactions)
- [Max Width](#max-width)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Figma Access
To access the design details, create an account in Figma and duplicate the project to your drafts. If you can’t access it, use the Figma file provided:

- [Figma File](https://www.figma.com/file/YOUR-FIGMA-FILE-LINK)

## Important Notes
- If your computer doesn’t have the fonts used in this project, you can download and install them:
  - [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
  - [Spin Cycle OT](https://example.com/spin-cycle-ot) (Provide the correct link here)
- Some values are in float - feel free to round them.

## Fonts
To ensure the correct display of fonts, install the following:
- **Source Sans Pro:** [Download from Google Fonts](https://fonts.google.com/specimen/Source+Sans+Pro)
- **Spin Cycle OT:** [Download from Example.com](https://example.com/spin-cycle-ot) (Provide the correct link here)

### Installing Fonts on Your System

#### Windows
1. Download the font files.
2. Extract the files if they are in a zip format.
3. Right-click on each font file and select "Install".

#### macOS
1. Download the font files.
2. Extract the files if they are in a zip format.
3. Double-click on each font file and click "Install Font" in the preview window.

### Using the Fonts in VS Code
1. Open VS Code.
2. Access `settings.json` via the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`), then type `Preferences: Open Settings (JSON)`.
3. Add the following to `settings.json`:
    ```json
    {
      "editor.fontFamily": "'Source Sans Pro', 'Spin Cycle OT', 'Courier New', monospace",
      "editor.fontSize": 14,
      "editor.lineHeight": 20
    }
    ```
4. Save the file and restart VS Code.

## Responsive Design
The web page is designed to be responsive and will switch to the mobile version when the screen width is 480px or less.

### Media Queries
```css
/* For screens 480px or narrower */
@media (max-width: 480px) {
  /* Add your responsive styles here */
}