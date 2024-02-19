# xlockmore - AlmaLinux 8 etc

## Fedora Core 29 binary package will install
The package **xlockmore-5.55-5.fc29.x86_64.rpm** will install on AlmaLinux8
with the prerequisite icon package **gnome-icon-theme-legacy-3.12.0-10.fc29.noarch.rpm**
installed presumably for */usr/share/icons/gnome/16x16/actions/gnome-lockscreen.png*

## Using the spec file from FC29
The package can be rebuilt for *AL8* etc  after the build prerequisites are satified. 

## No GL and Motif package built

Since I only required support for Openbox I disabled Motif and GL support avoiding the need for those development packages

Replaced the *gnome-lockscreen.png* icon with *system-lock-screen.png* removing the need for **gnome-icon-theme-legacy**.

As I use startx rather than gdm the icon is probably unneeded.

## Later version builds

The most recent version from sillycycle **xlockmore-5.75.tar.xz** will build with the slightly modified spec file xlockmore-5.75.spec.

## License

See **LICENSE** where the license from the upstream source is reproduced and is roughly a BSD style license.

