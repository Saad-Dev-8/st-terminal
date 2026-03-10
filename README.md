# st-terminal

suckless terminal but modern

## Overview
This is a custom build of the [suckless terminal (st)](https://st.suckless.org/) with a modern touch. It aims to provide a clean, fast, and lightweight terminal experience.

## Features
Based on the repository contents, this build includes:
- **Sixel graphics support** (`sixel.c`, `sixel.h`, `sixel_hls.c`, `sixel_hls.h`) - for displaying images directly in the terminal
- **HarfBuzz text shaping** (`hb.c`) - for improved font rendering and complex script support
- Standard suckless terminal functionality with a modern configuration

## Installation
```bash
git clone https://github.com/Saad-Dev-8/st-terminal.git
cd st-terminal
sudo make clean install
```

## Configuration
Edit `config.h` before compilation to customize:
- Fonts
- Colorschemes
- Keyboard shortcuts
- Terminal behavior

For persistent changes, modify `config.def.h` and recompile.

## Requirements
- Xlib headers
- Fontconfig
- HarfBuzz development libraries
- (Optional) libsixel for advanced sixel support

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
