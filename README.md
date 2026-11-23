# Hyprism Pixie SDDM

This repository is the Hyprism-maintained Qt 6 fork of [Pixie SDDM](https://github.com/xCaptaiN09/pixie-sddm). It is based on upstream commit `1e1a863761f742e8d509d569382b17c112e29fdc` and retains the original Pixie MIT license and notices.

The theme is designed to be vendored at `themes/hyprism-pixie/` in [Hyprism](https://github.com/kristyancarvalho/hyprism). Hyprism generates `theme.conf` and `/var/lib/hyprism/sddm/current-wallpaper.jpg`, installs the theme and its Qt 6 dependencies, and configures the virtual keyboard. Use the Hyprism installer to install or update it; do not install this repository directly.

The theme retains Pixie's stacked clock, wallpaper presentation, user avatar and session selector, rounded login card, transitions, and power controls. Hyprism-specific changes supply the active palette, synchronized wallpaper, session logos, and visible Qt Quick Virtual Keyboard. The password field and login button share one horizontal row and the same height.

For provenance, bundled logo sources, and license details, see [ORIGIN.md](ORIGIN.md). Preview the installed theme from an active desktop session with:

```bash
sddm-greeter-qt6 --test-mode --theme /usr/share/sddm/themes/hyprism-pixie
```
