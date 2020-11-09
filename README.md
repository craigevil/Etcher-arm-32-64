# Etcher-arm-32-64
balena-etcher v1.5.109 & v1.5.110 compiled from source for armhf and arm64 for the RaspberryPi and other arm computers.

![Etcher on rpi screenshot](/screenshots/etcher.png)


## Installation:
you can install this version of Etcher in Pi-Apps (click the badge bellow for more info about pi-apps) <br> 
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)
or install manually: download the .deb file for your system architecture, (armhf is 32bit arm, and arm64 is 64bit arm) and open it with the package installer or open terminal in the directory where the .deb is and type 
```sh-session
$ sudo dpkg -i <the file name.deb>
```
## compile
follow the instructions [here](https://github.com/futurejones/balena-etcher-arm/blob/master/etcher-build/BUILD.md)
but replace this line: 
```sh-session
$ git checkout v1.5.63
```
with this line:
```sh-session
$ git checkout v1.5.110
```

## Uninstallation
If you installed from [Pi-Apps](https://github.com/Botspot/pi-apps), the you can also uninstall it from there.
to manually uninstall, type in terminal the following:
```sh-session
$ sudo apt purge -y balena-etcher-electron
```

