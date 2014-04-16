# Gnome-Catgen #

A Gnome 3.12 application-overview folder configuration tool

## CONFIG ##

To configure the folders gnome-catget will generate when `gnome-catgen set` is run:

1. Create a folder @ `~/.local/share/applications-categories`.
2. Create a file in that folder with the name of the category you want it to represent.
3. Place the filename of the .desktop file of an applicaton you'd like in the folder on a single line.
4. Repeat step **2** for more categories and step **3** for more applications until things are how you want them.
5. Run `gnome-catgen set` to configure your settings, then `gnome-catgen get` to check the results.
6. To remove all folders without having to change your config, run `gnome-catgen clear`.

## COMMANDS ##

* **gnome-catgen get**: Returns the list of categories followed by a list of the applications associated with each one.
* **gnome-catgen set**: Configures the folder categories and their included applications as defined.
* **gnome-catgen clear**: Removes all application lists currently set and defines the list of folder categories as blank.

## CREDITS ##

* Written by prurigro: [GitHub Projects](https://github.com/prurigro) | [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)
