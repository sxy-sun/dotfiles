# dotfiles-backup
Applications:

Install with `sudo apt install xxx`

- Wallpaper setting: nitrogen
- Screenshot: flameshot
- File manager: nautilus
- Status bar: i3bar
- Display manager: Ly (Doesn't work, https://github.com/fairyglade/ly/issues/450)
- Screen lock: betterlockscreen
- Multiple monitor: xrandr

## Some useful commands:
How to restart the default display manager gdm3 [source](https://askubuntu.com/q/1361285)
```
sudo systemctl start gdm3
```

Update betterlockscreen wallpaper
```
betterlockscreen -u <path>
```
