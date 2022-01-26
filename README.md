# *WaveFox*


## Overview

### Various tab shapes supported

| Style | Light | Dark | AMO |
|-------|-------|------|-----|
| WaveFox | ![изображение](https://user-images.githubusercontent.com/85301851/151183317-12228b83-7e4d-4daf-b7ae-ee333c94aa54.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183202-e4e183b3-80f3-4aa6-a95b-e40c1ca91a61.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183033-6d5eb436-59a7-470f-8437-06d5dcebda5f.png) |
| Proton | ![изображение](https://user-images.githubusercontent.com/85301851/151183646-82878986-78d9-43df-956e-21380f7d04e5.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183808-76a9aeff-34df-46f8-8f15-a120058580ee.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183932-b80b8732-6d2e-43d8-a572-079364c08db8.png) |
| Photon | ![изображение](https://user-images.githubusercontent.com/85301851/151182545-934db216-a15b-449d-b6f8-3f0c8a5f9bc9.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151182383-1b1a1833-d5b8-4b7c-8476-a193bdb7c015.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151182686-d50a3164-0d25-412b-ab5f-6df1d6849e4f.png) |
| Chrome | ![изображение](https://user-images.githubusercontent.com/85301851/151187719-5e64c2f0-d01c-4248-b80e-c275b4e89677.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151187617-1b4f5d55-0bc6-4a0a-a284-822deaeb8a8c.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151187459-a8e4895c-f217-4e2f-b4de-4fa28d1e7739.png) |
| Edge | ![изображение](https://user-images.githubusercontent.com/85301851/151188052-dd550152-e7e7-4ad6-9df2-4b4bc8fa41cf.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188156-a80e9e38-5e5f-440e-9864-6958e10b736d.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188255-0e2df491-674b-48e9-9cbe-36d5c0e1a360.png) |
| Chrome (Legacy) | ![изображение](https://user-images.githubusercontent.com/85301851/151188819-8ac900d2-f126-4302-8824-f507a80e5f1b.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188707-3ed5a636-e3d2-456b-9fa7-f7e5f8991b27.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188546-7abb257c-235a-420e-b841-13657b07968d.png) |
| Australis | ![изображение](https://user-images.githubusercontent.com/85301851/151189110-5de939b8-f6d4-4a40-930b-f15c07254be5.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151189212-52918558-9969-4127-bc6d-30ab70b73949.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151189329-c6c48d18-091c-4f62-903a-d4dc08eb0ac8.png) |

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
