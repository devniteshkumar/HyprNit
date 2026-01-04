# HyprNit - Dotfiles and Configs

This repo contains configuration files for Hyprland, Waybar, Rofi, Kitty and related Wayland utilities.

## Overview
- Hyprland config: `hypr/hyprland.conf` and `hypr/modules/`
- Waybar: `waybar/` (includes `launch.sh`)
- Rofi themes and launchers: `rofi/launchers/`
- Kitty: `kitty/kitty.conf`
- SwayNC: `swaync/`

## External Dependencies
These configs rely on a set of common Wayland utilities. Install at least the following:

- Hyprland (Wayland compositor)
- wlroots (Wayland compositor library)
- waybar
- swaync
- swww
- rofi
- kitty
- grim (screenshot tool)
- slurp (region selector)
- wl-clipboard (`wl-copy` / `wl-paste`)
- playerctl (media control)
- pamixer or `pactl` (audio control)

## Quick install
The simplest way is to copy or symlink the folders into `~/.config`:

```bash
mkdir -p ~/.config
cp -r hypr ~/.config/hypr
cp -r waybar ~/.config/waybar
cp -r rofi ~/.config/rofi
cp -r kitty ~/.config/kitty
cp -r swaync ~/.config/swaync
# Make launch scripts executable
chmod +x ~/.config/waybar/launch.sh
```

Or create symlinks (preferred for dotfile management):

```bash
ln -s $(pwd)/hypr ~/.config/hypr
ln -s $(pwd)/waybar ~/.config/waybar
ln -s $(pwd)/rofi ~/.config/rofi
ln -s $(pwd)/kitty ~/.config/kitty
ln -s $(pwd)/swaync ~/.config/swaync
```

## Themes
- Bibata Modern Ice Cursor
- Papirus Icon Theme
- Adwaita Dark