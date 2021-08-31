# *WaveFox*

### Supported operating systems:
* Windows 10
* Windows 8.1
* Windows 7
* Linux 
* MacOS

### Features:
* Tabs with a more classic look
* All interface densities supported
* You can control the size of the drag space for each density in the "Custom Settings" section
* Reduced context menus. You can control the size of the context menus for each density in the "Custom Settings" section
* You can control the size and color of the shadows for each density in the "Custom Settings" section (Tab bar only)
* Website icons and media icons on tabs are always visible
* Returned accent color to Windows 10
* Style is compatible with themes from the repository

### Screenshots:
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
-----------------------------------------------------------------------------------------------------------------------

### Installation
1) Enter "about:profiles" in the address bar and open the root directory folder
2) Create a folder "chrome"
3) Download the "userChrome.css" file
4) Put the file "userChrome.css" in "chrome"
5) Enter "about:config" in the address bar
6) Looking for and changing the value of the following keys:
* "toolkit.legacyUserProfileCustomizations.stylesheets" > "True"
* "svg.context-properties.content.enabled" > "True"
* "layout.css.color-mix.enabled" > "True"
7) "browser.tabs.tabMinWidth":
* Compact > Minimum: 88 Recommended: 106
* Normal > Minimum: 94 Recommended: 112
* Touch > Minimum: 90 Recommended: 118
8) Restart the browser
