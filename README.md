# ubuntu-setup-with-gruvybox
This is my Ubuntu 22.04 setup basic iwith gruvybox

![screenshot](screenshots/dirty.png)

# dotfiles

A collection of my configuration and other dotfiles.

* Ubuntu 22.04 minimal

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
