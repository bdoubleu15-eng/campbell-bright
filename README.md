# Campbell Bright

A vibrant, high-contrast terminal color scheme based on the classic Microsoft "Campbell" theme.

![Campbell Bright](https://placeholder-image-url-or-screenshot)

## Overview

**Campbell Bright** takes the sturdy, reliable foundation of the original Campbell scheme and amps up the saturation and brightness for a more modern, poppy terminal experience. It is designed to look great on high-DPI displays and pairs perfectly with bold fonts like **JetBrains Mono Nerd Font**.

## Content

- `campbell-bright.json`: The standalone color scheme definition.
- `terminal-settings.json`: A reference configuration showing how it's used with fonts and acrylic effects.

## Installation (Windows Terminal)

1. Open Windows Terminal settings ( `Ctrl` + `,` ).
2. Open the JSON file (click the "Open JSON file" icon in the bottom left).
3. Scroll to the `"schemes": []` array.
4. Paste the object from `campbell-bright.json` inside the array.
5. In your profile settings (e.g., "defaults" or specific profiles like "Ubuntu"), set:
   ```json
   "colorScheme": "Campbell Bright"
   ```

## Recommended Font Settings

This theme was developed with the following font settings in mind:

```json
"font": {
    "face": "JetBrainsMonoNL Nerd Font",
    "size": 14,
    "weight": "bold"
}
```

## Credits

- Based on the original [Campbell scheme](https://github.com/microsoft/terminal) by Microsoft.
- Customized by BWRIGHT.

## License

MIT License