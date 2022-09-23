# ubuntu-setup-with-I3
This is my Ubuntu 22.04 setup with i3-wm and guvbox

![screenshot](screenshots/dirty.png)

# dotfiles

A collection of my configuration and other dotfiles.

* Ubuntu 22.04 minimal + i3-wm

## Start theme configurate

```bash
sudo add-apt-repository universe
# install gnome tweaks
sudo apt install gnome-tweak-tool
# start gnome tweaks
gnome-tweaks
# Copy .themes and .icons and paste in your home
```


Create a folder ".themes" in your home and extract this file there
[Gruvbox GTK Theme](https://www.gnome-look.org/p/1681313)

Create a folder ".icons" in your home and extract this file there
[Gruvbox icon theme](https://www.gnome-look.org/p/1327720/)

go to tweaks -> appearance and set gruvybox-Dark-BL to "applications" and gruvybox to "icons"

## Things to install

```bash
sudo apt install i3-wm
sudo apt install i3-status
sudo apt install i3-block
sudo apt-get -y install polybar
sudo apt install dmenu j4-dmenu-desktop
sudo apt install neofetch

python3 -m pip install --user pipx
python3 -m pipx ensurepath
```