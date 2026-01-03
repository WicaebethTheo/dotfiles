# Dotfiles

My personal dotfiles for CachyOS with Hyprland.

## 🖥️ Stack

- **OS**: CachyOS
- **WM**: [Hyprland](https://hyprland.org/)
- **Terminal**: [Kitty](https://sw.kovidgoyal.net/kitty/)
- **Shell**: [Fish](https://fishshell.com/)
- **Fetch**: [Fastfetch](https://github.com/fastfetch-cli/fastfetch)

## 📁 Structure

```
dotfiles/
├── fastfetch/     # System info display config
├── fish/          # Fish shell config
├── hypr/          # Hyprland window manager config
│   ├── hyprland.conf      # Main config (sources others)
│   ├── monitors.conf      # Monitor setup
│   ├── programs.conf      # Default programs
│   ├── autostart.conf     # Startup applications
│   ├── env.conf           # Environment variables
│   ├── appearance.conf    # Theming & visuals
│   ├── input.conf         # Keyboard/mouse settings
│   ├── keybinds.conf      # Keyboard shortcuts
│   └── windowrules.conf   # Window rules
└── kitty/         # Kitty terminal config
```

## ⚙️ Installation

Clone and symlink to `~/.config/`:

```bash
git clone https://github.com/WicaebethTheo/dotfiles.git ~/dotfiles

# Symlink configs
ln -sf ~/dotfiles/hypr ~/.config/hypr
ln -sf ~/dotfiles/kitty ~/.config/kitty
ln -sf ~/dotfiles/fish ~/.config/fish
ln -sf ~/dotfiles/fastfetch ~/.config/fastfetch
```

## 🎨 Kitty Theme

- Font: **FiraCode Nerd Font**
- Theme: **Oxocarbon**
- Opacity: 80%

## ⌨️ Kitty Keybinds

| Keybind | Action |
|---------|--------|
| `Ctrl+T` | New tab |
| `Ctrl+Shift+W` | Close tab |
| `Ctrl+Enter` | New window |
| `Ctrl+Shift+L/H` | Next/Previous window |
| `Ctrl+Shift+C/V` | Copy/Paste |
