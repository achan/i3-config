# My very own i3 Configuration

## Requirements
### general
* i3 - window manager
* i3status - status bar
* feh - setting bg, also nice image viewer
* urxvt - terminal emulator
* unclutter - autohide mouse cursor
* udiskie - device automounting
* dunst - notifications
* pulseaudio - audio managment
* autocutsel - clipboard synchroniation
* dmenu - Super-P launcher
* pavucontrol - pulseaudio mixer
* alsamixer
### from xorg
* setxkbmap - setting keyboard layout
* xmodmap - custom key changes


##Installation
It's as simple as that:

```bash
cd
git clone https://github.com/achan/i3-config.git .i3
ln -s .i3/xinitrc .xinitrc
ln -s .i3/gtkrc-2.0 .gtkrc-2.0
```

##Bindings
* Super-Shift-c - close current windows
* Super-Shift-Enter - open terminal
* Super - drag floating windows
* Super-t - toggle floating mode
* Super-f - fullscreen
* Super-r - resize mode

Check config for more.
