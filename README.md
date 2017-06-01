# atom-terminal-powershell

## Difference from Atom-Terminal
Custom edit to atom-terminal plugin to support powershell out of the box.
Provides the same properties as the original plugin except defaults to Powershell.

Original package can be found here: [https://github.com/karan/atom-terminal](https://github.com/karan/atom-terminal)

![Default Powershell Option](https://raw.github.com/superkaitokid/atom-terminal-powershell/master/default.png)

## Usage
If using Powershell, supply a Powershell executable and check the Is Powershell option.

If using other terminals, uncheck Is Powershell option and follow normal atom-terminal usage.

![Is PowerShell Option](https://raw.github.com/superkaitokid/atom-terminal-powershell/master/isPowerShell.png)

## Original Atom-Terminal Instructions

Open terminal on current file's directory with `ctrl-shift-t`.

Open a terminal in the project's root directory with `alt-shift-t`.

Keybindings: `ctrl-shift-t`, `alt-shift-t`

Install: `apm install atom-terminal-powershell`

Config:
```coffeescript
"atom-terminal":
    # only necessary if standard config doesn't find terminal app
    app: "/path/to/your/favorite/terminal"
    args: "--useThisOptionWhenLaunchingTerminal"
```

![atom-terminal](https://raw.github.com/karan/atom-terminal/master/terminal.gif)
