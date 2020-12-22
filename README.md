# My purple setup

This is meant for `r/unixp*n`, and as a backup of my settings.

## Content

* [How it looks](#how-it-looks)
* [Themes](#themes)
* [Gnome Extensions](#gnome-extensions)
* [Background](#background)
* [Terminal](#terminal)
* [Shell](#shell)

## How it looks

![Setup](https://raw.githubusercontent.com/zastrixarundell/purple_setup/main/my_setup.png)

## Themes

* Applications: [Layan-dark-solid](https://www.gnome-look.org/p/1309214/)
* Cursor: Yaru
* Icons: [Papirus-Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
* Shell: [Layan-dark-solid](https://www.gnome-look.org/p/1309214/)
Sound: Yaru

## Gnome Extensions

* [Dynamic panel transparency](https://extensions.gnome.org/extension/1011/dynamic-panel-transparency/) with custom background color to color of theme bar
* [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)
* [Netspeed](https://extensions.gnome.org/extension/104/netspeed/)
* [User themes](https://extensions.gnome.org/extension/19/user-themes/)

## Background

![Beach](https://raw.githubusercontent.com/zastrixarundell/purple_setup/main/beach.jpg)

## Terminal

The terminal I use is `tilix`. I installed via `sudo apt-get instal tilix`.

## Shell

I'm using `zsh`/`oh-my-zsh` with [`powerlevel10k`](https://github.com/romkatv/powerlevel10k)

## Neofetch

To setup how I use neofetch:

```bash
sudo mkdir /usr/share/neofetch_ascii
sudo cp ./cat.txt /usr/share/neofetch_ascii/cat.txt
echo 'neofetch --ascii_colors 16 243 237 177 7 e --ascii /usr/share/neofetch_ascii/cat.txt' >> ~/.zshrc
```

## Music visualizer

For music I'm using [vis](https://github.com/dpayne/cli-visualizer)

There's a settings file in the repo.

## VScode theme

```
Name: Ariake Dark
Id: wart.ariake-dark
Description: Dark VSCode theme inspired by Japanese traditional colors and the poetry composed 1000 years ago
Version: 0.2.2
Publisher: wart
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=wart.ariake-dark
```