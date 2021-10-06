# *WaveFox*

## Supported operating systems
* Windows 7 and newer
* Linux 
* MacOS 11 and newer

## Features
* Tabs with a more classic look
* All interface densities supported
* You can control the size of the drag space for each density in the "Custom Settings" section
* Reduced context menus. You can control the size of the context menus for each density in the "Custom Settings" section
* You can control the size and color of the shadows for each density in the "Custom Settings" section (Tab bar only)
* Media icons on tabs are always visible
* Accent color (Windows 11 / Windows 10) 
* Vibrancy (MacOS)
* Style is compatible with themes from the repository

## Screenshots
#### Compact (Light)
![7KBRGjs](https://user-images.githubusercontent.com/85301851/131252428-6d49b402-1380-4857-901a-481e73c8fa3d.jpeg)
#### Compact (Dark)
![QdY1qHy](https://user-images.githubusercontent.com/85301851/131252437-424ed58d-df61-4e56-a6e0-989055443af0.jpeg)
#### Normal (Light)
![Ey9uBqz](https://user-images.githubusercontent.com/85301851/131252443-d0295b17-54b4-4598-8b05-621b77459f76.jpeg)
#### Normal (Dark)
![TVRfbMI](https://user-images.githubusercontent.com/85301851/131252452-de7d893a-23bd-4b9d-926f-660050d907cb.jpeg)
#### Touch (Light)
![oWaAVDq](https://user-images.githubusercontent.com/85301851/131252461-0d54f7a8-cd9b-4be6-b118-36c47c803e12.jpeg)
#### Touch (Dark)
![flwqscM](https://user-images.githubusercontent.com/85301851/131252472-d305f9dc-ca91-4cd4-aa65-a3edeae9b0fd.jpeg)

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
7) Restart the browser

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* "browser.tabs.closeTabByDblclick" > "True" in "about:config"
