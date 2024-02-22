# 1. Debian DWM Bootsrap
Simple script to install suckless [DWM](https://dwm.suckless.org/) on bare minimal Debain 12.

# 2. Prerequisite
Make sure the user has **sudo** previlidge and the machine has access to the internet.

# 3. Clone the repo

```
$ sudo pacman -S git
$ git clone https://github.com/Kouei-Lin/arch-dwm-bootstrap ~/arch-dwm-bootstrap
```

# 4. Run the script

```
$ cd ~/arch-dwm-bootstrap
$ chmod +x dwm.sh
$ ./dwm.sh
```

# 5. Start DWM

The script should auto start into DWM, if not, type in `startx` in the terminal to start DWM.

Next time boot up your machine, same just type `startx` to start DWM.

# 6. Wallpaper
I set wallpaper to the `~/.suckless/bg/bg.jpg` in the [dotfiles](https://github.com/Kouei-Lin/dwm-dotfiles) repo. 

Set the wallpaper to whatever you like using `feh --bg-fill /path/to/your/image.jpg`.

# 7. DWM Patches
Patch your DWM by visting [DWM Patches](https://dwm.suckless.org/patches/)!!

Default DWM keybindings can be checked via this community made [cheatsheet](https://gist.github.com/erlendaakre/12eb90eef84a3ab81f7b531e516c9594).
