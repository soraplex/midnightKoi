# midnight-koi

a tranquil and calming theme designed for developers who prefer a dark interface while coding. This theme aims to reduce eye strain and enhance focus, providing a peaceful coding environment.

### Features

- Calming Color Palette: Soft colors that are easy on the eyes.
- Syntax Highlighting: Clear and distinct highlighting for various programming languages.
- Minimalistic Design: A clean and uncluttered interface to help you concentrate on your code.
- Customizable: Easily adjustable settings to fit your personal preferences.

### Customization

You can further customize the theme by modifying your settings in settings.json. For example, you can adjust the font size, line height, and other editor settings to enhance your experience.

## Bracket Color Setup (Recommended)

This theme uses a custom bracket‑color palette for improved readability.  
VS Code does not allow themes to define bracket highlight colors directly,  
so you must add them to your user settings.

### Step 1 — Open Your VS Code Settings (JSON)

1. Open VS Code
2. Press Ctrl + Shift + P
3. Type: Preferences: Open Settings (JSON)
4. Select it

### Step 2 — Add the Bracket Highlight Colors

Paste this into your settings.json:

```json
"workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#D7C27A",
    "editorBracketHighlight.foreground2": "#76baa8",
    "editorBracketHighlight.foreground3": "#aa9061",
    "editorBracketHighlight.foreground4": "#7f9fc4",
    "editorBracketHighlight.foreground5": "#9fc47f",
    "editorBracketHighlight.foreground6": "#c47f7f",

    "editorBracketHighlight.unexpectedBracket.foreground": "#c47f7f"
}
```

### Step 3 — Ensure Bracket Pair Colorization Is Enabled

Add this if it is not already enabled:

```json
"editor.bracketPairColorization.enabled": true
```

### Done!

Your brackets will now use the same color system the theme was designed around.

## React example

![React](img/React.png)

## Javascript Example

![Javascript](img/Javascript.png)

## Python Example

![Python](img/Python.png)

## HTML Example

![HTML](img/HTML.png)

## CSS Example

![CSS](img/HTML.png)

## README Example

![README](img/README.png)
