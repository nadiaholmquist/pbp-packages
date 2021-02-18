# pbp-packages
Packages for using Arch Linux ARM on the Pinebook Pro laptop.

To use this repo, add the following to your `pacman.conf`:
```
[pinebookpro]
Server = https://nhp.sh/pinebookpro/
```
then run the following as root to import the signing key:
```
pacman-key --recv-keys 50626D06C63A8C774FCB35D2497FE64338F993E9
pacman-key --lsign-key 50626D06C63A8C774FCB35D2497FE64338F993E9
```
