# Always Visible Bookmarks Bar

A Sine mod for Zen Browser that makes the bookmarks bar always visible in Single Toolbar Layout.

## Features

- **Always Visible** — Bookmarks bar stays visible instead of hiding until hover
- **Single Toolbar Layout** — Works with Zen's default Single Toolbar layout
- **Minimal Changes** — Only 2 CSS rules, safe and conservative approach
- **No Layout Breaks** — Does not modify browser structure or layout

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

1. Make sure you're using Single Toolbar Layout (Zen's default)
2. The bookmarks bar will now stay visible at all times
3. No need to hover at the edge of the browser to show it

## How It Works

This mod forces the bookmarks bar to be visible by:
1. Setting `height: var(--zen-toolbar-height)` on the navbar container
2. Setting `opacity: 1` on both the navbar container and PersonalToolbar

This overrides Zen's default hover-to-show behavior in Single Toolbar Layout while keeping all toolbar functionality intact.

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
