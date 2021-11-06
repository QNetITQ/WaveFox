# *WaveFox*

## Supported operating systems
* Windows 7 and newer
* Linux 
* MacOS 11 and newer

## Features
* Tabs with a more classic look
* Light and dark theme support 
* All interface densities supported
* You can control the size of the drag space for each density in the "Custom Settings" section
* Reduced context menus. You can control the size of the context menus for each density in the "Custom Settings" section
* You can control the size and color of the shadows for each density in the "Custom Settings" section (Tab bar only)
* Media icons on tabs are always visible
* Accent color (Windows 11 / Windows 10) 
* Vibrancy (MacOS)
* Style is compatible with themes from the repository (Browser bar can be difficult to see depending on the theme)
* Support for different forms of tabs
* Support for tabs at the bottom 

## Screenshots
![Styles](https://user-images.githubusercontent.com/85301851/139716492-b4ac94d2-8dc8-41ff-acc8-53631cd3befd.png)
![изображение](https://user-images.githubusercontent.com/85301851/140235546-78f58809-33f5-44f6-9d1d-4467c30da597.png)

## Installation
1) Enter "about:profiles" in the address bar and open the root directory folder
2) Create a folder "chrome"
3) Download the "userChrome.css" file
4) Put the file "userChrome.css" in "chrome"
5) Enter "about:config" in the address bar
6) Looking for and changing the value of the following keys:
* "toolkit.legacyUserProfileCustomizations.stylesheets" > "True"
* "svg.context-properties.content.enabled" > "True"
* "layout.css.color-mix.enabled" > "True"
* If you want compact mode, set "browser.compactmode.show" > "True" and go to "Customize Toolbar"
7) By default, the shape of the tabs corresponds to the proton interface. To select a different form of tabs, go to "about:config" and create one of the keys below:
* Style.Photon
* Style.WaveFox
* Style.Chrome
* Style.Edge
* Style.Australis
* Style.Chrome-Old

To move tabs to the bottom of the browser bar, create a key below: 
* Style.Tabs-On-Bottom
* browser.tabs.drawInTitlebar > 0 (To display window control buttons on Windows 7/8. Not necessary for other systems)

8) Restart the browser

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* "browser.tabs.closeTabByDblclick" > "True" in "about:config"
