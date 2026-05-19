# dotfiles

Personal config files for tmux and Alacritty.

## Layout

- `tmux/.tmux.conf` → `~/.tmux.conf`
- `alacritty/alacritty.toml` → `~/.config/alacritty/alacritty.toml`

Neovim config lives in its own repo: [kickstart.nvim](https://github.com/jonpaco/kickstart.nvim).

## Install

```sh
ln -s "$PWD/tmux/.tmux.conf" ~/.tmux.conf
mkdir -p ~/.config/alacritty
ln -s "$PWD/alacritty/alacritty.toml" ~/.config/alacritty/alacritty.toml
```
