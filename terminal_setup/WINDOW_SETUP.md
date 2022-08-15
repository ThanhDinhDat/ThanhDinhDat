<img src="../assets/tabby+oh_my_posh+autocomplete.png" alt="window_terminal">
# Requirements
+ OS: Window 10/11

# Terminal alternatives
+ [Tabby](https://tabby.sh/) - A terminal for the modern age

## Personal powershell_profile
```
oh-my-posh init pwsh --config ~/.thanhdinhdat.omp.json | Invoke-Expression
Import-Module -Name Terminal-Icons
Import-Module PSReadLine
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
Set-PSReadLineOption -EditMode Windows
```
# Open powershell
## ADD "OH MY POSH" TO YOUR SHELL
They have an amazing docs [here](https://ohmyposh.dev/docs/installation/windows)

### Personal oh-my-posh config
- [JSON](./.thanhdinhdat.omp.json)

## Add colorful icons/color
- Install the packages
```
Install-Module -Name Terminal-Icons -Repository PSGallery
```
- Add to your `$PROFILE` - you can use VSCode to edit `$PROFILE` with `code $PROFILE`
```
Import-Module -Name Terminal-Icons
```

## Show recent history commands when typing
- Install the amazing [PSReadLine](https://github.com/PowerShell/PSReadLine?WT.mc_id=-blog-scottha)

# Ref
Big thanks for [HanselMan](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal)