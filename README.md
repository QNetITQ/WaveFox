# *WaveFox*

## Supported operating systems
* Windows 7 and newer
* Linux 
* MacOS 11 and newer (MacOS support temporarily suspended. This does not mean that the style will not work, it just has not been personally verified by the author)

## Features
* All themes supported (Tabs can be difficult to distinguish with some themes from the repository)
* All interface densities supported
* You can control the size of the drag space in the "Custom Settings" section
* You can control the size of the context menus in the "Custom Settings" section
* You can control the size and color of the shadows in the "Custom Settings" section (Tab bar only)
* Media icons on tabs are always visible
* Accent color (Windows 11 / Windows 10) 
* Vibrancy (MacOS)
* Various forms of tabs are supported
* Tabs under the bookmarks bar supported
* Menu icons support (Not all icons are active on MacOS)

## Screenshots
![Styles](https://user-images.githubusercontent.com/85301851/139716492-b4ac94d2-8dc8-41ff-acc8-53631cd3befd.png)
![изображение](https://user-images.githubusercontent.com/85301851/140235546-78f58809-33f5-44f6-9d1d-4467c30da597.png)

## Installation
Download the `chrome` folder and put it in the root folder (also known as the user profile folder)

Go to the `about:config` and switch the keys below:
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


To move tabs under the bookmarks bar, create a key below: 
* `Style.Tabs-On-Bottom` > `True`
* `browser.tabs.drawInTitlebar` > `0` or `browser.tabs.inTitlebar` > `0` (To display window control buttons on Windows 7/8. Not necessary for other systems)

To enable icons, create one of the keys below:
* `Style.Menu-Icons-Regular` > `True`
* `Style.Menu-Icons-Filled` > `True`

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* `browser.tabs.closeTabByDblclick` > `True`
* `Ctrl + W` / `Command + W` closes the current tab
