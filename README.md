# dots
My river dotfiles

#                                                                                        Getting started (?)

On artix you should install the archlinux-keyring package and enable the extra repository to get some stuff to work

On void install all repos except debug (or not your choice) for unfree stuff if that will ever be there
#
    sudo xbps-install void-repo-nonfree void-repo-multilib void-repo-multilib-nonfree

On gentoo enable the guru repository for some extra stuff

    sudo emerge eselect-repository
    sudo eselect-repository enable guru
    emaint sync

#                                                                                        Screenshots



![screenshot](https://github.com/user-attachments/assets/8e89110a-c8fd-4922-a304-4084447597f4)



![screenshot](https://github.com/user-attachments/assets/a556dc25-21de-4feb-84c5-1d0677080536)



#                                                                                        Requirements:

    Pipewire, wireplumber, pipewire-pulse pipewire-session-manager 

    xdg-desktop-portal (-wlr -kde -hyprland)

    river swww rofi waybar pywal thunar kitty floorp 

    git make cmake curl

   An aur helper such as yay or paru is also recommended if using arch based distros





#                                                                                         Optional:

    vesktop, lyssa, dunst, flatpak, grim and slurp

#                                                                                        Installation

Arch:
      
    paru -S pipewire wireplumber pipewire-pulse pipewire-session-manager xdg-desktop-portal-wlr xdg-desktop-portal-hyprland xdg-desktop-portal-kde xdg-desktop-portal river swww rofi-wayland waybar dunst pywal thunar kitty floorp git make cmake curl
    
Artix:

    on artix its the same as arch but pipewire, wireplumber, pipewire-pulse are suffixed by your init "pipewire-openrc" as example 
ps: make sure to have extra repository enabled too in /etc/pacman.conf

Void:

    sudo xbps-install pipewire wireplumber pipewire-pulse xdg-desktop-portal xdg-desktop-portal-wlr xdg-desktop-portal-kde river swww rofi waybar dunst pywal thunar kitty firefox git make cmake curl
ps: i couldnt find floorp in void repo or xbps-src so maybe its there i didnt search much please pm if there is
    
Gentoo:

    sudo emerge media-video/pipewire    media-video/wireplumber    sys-apps/xdg-desktop-portal    sys-apps/xdg-desktop-portal-kde    sys-apps/xdg-desktop-portal-wlr 
    gui-wm/river    gui-apps/swww    gui-apps/rofi-wayland    gui-apps/waybar    x11-misc/dunst    x11-misc/pywal    xfce-base/thunar    x11-terms/kitty    www-client/firefox    dev-vcs/git             dev-build/make    dev-build/cmake    net-misc/curl
    
ps: no floorp in gentoo repos and guru too

god that gentoo part took some time




                                                                                          
