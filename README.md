--Install Essentials
  
Sudo pacman -S git curl firefox brave btop proton-vpn-gtk-app networkmanager mesa yazi steam kitty libre-office powertop

--Yay

Sudo pacman -S --needed git base-devel

git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

--Spicetify

yay -S spotify spicetify-cli

sudo chmod a+wr /opt/spotify

sudo chmod a+wr /opt/spotify/Apps -R
