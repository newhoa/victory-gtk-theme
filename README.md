# Victory Gtk Theme
Victory Gtk Theme, A flat minimalistic and bright gtk theme.

[Preview](#preview) | [About](#about) | [Installation](#install) | [Background](#background) | [Contribute or Donate](#contdon) 

<a name="preview"></a>

##Preview

![VictoryGtk](https://i.imgur.com/y36CqfX.png "VictoryGtk")

Above:  Victory Gtk Theme, XFCE with Thunar, [Victory Icon Theme](https://github.com/newhoa/victory-icon-theme), [Flow wallpaper by tri5tian](https://www.gnome-look.org/content/show.php/Flow?content=71058)

![Victory Gtk Theme Medium with Boston Icons](https://i.imgur.com/14FfVBP.png "Victory Gtk Theme Medium with Boston Icons")

Above: Victory Gtk Theme Medium with Boston Icons

![Victory Gtk Theme Medium Dark with Arc Icons](https://i.imgur.com/nrgzrZu.png "Victory Gtk Theme Medium Dark with Arc Icons")

Above: Victory Gtk Theme Medium Dark with Arc Icons

![Victory Gtk Theme Medium Dark with Papirus Icons](https://i.imgur.com/cjL0Qf2.png "Victory Gtk Theme Medium Dark with Papirus Icons")

Above: Victory Gtk Theme Medium Dark with Papirus Icons

![Victory Gtk Theme Dark with Papirus Icons](https://i.imgur.com/OBVATAu.png "Victory Gtk Theme Dark with Papirus Icons")

Above: Victory Gtk Theme Dark with Papirus Icons

![Victory Gtk Theme Dark with Breeze Icons](https://i.imgur.com/TUcBLWO.png "Victory Gtk Theme Dark with Breeze Icons")

Above: Victory Gtk Theme Dark with Breeze Icons

<a name="about"></a>

## About

Victory Gtk Theme is a flat, minimilistic, and mostly bright Linux theme made primarily for Gtk 2-centric desktops (XFCE and LXDE) with some Gtk 3 support.

This was made, tested, and known to work well on Xubuntu and Lubuntu 16.04 and 16.10. Gtk 3 support is being tested on the aforementioned DE's as well as on [Solus OS](https://solus-project.com/). The main theme includes:

* A Gtk2 theme that works great for XFCE and LXDE (should work on MATE as well)
* A Notifications Theme for XFCE
* An XFWM4 window border theme for XFCE (also a test HiDPI variant)
* An Openbox window border theme for LXDE and Openbox
* A somewhat functioning Gtk 3 theme for Gtk 3.18 (in Victory 16.04 and 16.10)
* A work-in-progress Gtk 3 theme for Gtk 3.20 and higher (in Victory 16.10)


Border variants (Medium, Medium Dark, and Dark) effect only Gtk2, Openbox, and XFWM4 for now. Each variant theme includes:

* A variant Openbox window theme for LXDE and Openbox
* A variant XFWM4 window theme for XFCE
* A slightly modified Gtk2 theme taken from the original to match the variant window border
* A Gtk 3 theme copied from the main theme so buttons and stuff work and match, but Gtk 3 theme will not have the dark borders.

<a name="install"></a>

## Installation

To install the theme you can [download the theme as an archive](https://github.com/newhoa/victory-gtk-theme/archive/master.zip) and extract the folder of the version you want to your `/home/yourusername/.themes/` folder.

Or you can clone it in the terminal using either of these commands (NOTE: this will download all variants and also any documentation in the repository to your themes folder):

```bash
$ git clone https://github.com/newhoa/victory-gtk-theme.git ~/.themes/
```


Once the theme is placed in the .themes folder open the appearance manager for your Desktop Environment to select the theme:

- LXDE/LXQT: `lxappearance`
- XFCE: `xfce4-appearance-settings`

Use these apps to change the Window Border:

- LXDE/Openbox: `obconf`
- XFCE/XFWM4 Window Border: `xfwm4-settings`

Use the XFCE Notifications Settings to change the Notify Popup theme

- XFCE: `xfce4-notifyd-config`


To uninstall, simply delete the 'Victory-16.04' or similar folders.

<a name="background"></a>

### Background

I started working on this around 2008, although at the time it was quite a different theme. It was colorful, compartmental, and made to be easily tweaked. There were GUI tools for Gnome 2, XFCE, and LXDE that allowed you to tweak a theme's colors such as tooltips and selection colors. I made a theme which linked the sidebar colors and menubar colors to those colors which could be changed, allowing people to easily change sidebar colors and menubar colors which allowed for many different window borders to be used with the theme. It also used a lot of color mixing in the code making it work for people who wanted a dark theme.

I eventually came to a point where I thought the theme was complete. At the time it included a complete version for Gnome 2, Gnome 3, XFCE, LXDE, XFWM4, Openbox, Gnome Shell, Cinnamon, MATE. As well as platform specific menus like MintMenu, Cardapio, SuSE SLAB, USP, etc. In fact, I think at the time it was one of the most complete and well documented themes there was. It became a bit difficult to keep up, though, especially with Gtk3. I attempted many times to make the theme work with Gtk3 apps, but every new release to Gtk made changes that broke themes. Eventually I gave up on that and just let it be a Gtk2 theme and stand as it was.

I decided just for personal use to make changes here and there, eventually making it into a very simple and flat theme. I never published it because I thought it was very specific to my taste and to be honest I thought some of the current themes being worked on were quite incredible and worth more attention. Because I had slowly tweaked it and made it for my personal use, updating only the parts that I needed, the aspects aside from the ones that I used fell behind. Metacity, Gtk3, Cinnamon, Gnome Shell, and to a lesser extent MATE didn't keep up and didn't work with the current theme. It also mostly lost its tweakability as some of the colors became hard coded.

Recently I published an icon theme that I had worked on. In the preview image I was using this theme and people asked for a place to download it so I thought I'd put it up. It's not as elaborate, beautiful, or as cohesive or as complete as many others like Arc, Numix, Vertex, etc, but hopefully people will enjoy it nevertheless!


<a name="contdon"></a>

## Contribute or Donate

If anyone would like to contribute, please feel free to let me know where something doesn't look right, file a bug report if you have any problems, or even help out with the theme if you'd like. A dark theme is something I'm not very focused on, I have started it (in the gtk-3.20 folder) and if anyone would like to help work on that it would be appreciated. 

In addition to contributing, I'll also offer my paypal email for anyone interested in donating. I don't expect anything from this but a few have asked so it couldn't hurt to add it. It is `newhoa.donate` (AT) `linuxmail.org` | I've worked for many years and hundreds of hours on this theme and the icon theme. I've enjoyed every second of it and it has been an incredible learning experience. I'll continue to do it because I enjoy it and it's my way to give something to the FOSS community that I love, admire, and am indebted to. I would greatly appreciate help in any form and thank anyone who feels inclined to do so. Thank you all for your support, whether it is simply a thank you, a compliment, some advice, constructive criticism, or a donation it is all very much appreciated.


