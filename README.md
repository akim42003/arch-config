## Hyprland Dotfiles

Arch Linux + Hyprland setup

## Core

- **Hyprland** - Wayland compositor
- **Waybar** - Status bar
- **Hyprlock** - Lock screen
- **Hyprpaper** - Wallpaper

## Apps

- **Hyprlauncher** - Application launcher
- **Dolphin** - File manager
- **Cava** - Audio visualizer
- **SwayNC** - Notifications

## Utilities

- **swww** - Animated wallpaper transitions
- **Matugen** - Material You color generation
- **Network Manager Applet** - WiFi management
- **Grim / Slurp** - Screenshots

## Login

TTY autologin → Hyprland (no display manager)

## Fonts

- JetBrains Mono Nerd Font
- Noto Fonts + Emoji

## Install
```bash
# Official repos
sudo pacman -S hyprland waybar hyprlock hyprpaper thunar cava swaync \
  grim slurp wl-clipboard matugen network-manager-applet \
  ttf-jetbrains-mono-nerd noto-fonts noto-fonts-emoji

# AUR
yay -S hyprlauncher swww
``` arch-config
# arch-config
