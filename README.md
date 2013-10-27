Neuver Theme
======

Neuver is a super flat linux theme for anyone who has preference for ultra minimalistic looks. Neuver is based on the super awesome Numix Theme (numixproject.org). It works best with Gnome and Unity but supports XFCE and Openbox too.

![alt tag](https://raw.github.com/hashbit/neuver/master/screenshot.png)

### Installation

Extract or Copy the Theme folder to your themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Neuver"
gsettings set org.gnome.desktop.wm.preferences theme "Neuver"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Neuver"
xfconf-query -c xfwm4 -p /general/theme -s "Neuver"
```

For a completely super flat look, you should consider disabling shadows.

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### Code and license

License: GPL-3.0+

