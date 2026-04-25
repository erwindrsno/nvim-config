# 💤 LazyVim

A starter template for LazyVim.
Refer to the official documentation to get started:
https://lazyvim.github.io/installation

# -----------------------------
# Fresh Install / Reset
# -----------------------------

# Step to nvim config directory
`cd ~/.config/nvim`

# Delete lock file and plugin directory
`rm lazy-lock.json`
`rm -rf ~/.local/share/nvim/lazy`
`rm ~/.local/state/nvim`
`rm ~/.cache/nvim`
(or you can back it up also)

# Reopen Neovim
`nvim`

# Sync and reinstall plugins
`:Lazy sync`
