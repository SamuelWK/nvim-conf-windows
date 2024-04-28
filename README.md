
# Requirements
## git
```powershell
winget install --id=Git.Git  -e
```
## neovim 8+
```powershell
winget install --id=Neovim.Neovim  -e
```

# Install
> [!WARNING]  
> Open your terminal as administrator

## Current configuration
```powershell
rm $env:LOCALAPPDATA\nvim\*
```
## Install new configuration
```powershell
cd $env:LOCALAPPDATA\nvim
git clone git@github.com:SamuelWK/nvim-conf-windows.git
```


