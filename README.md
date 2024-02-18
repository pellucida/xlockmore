# xlockmore - AlmaLinux 8 etc

## Fedora Core 29 binary package will install
The package **xlockmore-5.55-5.fc29.x86_64.rpm** will install on AL8
with the icon packages **gnome-icon-theme-legacy-3.12.0-10.fc29.noarch.rpm**
prerequisite package installed
(for /usr/share/icons/gnome/16x16/actions/gnome-lockscreen.png)

## Using the spec file from FC29
The package can be rebuilt for *EL8 after the build prerequisites are 
satified. 

## Removed GL and Motif package build
Since I only required support for Openbox I disabled Motif and GL support
avoiding the need for those devel packages.

