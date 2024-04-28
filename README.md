
# Requirements
## Git
```powershell
winget install --id=Git.Git  -e
```
## Neovim 8+
```powershell
winget install --id=Neovim.Neovim  -e
```

# Install
> [!WARNING]  
> Open your terminal as administrator

## Remove current configuration
> [!WARNING]  
> This will remove your current configuration :?

```powershell
rm $env:LOCALAPPDATA\nvim\*
```
## Install new configuration
```powershell
git clone git@github.com:SamuelWK/nvim-conf-windows.git $env:LOCALAPPDATA\nvim
```

Open nvim for the first time and lazy(plugin manager) will install all plugins

# WIKI
## Plugin manager
- [folke/lazy.nvim](https://github.com/folke/lazy.nvim)

## Theme
- [tiagovla/tokyodark.nvim](https://github.com/tiagovla/tokyodark.nvim)
  
## List of plugins
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs)
- [vimwiki/vimwiki](https://github.com/chipsenkbeil/vimwiki.nvim)
