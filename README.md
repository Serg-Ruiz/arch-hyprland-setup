# arch-hyprland-setup

# install programs
pacman -S hypridle hyprlock hyprpaper swaync xorg-xhost timeshift firefox neovim waybar cliphist kvantum nwg-look qt6ct qt5ct tmux rofi zsh 

# install yay

git clone https://aur.archlinux.org/yay.git

cd yay

makepkg -si

# aur packages

yay -S ttf-jetbrains-mono-nerd dracula-gtk-theme bibata-cursor-theme vesktop-bin vesktop-bin visuaul-studio-code-bin pwvucontrol goxlr-utility


# move rofi themes to correct location

  sudo mv tokyonight.rasi /usr/share/rofi/themes
  sudo mv tokyonight_big1.rasi /usr/share/rofi/themes
  sudo mv tokyonight_big2.rasi /usr/share/rofi/themes

# change shell to zsh 

chsh -s /bin/zsh

mv .poshthemes/ /home/s321w1/