# My build of dwm
---

## Modifications
### Patches
---
  - [ActualFulscreen](https://dwm.suckless.org/patches/actualfullscreen/)
  - [AttachBelow](https://dwm.suckless.org/patches/attachbottom/)
  - [Center](https://dwm.suckless.org/patches/center/)
  - [HideVacanttags](https://dwm.suckless.org/patches/hide_vacant_tags/)
  - [PerTag](https://dwm.suckless.org/patches/pertag/)
  - [ResizeCorners](https://dwm.suckless.org/patches/resizecorners/)
  - [SaveFloats](https://dwm.suckless.org/patches/savefloats/)
  - [Systray](https://dwm.suckless.org/patches/systray/)
  - [VanityGaps](https://dwm.suckless.org/patches/vanitygaps/)
  - [Warp](https://dwm.suckless.org/patches/warp/)
### drw.c
---
  At line 207, a line of code was added to fix the transparent border issue when using picom.

## Note
---
My configuration still exists, so if you want to use dwm without it just remove the config.h file.

## installation
---
`
git clone https://github.com/IMSOEVIL/dwm.git
cd dwm
sudo make install
`
