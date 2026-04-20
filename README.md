# 🔴 Edric's Hyprland Setup — Red Glass Theme 

# **(Check hyprland.mp4 for demo)**

<p align="center">

<img src="https://img.shields.io/badge/OS-Fedora-blue?style=for-the-badge&logo=fedora">
<img src="https://img.shields.io/badge/WM-Hyprland-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Theme-Red%20Glass-darkred?style=for-the-badge">

</p>

<p align="center">
A custom <b>Hyprland-based Linux desktop setup</b> built on Fedora, featuring a <b>red & black glass aesthetic</b>, custom lockscreen styling, and SF Pro typography.
</p>

# ✨ Features

* 🔴 Red & Black themed UI
* 🧊 Glass-style blur effects
* 🔒 Custom Hyprlock lockscreen
* 🖋️ **SF Pro Display** typography
* 📊 Custom Waybar styling
* 🗂️ Nautilus as default file manager
* ⌨️ Custom keybindings
* 🎨 Flat Remix Red icon theme
* 🎵 Lockscreen music integration

---

# ⚙️ System Details

| Component        | Value                 |
| ---------------- | --------------------- |
| **OS**           | Fedora Linux          |
| **WM**           | Hyprland              |
| **Terminal**     | Kitty                 |
| **Bar**          | Waybar                |
| **Launcher**     | Rofi                  |
| **File Manager** | Nautilus              |
| **Fonts**        | SF Pro Display        |
| **Theme**        | Nightfox (Customized) |
| **Icons**        | Flat Remix Red        |

---

# 📁 Folder Structure

```bash
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
├── screenshots/
│   ├── desktop.png
│   ├── lockscreen.png
│   ├── waybar.png
│   └── hyprland.mp4
```

---

# 📥 Installation

⚠️ Recommended for users familiar with Hyprland.

## Clone Repository

```bash
git clone https://github.com/Edric2412/hyprland-dots.git
cd hyprland-dots
```

## Copy Configuration Files

```bash
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r kitty ~/.config/
cp -r rofi ~/.config/
```

## Reload Hyprland

```bash
hyprctl reload
```

---

# 🖋️ Fonts

This setup uses:

* **SF Pro Display**
* Nerd Fonts (for icons)

Install fonts before applying configuration.

---

# 🎨 Theme & Icons

Recommended:

* Nightfox GTK Theme
* Flat Remix Red Icons

---

# 🖼️ Wallpapers

Red/black aesthetic wallpapers included in:

```bash
wallpapers/
```

---

# ⌨️ Keybindings

| Shortcut          | Action               |
| ----------------- | -------------------- |
| **SUPER + A**     | Open Antigravity IDE |
| **SUPER + E**     | Open Nautilus        |
| **SUPER + ENTER** | Open Terminal        |
| **SUPER + D**     | Open Launcher        |

More bindings available in:

```bash
UserKeybinds.conf
```

---

# 🚧 Status

🛠️ Currently under active customization.

### Planned Improvements

* [ ] Glass-style UI refinements
* [ ] More lockscreen customization
* [ ] Dynamic color theming
* [ ] Improved blur tuning

---

# ⭐ Support

If you like this setup:

⭐ Star the repo
🍴 Fork it
🛠️ Customize it

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
