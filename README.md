# Arch_macbookAir72

My laptop is a 13" Macbook Air 7,2 purchased in Australia

I installed Arch using arch-anywhere with gnome and all the obvious laptop options

# Drivers

## Keyboard

Almost all keys seem to work by default including all special function keys except for the tilde key above the tab key

## Wireless (Broadcom Limited BCM4360)

broadcom-wl on AUR is the driver that worked for me

https://aur.archlinux.org/packages/broadcom-wl/


# Tools

## Package management

### Pacman (Official)

### Yaourt (AUR)

git clone https://aur.archlinux.org/package-query.git
cd package-query
makepkg -si
cd ..
git clone https://aur.archlinux.org/yaourt.git
cd yaourt
makepkg -si
cd ..
