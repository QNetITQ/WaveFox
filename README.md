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

## Screenshots
### Proton Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958256-b6476b63-5c3a-4c26-8d02-b026dcaf3caa.png)
### Photon Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958462-b3498673-e969-40c2-ba7b-d7185037e129.png)
### WaveFox Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137959254-65b911a4-86cb-48ec-8505-f95855e67870.png)
### Australis Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958540-db9e43ce-d4d8-4240-9d73-820efb4edfdb.png)
### Old Chrome Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958662-c27530d2-a8bf-46d5-902b-09e866d37618.png)
### Chrome Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958735-3265a11d-36e5-421b-a5e6-b49360f6fb0f.png)
### Edge Tabs
![изображение](https://user-images.githubusercontent.com/85301851/137958818-5eced00a-bf60-479a-bf40-61de6d75c4a8.png)



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
* Style.Australis
* Style.Chrome-Old
* Style.Chrome
* Style.Edge
8) Restart the browser

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* "browser.tabs.closeTabByDblclick" > "True" in "about:config"
