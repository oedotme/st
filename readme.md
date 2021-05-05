# st - simple terminal

This project is a fork of [st - simple terminal emulator](https://st.suckless.org)

## Features

- **Customize cursor color**
- **Desktop entry** add/remove on install/uninstall
- **Disabled bold fonts**
- **Emoji support**
- **Font ligatures support**
- **Fonts fallback**
- **Light color scheme**
- ~~**Scrollback support**~~ using `tmux` scrolling

## Requirements

#### In order to build st you need the Xlib header files

#### Packages `arch-based` systems

##### Official repositories - `pacman`

- `harfbuzz` : ligatures rendering
- `noto-fonts-emoji` : emoji support
- `noto-fonts` : unicode characters
- `ttf-jetbrains-mono` or `ttf-fira-code` : supports ligatures
- `ttf-nerd-fonts-symbols-mono` : glyph icons

##### Aur - `yay`

- `libxft-bgra` : emoji rendering

## Getting started

### Installing / Building

- `sudo make clean install`

### Running

- Start with geometry options : `st -g 200x100`
- Start with a `tmux` session : `st -e tmux`

### Uninstall

- `sudo make uninstall`
