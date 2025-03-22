# 🖌️ Moscow Polytech Grub2 theme

![GRUB2](https://github.com/user-attachments/assets/d5c539e4-0614-492d-8eb1-c9bb91ae93bf)

## ▶️ Installation

RUN:

```sh
sudo ./install.sh
```

### Installation Usage

Usage:  `sudo ./install.sh [OPTIONS...]`

|  Options:              | Description: |
|:-----------------------|:-------------|
| -b, --boot             | Install grub theme into `/boot/grub/themes` |
| -s, --screen           | screen display variant(s) [1080p/2k/4k] (default is 1080p) |
| -r, --remove           | Uninstall theme |
| -h, --help             | Show this help |

## ☠️ Correcting display resolution
 - On the grub screen, press `c` to enter the command line
 - Enter `vbeinfo` or `videoinfo` to check available resolutions
 - Open `/etc/default/grub`, and edit `GRUB_GFXMODE=[height]x[width]x32` to match your resolution
 - Finally, run `grub-mkconfig -o /boot/grub/grub.cfg` to update your grub config

## 🔗 Links
[Based On Graphite](https://github.com/vinceliuice/Graphite-gtk-theme/tree/main)
