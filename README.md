# st-terminal

suckless terminal but modern

## Overview
This is a custom build of the [suckless terminal (st)](https://st.suckless.org/) with a modern touch. It aims to provide a clean, fast, and lightweight terminal experience.

## Patches
- alpha
- anygeometry
- anysize
- blinking_cursor
- bold_is_not_bright
- boxdraw
- clipboard
- columns
- copyurl
- copyurl_highlight_selected_urls
- csi_22_23
- drag_and_drop
- dynamic_padding_patch
- externalpipe
- externalpipein
- fixkeyboardinput
- font2
- keyboardselect
- opencopied
- open_selected_text
- openurl_on_click
- reflow
- relativeborder
- selection_colors
- selectionbg_alpha
- sixel
- sync
- vertcenter
- wide_glyphs
- workingdir
- xresources
- xresources_reload

## Installation
```bash
git clone https://github.com/Saad-Dev-8/st-terminal.git
cd st-terminal
sudo make clean install
```

## Requirements
- Xlib
- Fontconfig
- HarfBuzz
- (Optional) libsixel

On Debian/Ubuntu:
```bash
sudo apt install libx11-dev libxft-dev libxext-dev libharfbuzz-dev
```
On Arch/Artix:
```bash
sudo pacman -S libx11 libxft libxext harfbuzz
```

## Documentation
- `man st` - for terminal manual
- `FAQ` - frequently asked questions
- `TODO` - planned features
- `LEGACY` - legacy documentation

## Acknowledgments
- Original [suckless terminal](https://st.suckless.org/) project
- [st-flexipatch](https://github.com/bakkeby/st-flexipatch) by [bakkeby](https://github.com/bakkeby)

## License
MIT © [Saad-Dev-8](https://github.com/Saad-Dev-8)
