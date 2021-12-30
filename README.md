# *WaveFox*

## Supported operating systems
* Windows 10 and newer (Full support)
* Linux (Full support)
* MacOS 11 and newer (Partial support)
* Windows 7/8 (Partial support)

#### Partial support
The style works under these systems, but has not been tested by the author. Visual effects unique to these systems (Aero / Vibrancy, etc.) are not supported, but will work if Mozilla activates them by default 

## Features
* All themes supported (Tabs can be difficult to distinguish with some themes from the repository)
* All interface densities supported
* You can control the size of the drag space in the "Custom Settings" section
* You can control the size of the context menus in the "Custom Settings" section
* You can control the size and color of the shadows in the "Custom Settings" section (Tab bar only)
* Media icons on tabs are always visible
* Accent color (Windows 11 / Windows 10)
* Various forms of tabs are supported
* Menu icons support (Not all icons are active on MacOS)

## Screenshots
![Styles](https://user-images.githubusercontent.com/85301851/139716492-b4ac94d2-8dc8-41ff-acc8-53631cd3befd.png)

## Installation
1. Download the `chrome` folder and put it in the root folder (also known as the user profile folder)
2. Go to the `about:config` and switch the keys below:
* `toolkit.legacyUserProfileCustomizations.stylesheets` > `True`
* `svg.context-properties.content.enabled` > `True`
* `layout.css.color-mix.enabled` > `True`

To enable an alternative form of tabs, go to `about:config` and create one of the keys below:
* `Style.Photon` > `True`
* `Style.WaveFox` > `True`
* `Style.Chrome` > `True`
* `Style.Edge` > `True`
* `Style.Australis` > `True`
* `Style.Chrome-Old` > `True`

To enable icons, create one of the keys below:
* `Style.Menu-Icons-Regular` > `True`
* `Style.Menu-Icons-Filled` > `True`

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* `browser.tabs.closeTabByDblclick` > `True`
* `Ctrl + W` / `Command + W` closes the current tab
