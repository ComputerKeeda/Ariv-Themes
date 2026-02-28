# Ariv Themes

A free, modern dark theme alternative to Vira/Material Themes.

## Recommended Settings

To get the best experience from the Ariv themes, we highly recommend enabling bracket pair colorization and guides. By default, VS Code has bracket pair colorization enabled, but the vertical guides (the connecting lines) are often turned off or set to only show horizontal lines.

Here is how to activate them so you can see your new Ariv theme colors in action:

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
2. Search for and select **Preferences: Open User Settings (JSON)**.
3. Add the following lines to your configuration:

```json
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active"
```

*(Setting `editor.guides.bracketPairs` to `"active"` will highlight the specific block your cursor is currently inside. Setting it to `true` will show the colored lines for all nested blocks at all times).*

### Theme-Specific Settings (Optional)
If you only want these settings applied when using the Ariv themes, you can use a theme-specific configuration block in your `settings.json`:

```json
  "[Ariv Dark]": {
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active"
  },
  "[Ariv Ocean]": {
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": "active"
  }
```

## Enjoy!
