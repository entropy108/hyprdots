
<div align="center">

```
                   ██████╗  ██████╗ ████████╗███████╗██╗██╗     ███████╗███████╗
                   ██╔══██╗██╔═══██╗╚══██╔══╝██╔════╝██║██║     ██╔════╝██╔════╝
                   ██║  ██║██║   ██║   ██║   █████╗  ██║██║     █████╗  ███████╗
                   ██║  ██║██║   ██║   ██║   ██╔══╝  ██║██║     ██╔══╝  ╚════██║
                   ██████╔╝╚██████╔╝   ██║   ██║     ██║███████╗███████╗███████║
                   ╚═════╝  ╚═════╝    ╚═╝   ╚═╝     ╚═╝╚══════╝╚══════╝╚══════╝
```

### 🌸 *my chaotic beautiful arch + hyprland rice* 🌸

![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Hyprland](https://img.shields.io/badge/Hyprland-58E1FF?style=for-the-badge&logo=wayland&logoColor=black)
![Wayland](https://img.shields.io/badge/Wayland-FFBA08?style=for-the-badge&logo=wayland&logoColor=black)
![Kitty](https://img.shields.io/badge/Kitty_Terminal-F5B0CB?style=for-the-badge&logo=gnome-terminal&logoColor=black)
![Maintained](https://img.shields.io/badge/maintained-obsessively-FF6B9D?style=for-the-badge)

<br>

> *"I use Arch, btw."* — me, constantly, unprompted

</div>

---

<div align="center">

## ✨ WELCOME TO MY DOTFILE DUNGEON ✨

*where configs go to become art and productivity is optional*

</div>

```
 ╔═══════════════════════════════════════════════════════════════╗
 ║  WARNING: Entering this repo may cause uncontrollable urges   ║
 ║  to rice your desktop for 6 hours instead of doing work.      ║
 ║  Side effects include: perfectionism, terminal addiction,      ║
 ║  and saying "btw I use Arch" in casual conversation.          ║
 ╚═══════════════════════════════════════════════════════════════╝
```

---

## 🎨 THE SETUP

| 💻 Component | 🔧 Tool |
|---|---|
| 🪟 **Window Manager** | [Hyprland](https://hyprland.org/) — silky smooth Wayland compositor |
| 🖥️ **Terminal** | [Kitty](https://sw.kovidgoyal.net/kitty/) — the fast, featureful GPU terminal |
| 🎵 **Audio Visualizer** | [CAVA](https://github.com/karlstav/cava) — console-based audio visualizer |
| 🚀 **Shell** | zsh *(THE BEST SHELL)* |
| 📊 **Status Bar** | Waybar — because plain taskbars are for cowards |
| 🚀 **Launcher** | Rofi — summon apps like spells |
| 🔔 **Notifications** | Dunst — fancy little toasts |
| 💻 **File Manager** | Yazi — Pure Satisfaction |


---

## ⚡ INSTALLATION

### 🛠️ Manual Method 

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/dotfiles.git

# Copy what you want, piece by piece
cp -r dotfiles/.config/hypr ~/.config/hypr
cp -r dotfiles/.config/kitty ~/.config/kitty
cp -r dotfiles/.config/cava ~/.config/cava
# ... and so on
```

### 📦 Dependencies (the shopping list)

```bash
# Core chaos
sudo pacman -S hyprland waybar kitty wofi swaync

# Audio visualizer greatness  
sudo pacman -S cava

# Nice to haves
sudo pacman -S swww               # wallpaper daemon
sudo pacman -S grim slurp         # screenshots
sudo pacman -S wl-clipboard       # clipboard
sudo pacman -S brightnessctl      # brightness control
sudo pacman -S playerctl          # media control
```

---

## ⌨️ KEYBINDS 

*because future-me always forgets*

| Keys | Action |
|------|--------|
| `SUPER + Return` | Open terminal (Kitty) |
| `SUPER + SPACE` | Open launcher (Wofi) |
| `SUPER + Q` | Kill focused window |
| `SUPER + F` | Fullscreen |
| `SUPER + T` | Toggle floating |
| `SUPER + [1-9]` | Switch workspace |
| `SUPER + SHIFT + [1-9]` | Move window to workspace |
| `SUPER + SHIFT + S` | Screenshot selection |
| `SUPER + L` | Lock screen |

---

## 🌈 COLORSCHEME

> *"A colorscheme isn't just colors, it's a lifestyle."*

Currently rocking **Catppuccin Mocha** 🐱

```
 Background  #1E1E2E  ████  cozy dark cave
 Surface     #313244  ████  slightly less dark cave
 Primary     #CBA6F7  ████  lavender dreams
 Secondary   #89B4FA  ████  soft blue sky
 Green       #A6E3A1  ████  minty fresh
 Red         #F38BA8  ████  pastel panic
 Yellow      #F9E2AF  ████  warm butter
 Peach       #FAB387  ████  sunset feels
```

---

<div align="center">

### 🌟 ACKNOWLEDGEMENTS

*standing on the shoulders of ricing giants*

Huge thanks to the legends at **r/unixporn**, the **Hyprland Discord**, and every person who ever posted their dotfiles publicly and let strangers like me steal from them.

<br>

**[⭐ Star this repo if it helped you]** • **[🐛 Open an issue if something's broken]** • **[🍴 Fork it and make it yours]**

<br>

```
                     made with ♥, caffeine, and an unhealthy amount of time
                           in the terminal instead of touching grass
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.dotfiles)

</div>
