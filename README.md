# Flare
An adaptive Gnome shell theme which keeps a lot of design elements from
Adwaita and brings some of the elements from the default
Unity theme. It is an attempt to make Ubuntu with Gnome feel more
familiar, but at the same time more modern.

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-16-56-01.png)

## Colors
Official Ubuntu colors were used throught the theme in order to keep the feel of the Ubuntu brand. 

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-16-56-54.png)

## Material
The use of blur brings better contrast between the background and the overview items. Many design
elements are now using translucent material in order to blend better with all kinds of different backgrounds
and colors.

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-16-57-07.png)

## Extensions
This theme heavily relies on "Blyr" and "Dynamic Panel Transparency" extensions which can be found on the official
Gnome shell extensions website. For the dynamic panel transparency enable custom foreground colors and custom background opacity.
The optimal values for the panel opacity are 0.5 when not maximized and 0.88 when maximized.

![alt text](https://raw.githubusercontent.com/vladimir-genkin/image-assets/master/screenshots/2017-11-04-17-19-26.png)

## Installation
The Ubuntu font family is used throught the theme, so make sure to install it first.

```
sudo apt install ttf-ubuntu-font-family
```

Download the zip archive containing the theme and unzip it into the "themes" directory.

```
cd Downloads
```

```
unzip flare-master.zip
```

```
cp -r flare-master ~/.local/share/themes
```

Enable the theme using the Gnome tweak tool.
