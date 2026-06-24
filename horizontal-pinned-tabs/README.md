# Horizontal Pinned Tabs

A Sine mod for Zen Browser that reorganizes the interface with a horizontal pinned tabs bar.

## Features

- **Horizontal Pinned Tabs Bar** — Fixed bar at the top of the window spanning full width
- **Vertical Sidebar** — Left side below the pinned tabs bar
- **Main Content Area** — Right side with no overlap with other elements
- **Clean Layout** — CSS Grid-based layout for precise positioning

## Installation

### Prerequisites

You must have [Sine](https://github.com/CosmoCreeper/Sine) installed to use this mod.

### Steps

1. Open Zen Browser
2. Go to Settings → Sine Mods
3. Enable "Download JS from unofficial sources" in Sine settings (gear icon below marketplace)
4. Below the marketplace, paste this repository link: `https://github.com/antajl/zen-mods`
5. The mod should install automatically
6. If Sine asks to restart, do that or go to `about:support` and click "Clear startup cache"

## Usage

After installation and restart:

1. Pin some tabs (right-click → Pin Tab)
2. Or add tabs to Essentials (right-click → Add to Essentials)
3. You'll see the horizontal bar at the top with pinned tabs
4. Vertical sidebar with regular tabs will be on the left
5. Main content will be on the right

## Customization

You can customize the mod by editing the CSS variables at the top of `HorizontalPinnedTabs.css`:

```css
:root {
  --zen-pinned-bar-height: 40px;      /* Height of pinned bar */
  --zen-sidebar-width: 250px;         /* Width of sidebar */
  --zen-pinned-bar-bg: var(--toolbar-bgcolor, #2b2a33);  /* Background color */
  --zen-pinned-bar-border: var(--chrome-content-separator-color, #52525e);  /* Border color */
}
```

## Behavior

- Tab labels are hidden by default for a cleaner look
- Labels appear on hover
- In fullscreen mode (F11), the pinned bar is automatically hidden
- Scrollbars are styled for consistency

## Compatibility

- Zen Browser 1.0.0+
- Works with Zen's vertical tabs
- May conflict with other layout-modifying mods

## Troubleshooting

**Mod not installing:**
- Ensure Sine is properly installed
- Check that "Download JS from unofficial sources" is enabled in Sine settings
- Verify the repository link is correct

**Styles not applying:**
- Restart the browser after installation
- Check if the mod is enabled in Sine Mods settings
- Try clearing startup cache (`about:support` → Clear startup cache)

## Credits

Created for Zen Browser using the Sine mod manager.

## License

This mod is provided as-is. Feel free to modify and distribute.
