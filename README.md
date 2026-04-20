# 🔴 Edric's Hyprland Setup — Red Glass Theme

A custom **Hyprland-based Linux desktop setup** built on Fedora, featuring a **red and black aesthetic**, custom lockscreen styling, and SF Pro typography.

This setup is inspired by modern UI design principles — focusing on **clarity, minimalism, and glass-style visuals**.

---

# 🖥️ Preview

## Desktop

*(Add screenshot here)*

## Lockscreen

*(Add screenshot here)*

## Waybar

*(Add screenshot here)*

---

# ✨ Features

* 🔴 Red & Black themed UI
* 🧊 Glass-style blur effects
* 🔒 Custom Hyprlock lockscreen
* 🖋️ **SF Pro Display** font integration
* 📊 Custom Waybar styling
* 🗂️ Nautilus as default file manager
* ⌨️ Custom keybindings
* 🎨 Flat Remix Red icon theme
* 🎵 Lockscreen music integration

---

# ⚙️ System Details

| Component    | Value                 |
| ------------ | --------------------- |
| OS           | Fedora Linux          |
| WM           | Hyprland              |
| Terminal     | Kitty                 |
| Bar          | Waybar                |
| Launcher     | Rofi                  |
| File Manager | Nautilus              |
| Fonts        | SF Pro Display        |
| Theme        | Nightfox (Customized) |
| Icons        | Flat Remix Red        |

---

# 📁 Folder Structure

```
hyprland-dots/
├── hypr/
│   ├── hyprland.conf
│   ├── hyprlock.conf
│   ├── hypridle.conf
│   └── scripts/
│
├── waybar/
│   ├── config
│   └── style.css
│
├── kitty/
│   └── kitty.conf
│
├── rofi/
│   └── config.rasi
│
├── wallpapers/
│
└── screenshots/
```

---

# 📥 Installation

⚠️ Recommended for users familiar with Hyprland.

Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/hyprland-dots.git
```

Copy configuration files:

```
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r kitty ~/.config/
cp -r rofi ~/.config/
```

Reload Hyprland:

```
hyprctl reload
```

---

# 🖋️ Fonts

This setup uses:

* **SF Pro Display**
* Nerd Fonts (for icons)

Install fonts before using the configuration.

---

# 🎨 Theme & Icons

Recommended:

* Nightfox GTK Theme
* Flat Remix Red Icons

---

# 🖼️ Wallpapers

Red/black aesthetic wallpapers included in:

```
wallpapers/
```

---

# ⌨️ Keybindings

| Shortcut      | Action               |
| ------------- | -------------------- |
| SUPER + A     | Open Antigravity IDE |
| SUPER + E     | Open Nautilus        |
| SUPER + ENTER | Open Terminal        |
| SUPER + D     | Open Launcher        |

More bindings available in:

```
UserKeybinds.conf
```

---

# 🚧 Status

Currently under active customization.

Planned improvements:

* [ ] Glass-style UI refinements
* [ ] More lockscreen customization
* [ ] Dynamic color theming
* [ ] Improved blur tuning

---

# 🙏 Credits

Inspired by:

* JaKooLit Hyprland setup
* Hyprland community themes
* Modern UI design trends

---

# 📜 License

Free to use and modify.

If you use this setup, a star ⭐ would be appreciated.
