
![The lucid UI 4 icon](lucidui4-1-icon.png)
# LucidUI
(Formerly Hyprlucid)
## Note
LucidUI 4.1 will release soon, it will upgrade LucidUI to Lua\
4.1 will be the last release of LucidUI
## Supported distros
Arch/Arch based `works perfectly`\
Artix `mostly fine but things regarding power/reboot/sleep need tweaking`\
NixOS `works decently`\
Debian/Ubuntu based `Unsupported`
## Pre-Installation
The following tools are required for lucidUI\
Please make sure they're installed before doing anything\
```
fastfetch
hyprland
hyprpaper
hyprlock
hyprshot
kitty
swaync
pywal
python
waybar
wlogout
wofi
Nautilus
firefox
```
The following fonts are also required\
[Google Sans Flex](https://fonts.google.com/specimen/Google+Sans+Flex)\
[JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/JetBrainsMono.zip)
<details>
  <summary>List of packages for NixOS users</summary>
  
  NixOS users can paste this into their configuration.nix
```
fish
fastfetch
python3
python3Packages.pywal
hyprland
waybar
wofi
kitty
hyprpaper
hyprshot
hyprlock
imagemagick
wlogout
git
swaynotificationcenter
libnotify
nautilus
firefox
```
</details>

## Installation
Now that you've installed all the needed tools\
Download your preferred version of LucidUI and copy the following folders to their respective locations\
copy `Wallpaper` into `~/`\
copy `bibata` into `~/.icons/`\
copy everything else into `~/.config/`

## Keybinds
When using LucidUI, it is important to learn these keybinds\
`SUPER + Q: Terminal`\
`SUPER + W: File Manager`\
`SUPER + E: Browser (Firefox)`\
\
`SUPER + SPACE: Launcher`\
`ALT + [Number]: Switches to that workspace`\
`ALT + LEFT: Switches to the previous workspace`\
`ALT + RIGHT: Switches to the next workspace`\
`ALT + F: Fullscreen`\
\
`SUPER + 1: Close`\
`SUPER + 0: Exit`\
`CTRL + ALT + DEL: Logout Menu`\
