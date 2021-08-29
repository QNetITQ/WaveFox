# *WaveFox*

### Supported operating systems:
* Windows 10
* Windows 8.1
* Windows 7
* Linux 
* MacOS

### Features:
* All interface densities supported
* You can control the size of the drag space for each density in the "Custom Settings" section
* Reduced context menus. You can control the size of the context menus for each density in the "Custom Settings" section
* You can control the size and color of the shadows for each density in the "Custom Settings" section (Tab bar only)
* Website icons and media icons on tabs are always visible 
* Style is compatible with themes from the repository

### Screenshots




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
