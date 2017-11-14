# Flare
An adaptive Gnome shell theme which keeps a lot of design elements from
Adwaita and brings some of the elements from the default
Unity theme. It is an attempt to make Ubuntu with Gnome feel more
familiar, but at the same time more modern.

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-16-56-01.png)

## Colors
Official Ubuntu colors were used throughout the theme in order to keep the feel of the Ubuntu brand. 

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-16-56-54.png)

## Material
The use of blur brings better contrast between the background and the overview items. Many design
elements are now using translucent material in order to blend better with all kinds of different backgrounds
and colors.

## Extensions
This theme heavily relies on "Blyr" and "Dynamic Panel Transparency" extensions which can be found on the official
Gnome shell extensions website. For the dynamic panel transparency enable custom foreground colors and custom background opacity.
The optimal values for the panel opacity are 70% when not maximized and 90% when maximized.

## Installation
The Ubuntu font family is used throughout the theme, so make sure to install it first.

```sh
sudo apt install ttf-ubuntu-font-family
```
Download the zip archive containing the theme and unzip it into the "themes" directory.

```sh
cd Downloads
unzip flare-master.zip
cp -r flare-master ~/.local/share/themes
```

Enable the theme using the Gnome tweak tool.

## Credits
The icons shown on the screenshots are based on the Numix circle icon theme
(https://github.com/numixproject/numix-icon-theme-circle).
