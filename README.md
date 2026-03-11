
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
 ║  Side effects include: perfectionism, terminal addiction,     ║
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
| 🚀 **Shell** | zsh / fish *(pick your poison)* |
| 📊 **Status Bar** | Waybar — because plain taskbars are for cowards |
| 🚀 **Launcher** | Wofi / Rofi — summon apps like spells |
| 🔔 **Notifications** | Dunst / Mako — fancy little toasts |
| 🎨 **Color Scheme** | Catppuccin / Gruvbox *(vibes-based decision)* |

---

## 📁 REPO STRUCTURE

*organized chaos, emphasis on chaos*

```
~/.config/
├── 🌿 hypr/
│   ├── hyprland.conf          # the holy grail
│   ├── keybinds.conf          # my muscle memory
│   ├── animations.conf        # silky smooth magic
│   └── monitors.conf          # screen real estate
│
├── 🐱 kitty/
│   ├── kitty.conf             # terminal of the gods
│   └── themes/                # too many themes, no regrets
│
├── 🎵 cava/
│   └── config                 # bouncy bars go brrr
│
├── 📊 waybar/
│   ├── config                 # status bar sorcery
│   └── style.css              # css in my wm, yes really
│
├── 🚀 wofi/
│   ├── config                 # launcher config
│   └── style.css              # because it can be pretty
│
├── 🔔 dunst/
│   └── dunstrc                # notification therapy
│
└── 🐚 shell/
    ├── .zshrc                 # aliases upon aliases
    └── .aliases               # ls is now lsd and i refuse to apologize
```

---

## ⚡ INSTALLATION

> **WARNING:** This will obliterate your existing configs. Back up your stuff unless you enjoy pain.

### 🔧 The "I Trust Strangers on the Internet" Method

```bash
# Clone this beautiful disaster
git clone https://github.com/YOUR_USERNAME/dotfiles.git ~/.dotfiles

# Back up your existing configs (do this, seriously)
cp -r ~/.config ~/.config.bak

# Symlink everything with stow (the chad approach)
cd ~/.dotfiles
stow hypr kitty cava waybar wofi dunst
```

### 🛠️ Manual Method (for control freaks, respectfully)

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
sudo pacman -S hyprland waybar kitty wofi dunst

# Audio visualizer greatness  
sudo pacman -S cava

# Fonts (non-negotiable, your eyes deserve this)
sudo pacman -S ttf-jetbrains-mono-nerd ttf-font-awesome

# Nice to haves
sudo pacman -S swww               # wallpaper daemon
sudo pacman -S grim slurp         # screenshots
sudo pacman -S wl-clipboard       # clipboard
sudo pacman -S brightnessctl      # brightness control
sudo pacman -S playerctl          # media control
```

---

## ⌨️ KEYBINDS CHEATSHEET

*because future-me always forgets*

| Keys | Action |
|------|--------|
| `SUPER + Return` | Open terminal (Kitty) |
| `SUPER + D` | Open launcher (Wofi) |
| `SUPER + Q` | Kill focused window |
| `SUPER + F` | Fullscreen |
| `SUPER + V` | Toggle floating |
| `SUPER + [1-9]` | Switch workspace |
| `SUPER + SHIFT + [1-9]` | Move window to workspace |
| `SUPER + SHIFT + S` | Screenshot selection |
| `SUPER + L` | Lock screen |
| `SUPER + M` | Exit Hyprland (don't) |

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

## 🎵 CAVA CONFIG HIGHLIGHTS

*making your music visible since you installed this*

```ini
[general]
bars = 50
bar_width = 2
bar_spacing = 1

[color]
gradient = 1
gradient_count = 8
gradient_color_1 = '#CBA6F7'  # lavender
gradient_color_2 = '#89B4FA'  # blue
gradient_color_3 = '#A6E3A1'  # green
```

*Result: absolute cinema in your terminal*

---

## 🖼️ HYPRLAND ANIMATION CONFIG

*because smooth animations are a human right*

```ini
animations {
    enabled = yes
    bezier = overshot, 0.05, 0.9, 0.1, 1.05
    bezier = smoothOut, 0.36, 0, 0.66, -0.56
    bezier = smoothIn, 0.25, 1, 0.5, 1

    animation = windows, 1, 5, overshot, slide
    animation = windowsOut, 1, 4, smoothOut, slide
    animation = border, 1, 10, default
    animation = workspaces, 1, 6, smoothIn, slide
}
```

---

## 🤝 CONTRIBUTING / STEALING

See something you like? **Take it.** That's the Linux spirit. ✊

If you actually want to contribute improvements:

1. 🍴 Fork this repo
2. 🌿 Create a branch (`git checkout -b feature/even-more-rice`)
3. ✍️ Make your changes
4. 📬 Open a PR

---

## 🐛 KNOWN ISSUES

- [ ] Sometimes Hyprland crashes and I have no idea why *(it's fine)*
- [ ] CAVA occasionally seizes on bluetooth audio *(skill issue)*
- [ ] Waybar sometimes decides to not render icons *(vibes)*
- [ ] My screen randomly goes black *(touch grass, it fixes itself)*
- [ ] I keep adding new configs instead of finishing old ones

---

## 📜 LICENSE

Do whatever you want with this. It's dotfiles, not nuclear codes.

[WTFPL](http://www.wtfpl.net/) — *Do What The F\*ck You Want To Public License*

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
