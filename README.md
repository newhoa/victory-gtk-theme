# Victory Gtk Theme
Victory Gtk Theme, A flat minimalistic and bright gtk theme.

[Preview](#preview) | [About](#about) | [Installation](#install) | [Background](#background)

<a name="preview"></a>

##Preview

![VictoryGtk](https://i.imgur.com/y36CqfX.png "VictoryGtk")

Above:  Victory Gtk Theme, XFCE with Thunar, [Victory Icon Theme](https://github.com/newhoa/victory-icon-theme), [Flow wallpaper by tri5tian](https://www.gnome-look.org/content/show.php/Flow?content=71058)

![VictoryGtk Medium with Boston Icons](https://i.imgur.com/14FfVBP.png "VictoryGtk Medium with Boston Icons")

Above: VictoryGtk Medium with Boston Icons

![VictoryGtk Medium Dark with Arc Icons](https://i.imgur.com/nrgzrZu.png "VictoryGtk Medium Dark with Arc Icons")

Above: VictoryGtk Medium Dark with Arc Icons

![VictoryGtk Dark with Papirus Icons](https://i.imgur.com/OBVATAu.png "VictoryGtk Dark with Papirus Icons")

Above: VictoryGtk Dark with Papirus Icons

![VictoryGtk Dark with Breeze Icons](https://i.imgur.com/TUcBLWO.png "VictoryGtk Medium with Breeze Icons")

Above: VictoryGtk Medium with Breeze Icons

<a name="about"></a>

## About

Victory Gtk Theme is a flat, minimilaistic and mostly bright Gtk theme for Linux. It was made for Gtk2, specifically for XFCE and LXDE, though I did try to complete a lot of Gtk3 elements for Gtk 3.18 (Ubuntu 16.04). While some apps may look fine (Nautilus, Transmission, Catfish, etc) it is unlikely to work well in a full Gtk3 desktop like Gnome 3.

This was made, tested, and known to work well on Xubuntu and Lubuntu 16.04. The main theme includes:

* A Gtk2 theme that works great for XFCE and LXDE (should work on MATE as well)
* A somewhat functioning Gtk3 theme for Gtk 3.18 only
* An XFWM4 window border theme (also a test HiDPI variant)
* An Openbox window border theme

It will work best on XFCE or LXDE. It will not work with Gtk 3.20+ Apps or Desktops for now.


Border variants (Medium, Medium Dark, and Dark) are made for Gtk2 and Openbox only as of the 16.04 release. Each variant theme includes:

* A slightly modified Gtk2 theme from the original to match the window theme
* Gtk3.18 theme from the original so buttons and stuff work, but prob will not match the variant Gtk2 theme
* Openbox window themes

<a name="install"></a>

## Installation

To install the theme you can [download the theme as an archive](https://github.com/newhoa/victory-gtk-theme/archive/master.zip) and extract the folder of the version you want to your `/home/yourusername/.themes/` folder.

Or you can clone it in the terminal using either of these commands (NOTE: this will download all variants and also any documentation in the repository to your themes folder):

```bash
$ git clone https://github.com/newhoa/victory-gtk-theme.git ~/.themes/
```


Once the theme is placed in the .themes folder, open the appearance manager for your Desktop Environment to select the theme:

- LXDE/LXQT/Openbox: `lxappearance`
- Gnome 3: `gnome-tweak-tool`
- Mate: `mate-appearance-properties`
- XFCE: `xfwm4-settings`

To uninstall, simply delete the 'Victory-16.04' folder.

<a name="background"></a>

### Background

I started working on this around 2008, although at the time it was quite a different theme. It was colorful, compartmental, and made to be easily tweaked. There were GUI tools for Gnome 2, XFCE, and LXDE that allowed you to tweak a theme's colors such as tooltips and selection colors. I made a theme which linked the sidebar colors and menubar colors to those colors which could be changed, allowing people to easily change sidebar colors and menubar colors which allowed for many different window borders to be used with the theme. It also used a lot of color mixing in the code making it work for people who wanted a dark theme.

I eventually came to a point where I thought the theme was complete. At the time it included a complete version for Gnome 2, Gnome 3, XFCE, LXDE, XFWM4, Openbox, Gnome Shell Cinnamon, MATE. As well as platform specific menus like MintMenu, Cardapio, SUSE SLAB, USP, etc. In fact, I think at the time it was one of the most complete and well documented themes there was. It became a bit difficult to keep up, though, especially with Gtk3. I attempted many times to make the theme work with Gtk3 apps, but every new release to Gtk made changes that broke themes. Eventually I gave up on that and just let it be a Gtk2 theme and stand as it was.

I decided just for personal use to make changes here and there, eventually making it into a very simple and flat theme. I never published it because I thought it was very specific to my taste and to be honest I thought some of the current themes being worked on were quite incredible and worth more attention. Because I had slowly teaked it and made it for my personal use, the aspects aside from the ones that I used fell behind. Metacity, Gtk3, Cinnamon, Gnome Shell, and to a lesser extent MATE didn't keep up and didn't work with the current theme. It also mostly lost its tweakability as some of the colors became hard coded.

I eventually published an icon theme I had worked on. In the preview shot I was using this theme and people asked for a place to download it so I thought I'd put it up. I hope some people enjoy it. It's not as elaborate, beautiful, or as cohesive or as complete as many others like Arc, Numix, Vertex, etc, but hopefully people will enjoy it nevertheless!
