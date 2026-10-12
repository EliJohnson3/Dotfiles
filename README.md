--Install Essentials
  
Sudo pacman -S git curl firefox brave btop proton-vpn-gtk-app mesa yazi steam kitty libre-office powertop ttf-jetbrains-mono-nerd spotify-launcher

--Yay

Sudo pacman -S --needed git base-devel

git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

--Spicetify

yay -S spicetify-cli

The spotify-launcher package installs Spotify to a user directory. Set the path in your config:

Terminal window
spicetify config spotify_path "$HOME/.local/share/spotify-launcher/install/usr/share/spotify"

