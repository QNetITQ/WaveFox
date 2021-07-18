# *WaveFox*
*(Style with unique shape of tabs)*

## Supported operating systems:
* Windows 10
* Windows 8.1
* Windows 7
* Linux 
* MacOS

## Supported interface densities:
* Compact (Non-system context menus are reduced. System menus are reduced only in Windows 10)
* Normal (Context menus unchanged)
* Touch (Context menus unchanged)

### Compatible with themes from the repository

### Customize the style for yourself in the "User preferences" section

### Windows 10
![Windows 10](https://user-images.githubusercontent.com/85301851/123125139-ee92c380-d450-11eb-8458-1e12fdc7e847.png)

### Windows 8
![Windows 8](https://user-images.githubusercontent.com/85301851/123125196-f94d5880-d450-11eb-93c3-c1d0331a8069.png)

### Windows 7
![Windows 7](https://user-images.githubusercontent.com/85301851/123125224-fe120c80-d450-11eb-8410-f9d90e5d5d9b.png)

# Installation
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
