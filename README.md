# *WaveFox*


## Overview

### Various tab shapes supported
| Proton | WaveFox | Chrome | Edge | Photon | Legacy Chrome | Australis |
|--------|---------|--------|------|--------|---------------|-----------|
| ![изображение](https://user-images.githubusercontent.com/85301851/150574473-007bc3e8-2953-4cfd-b4b5-4fc3a7299144.png) ![изображение](https://user-images.githubusercontent.com/85301851/150574613-b0a0d147-8038-445f-acba-8e8741448cc5.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150574943-ea318014-59ee-4693-b34e-e0b5fc045450.png) ![изображение](https://user-images.githubusercontent.com/85301851/150574825-380c6dec-842f-40e2-be12-0ffb466d69c8.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150575421-4e303d0a-e2a3-4c5c-89b5-9a3a613e1196.png) ![изображение](https://user-images.githubusercontent.com/85301851/150575482-272c841a-7588-43c6-952d-d32db3e8aa63.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150575763-a828deb2-6430-4990-932e-b988a2df39a2.png) ![изображение](https://user-images.githubusercontent.com/85301851/150575674-7ea2712e-ac8d-407a-bf77-8bb0de658103.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150575933-5780a858-7ae6-434b-866e-480e25a50744.png) ![изображение](https://user-images.githubusercontent.com/85301851/150576004-00aed1d0-b523-43d3-9914-38e71aa82be0.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150576190-938a2bb8-289d-4e35-a8af-4bad8c481c8a.png) ![изображение](https://user-images.githubusercontent.com/85301851/150576123-fbbbb59d-5ea3-4d69-9d33-28cb77c4e9b8.png) | ![изображение](https://user-images.githubusercontent.com/85301851/150576281-ea0110d1-9492-4425-b07a-3993b64f78d7.png) ![изображение](https://user-images.githubusercontent.com/85301851/150576355-44444c1d-b18e-4b96-99ba-9767c56b895b.png) |

## Supported operating systems
* Windows 10 and newer (Full support)
* Linux (Full support)
* MacOS 11 and newer (Partial support)
* Windows 7/8 (Partial support)

#### Full support
The style was tested by the author. All visuals are supported and updated as needed

#### Partial support
The style has not been tested by the author. Visual effects unique to these systems (Aero / Vibrancy, etc.) are not supported, but will work if Mozilla activates them by default

#### Unsupported systems
The style works only with systems from the list of supported

## Features
* All themes supported
* All interface densities supported
* You can control the size of the drag space in the "Custom Settings" section
* You can control the size of the context menus in the "Custom Settings" section
* You can control the size and color of the shadows in the "Custom Settings" section (Tab bar only)
* Media icons on tabs are always visible
* Accent color (Windows 11 / Windows 10)
* Various forms of tabs are supported
* Menu icons support
* New tab button like pinned tab
* Ability to control the length of pinned tabs 

## Installation
1. Download the `chrome` folder and put it in the root folder (also known as the user profile folder)
2. Go to the `about:config` and switch the keys below:
* `toolkit.legacyUserProfileCustomizations.stylesheets` > `True`
* `svg.context-properties.content.enabled` > `True`
* `layout.css.color-mix.enabled` > `True`
3. Select the desired shape of the tabs. Сreate one of the keys below:
* `Style.Proton` > `True`
* `Style.Photon` > `True`
* `Style.WaveFox` > `True`
* `Style.Chrome` > `True`
* `Style.Edge` > `True`
* `Style.Australis` > `True`
* `Style.Chrome-Old` > `True`

If point 3 is not fulfilled, the tabs and everything connected with them will be by default, as the Mozilla intended.

Tabs can be made even more compact. Create the key below:
* `Style.Compact-Plus` > `True`

The new tab button may look like a pinned tab. Create the key below:
* `Style.New-Tab-Button-Like-Pinned-Tab` > `True`

To enable icons, create one of the keys below:
* `Style.Menu-Icons-Regular` > `True`
* `Style.Menu-Icons-Filled` > `True`

## Tabs (Overflow mode)
Removed the ability to close tabs with the left mouse button in overflow mode to protect the user from accidental actions. Use the methods below to close tabs:
* Through the context menu
* By clicking on the mouse wheel
* `browser.tabs.closeTabByDblclick` > `True`
* `Ctrl + W` / `Command + W` closes the current tab
