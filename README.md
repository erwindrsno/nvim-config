# 💤 LazyVim

# step into your nvim config directory
cd ~/.config/nvim

# delete lock file and plugin directory
rm lazy-lock.json
rm -rf ~/.local/share/nvim/lazy

# reopen Neovim
nvim

:Lazy sync
