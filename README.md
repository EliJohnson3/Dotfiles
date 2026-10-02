--Install Essentials
  
Sudo pacman -S git curl firefox brave btop proton-vpn-gtk-app networkmanager mesa yazi steam kitty

yay -S spotify spicetify-cli

--Yay

Sudo pacman -S --needed git base-devel
it clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si

--Spicetify

sudo chmod a+wr /opt/spotify
sudo chmod a+wr /opt/spotify/Apps -R
