NumixBlue is a modified version of the original GTK3 Theme "Numix". Just like the original Numix theme, it supports
GNOME, xFce, openbox, and Unity.

KNOWN BUGS:
......Not exactly ones I can list. There are bugs though... I will address theme soon enough. Like, today. Or tomorrow.

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "NumixBlue"
gsettings set org.gnome.desktop.wm.preferences theme "NumixBlue"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "NumixBlue"
xfconf-query -c xfwm4 -p /general/theme -s "NumixBlue"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### Code and license

Report bugs or contribute at [GitHub](https://github.com/newfyworld/NumixBlue)

License: GPL-3.0+
=========
NumixBlue
=========

Blue version of Numix GTK3 Theme http://newfyworld2.deviantart.com/
