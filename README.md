# Ariv Themes

A free, modern dark theme alternative to Vira/Material Themes.

## Recommended Settings

To get the best experience from the Ariv themes, we highly recommend enabling bracket pair colorization, vertical guides, and the **Fira Code** font for beautiful ligatures.

Here is how to set up your environment for the best experience:

1. **Install Fira Code**: Download and install the [Fira Code font](https://github.com/tonsky/FiraCode) on your system if you haven't already.
2. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
3. Search for and select **Preferences: Open User Settings (JSON)**.
4. Add the following lines to your configuration:

```json
  "editor.fontFamily": "'Fira Code', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active"
```

*(Setting `editor.guides.bracketPairs` to `"active"` will highlight the specific block your cursor is currently inside. Setting it to `true` will show the colored lines for all nested blocks at all times).*

### Theme-Specific Settings (Optional)
If you only want these settings applied when using the Ariv themes, you can use a theme-specific configuration block in your `settings.json`:

```json
  "[Ariv Dark]": {
    "editor.fontFamily": "'Fira Code', Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active"
  },
  "[Ariv Ocean]": {
    "editor.fontFamily": "'Fira Code', Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active"
  }
```

## Enjoy!
