# pbp-packages
Packages for using Arch Linux ARM on the Pinebook Pro laptop.

To use this repo, add the following to your `pacman.conf`:
```
[pinebookpro]
Server = https://nhp.sh/pinebookpro/
```
then run the following as root to import the signing key:
```
pacman-key --recv-keys 955129793AA3C36B
pacman-key --lsign-key 955129793AA3C36B
```
