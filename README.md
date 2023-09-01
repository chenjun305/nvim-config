# neovim
[https://neovim.io/](https://neovim.io/)
## install
```
brew install neovim
```

## install other tools
* [lazygit](https://github.com/jesseduffield/lazygit)
* [ripgrep](https://github.com/BurntSushi/ripgrep)
* [fd](https://github.com/sharkdp/fd)

```
brew install lazygit
brew install ripgrep
brew install fd
```

## config neovim

```
git clone git@github.com:chenjun305/nvim-config.git ~/.config/nvim
```
如果不是第一次配置nvim, 已经有`~/.config/nvim/`配置，可先进行备份。
```
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

neovim config based on [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.


