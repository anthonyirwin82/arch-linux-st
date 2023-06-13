# arch-linux-st

This is a modified Arch Linux Simple Terminal (st) installation package that has the https://st.suckless.org/patches/scrollback/ 
patches applied so that you can use a wheel mouse in st to scrollback through history that has flowed off the 
screen.

It is based off the official https://aur.archlinux.org/st.git installation package.

## Installation Instructions
```
git clone https://github.com/anthonyirwin82/arch-linux-st.git
cd arch-linux-st
updpkgsums
makepkg
makepkg -ie
```
