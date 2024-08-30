# NauseaSB dotfiles Config

Hi, welcome to my dotfiles github!

## Basic information (things needed)

- wm : i3
- os : arch
- shell : zsh
- terminal : alacritty
- launcher : rofi
- imageviewer : feh/gwenview
- compositor : picom
- statusbar : polybar
- filemanager : ranger/dolphin
- texteditor : nvim/kate (for vim config i usually use [nvchad](https://nvchad.com/) (i also still new to vim/nvim so i still learning and barely used it, mainly still using kate))
- fonts : hack, jetbrains mono, feather, inconsolata, liberation (which you can find most of them [here](https://www.nerdfonts.com/), but i mostly only use hack)

## Preview
![screen](/img/1.png)
![screen](/img/2.png)
![screen](/img/3.png)
![screen](/img/4.png)
![screen](/img/5.png)

## Installation

```bash
sudo pacman -S zsh alacritty rofi feh gwenview picom polybar ranger dolphin nvim flameshot stow
```

```bash
yay -S rofi-power-menu oh-my-zsh-git autotiling-git
```

to copy the files to certain config file you can use stow, example:


```bash
stow i3
```

this command will automatically copy this i3 config file to your config folder.


## Additional information
- my rofi theme can be found in (it is actually normal theme but applied with catppuccin mocha color palette!)
```
.local/share/rofi/themes/nausea.rasi
```
- i still use kde aside i3 so for theme i used in kde basically just catppuccin mocha
- for spicetify theme i use comfy theme and the color scheme set to catppuccin mocha
- for sddm theme i use catppuccin you can get it [here](https://github.com/catppuccin/sddm)

> [!IMPORTANT]
> this github repo is still in WIP status. so it will be updated or deleted at anytime.
