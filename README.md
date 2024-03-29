# arch-dotfiles

These are the dotfiles

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/bklaaswerkman/dwm) (window manager)
- [dwmblocks](https://github.com/bklaaswerkman/dwmblocks) (statusbar)
- [st](https://github.com/bklaaswerkman/st) (terminal emulator)

## Install these dotfiles and all dependencies

Use [KARBS](https://github.com/bklaaswerkman/KARBS) to autoinstall everything:

```
curl -LO raw.githubusercontent.com/bklaaswerkman/KARBS/master/karbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/bklaaswerkman/KARBS/blob/master/progs.csv).
