[![](https://vsmarketplacebadge.apphb.com/version/beaugust.blamer-vs.svg)](https://marketplace.visualstudio.com/items?itemName=beaugust.blamer-vs)
[![](https://vsmarketplacebadge.apphb.com/installs/beaugust.blamer-vs.svg)](https://marketplace.visualstudio.com/items?itemName=beaugust.blamer-vs)

# SVN Gutter
This is the Visual Studio Code version of the [Blamer](https://github.com/BeauAgst/Blamer) plugin, built for Sublime Text.

## Commands:
This extension contributes the following commands to the Command palette.

`SVN Gutter - Show Blame`: Adds icons to gutter with tooltips containing information from each revision

`SVN Gutter - Clear Blame`: Clears icons and tooltips

It also adds a keyboard shortcut.

`CTRL + ALT + D`: Will run the `SVN Gutter - Show Blame` command.

## Features
When run, this extension will place an icon next to each line of your file. Each differently-coloured icon means a different revision. Hovering a line will produce a tooltip, showing the committer, date, and message. 

For example if you're working on a project and you want to see who modified a specific line:

![Example Usage](example.gif)

## Requirements
This extension requires that you're either:

* On a Windows machine with Tortoise SVN installed, with command-line tools.
* A Unix machine.

## Extension Settings
Currently there are no settings

## Known Issues
- Possibly incompatible with Mac. ([Pull requests welcome!](https://github.com/BeauAgst/blamer-vs/issues/1))
- A little bit slow, because all unique logs have to be retrieved first. ([Issue](https://github.com/BeauAgst/blamer-vs/issues/3))

## Release Notes
## 0.4.0
- Revision number added to tooltips [#7](https://github.com/BeauAgst/blamer-vs/issues/7)

## 0.3.2
- Fixed decoration issue causing characters to show incorrectly dependant on the language [#6](https://github.com/BeauAgst/blamer-vs/issues/6)

## 0.3.1
- Removed formatting error in decoration caused by conflict with `mailto:`
- Added icon to extension

## 0.3.0
- Linux support added. [#2](https://github.com/BeauAgst/blamer-vs/issues/2)

## 0.2.0
- Added keyboard shortcut
- Fixed readme typo

## 0.1.0
- Initial release