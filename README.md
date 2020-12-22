# My purple setup

This is meant for `r/unixp*n`, and as a backup of my settings.

## Themes

* Applications: [Layan-dark-solid](https://www.gnome-look.org/p/1309214/)
* Cursor: Yaru
* Icons: [Papirus-Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
* Shell: [Layan-dark-solid](https://www.gnome-look.org/p/1309214/)
Sound: Yaru

## GNOME Extensions

* [Dynamic panel transparency](https://extensions.gnome.org/extension/1011/dynamic-panel-transparency/) with custom background color to color of theme bar
* [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)
* [Netspeed](https://extensions.gnome.org/extension/104/netspeed/)
* [User themes](https://extensions.gnome.org/extension/19/user-themes/)

## Terminal

The terminal I use is `tilix`. I installed via `sudo apt-get instal tilix`.

## Background

![Background](https://lunawood.com/wp-content/uploads/2018/02/placeholder-image.png)

## Neofetch

To setup how I use neofetch:

```bash
sudo mkdir /usr/share/neofetch_ascii
sudo cp ./cat.txt /usr/share/neofetch_ascii/cat.txt
echo 'neofetch --ascii_colors 16 243 237 177 7 e --ascii /usr/share/neofetch_ascii/cat.txt' >> ~/.zshrc
```
