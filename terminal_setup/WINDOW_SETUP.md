<img src="../assets/tabby+oh_my_posh+autocomplete.png" alt="window_terminal">
# Requirements
+ OS: Window 10/11

# Terminal alternatives
+ [Tabby](https://tabby.sh/) - A terminal for the modern age

# Open powershell
## ADD "OH MY POSH" TO YOUR SHELL
They have an amazing docs [here](https://ohmyposh.dev/docs/installation/windows)

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