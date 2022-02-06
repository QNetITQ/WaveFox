# *WaveFox*
Style in progress. This page is also under construction. 

## Installation
0. Minimum Requirements:
- Firefox 96.0.2 and newer
- Windows 7 and newer
- MacOS 11 and newer
- Linux

1. Download the `chrome` folder and put it in the root folder (Also known as the user profile folder. You can easily get there from `about:profiles`)
2. Go to `about:config` and activate the keys below:
* `toolkit.legacyUserProfileCustomizations.stylesheets`
* `svg.context-properties.content.enabled`
* `layout.css.color-mix.enabled`

#### How to create keys?
![изображение](https://user-images.githubusercontent.com/85301851/151872252-87ff2a81-cb34-4bac-94fb-304f8f5210eb.png)
![изображение](https://user-images.githubusercontent.com/85301851/151872514-15bd77fd-929e-4d4d-a0e1-fa89385e0d0a.png)

3. Specify the desired shape of the tabs. Create and activate one of the keys below:
* `Style.Proton`
* `Style.Photon`
* `Style.WaveFox`
* `Style.Chrome`
* `Style.Edge`
* `Style.Australis`
* `Style.Chrome-Old`
4. Create and activate other keys. This step is optional

| Style | Light | Dark |
|-------|-------|------|
| WaveFox | ![изображение](https://user-images.githubusercontent.com/85301851/151183317-12228b83-7e4d-4daf-b7ae-ee333c94aa54.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183202-e4e183b3-80f3-4aa6-a95b-e40c1ca91a61.png) |
| Proton | ![изображение](https://user-images.githubusercontent.com/85301851/151183646-82878986-78d9-43df-956e-21380f7d04e5.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151183808-76a9aeff-34df-46f8-8f15-a120058580ee.png) |
| Photon | ![изображение](https://user-images.githubusercontent.com/85301851/151182545-934db216-a15b-449d-b6f8-3f0c8a5f9bc9.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151182383-1b1a1833-d5b8-4b7c-8476-a193bdb7c015.png) |
| Chrome | ![изображение](https://user-images.githubusercontent.com/85301851/151187719-5e64c2f0-d01c-4248-b80e-c275b4e89677.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151187617-1b4f5d55-0bc6-4a0a-a284-822deaeb8a8c.png) |
| Edge | ![изображение](https://user-images.githubusercontent.com/85301851/151188052-dd550152-e7e7-4ad6-9df2-4b4bc8fa41cf.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188156-a80e9e38-5e5f-440e-9864-6958e10b736d.png) |
| Chrome (Legacy) | ![изображение](https://user-images.githubusercontent.com/85301851/151188819-8ac900d2-f126-4302-8824-f507a80e5f1b.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151188707-3ed5a636-e3d2-456b-9fa7-f7e5f8991b27.png) |
| Australis | ![изображение](https://user-images.githubusercontent.com/85301851/151189110-5de939b8-f6d4-4a40-930b-f15c07254be5.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151189212-52918558-9969-4127-bc6d-30ab70b73949.png) |

## Optional

### Shadows
There are two shadows available for use. Each shadow is completely independent. In most situations, one shadow is enough, but there are situations where a second shadow can be useful. Shadows are formed from a combination of blur and saturation.

##### Low Blur + Very High Saturation
![изображение](https://user-images.githubusercontent.com/85301851/152011458-07a0790f-cf1e-4e80-b267-62334a36377c.png)
##### Very High Blur + Low Saturation
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)
##### A combination of shadows from the screenshots above
![изображение](https://user-images.githubusercontent.com/85301851/152012361-a2660ff1-eb59-44bf-910b-cf626a0c1d3e.png)

#### Main Shadow
Blur:
- `Style.Main-Shadow-Blur-Low`
- `Style.Main-Shadow-Blur-Medium`
- `Style.Main-Shadow-Blur-High`
- `Style.Main-Shadow-Blur-Very-High`

Saturation:
- `Style.Main-Shadow-Saturation-Low`
- `Style.Main-Shadow-Saturation-Medium`
- `Style.Main-Shadow-Saturation-High`
- `Style.Main-Shadow-Saturation-Very-High`

#### Additional Shadow
Blur:
- `Style.Additional-Shadow-Blur-Low`
- `Style.Additional-Shadow-Blur-Medium`
- `Style.Additional-Shadow-Blur-High`
- `Style.Additional-Shadow-Blur-Very-High`

Saturation:
- `Style.Additional-Shadow-Saturation-Low`
- `Style.Additional-Shadow-Saturation-Medium`
- `Style.Additional-Shadow-Saturation-High`
- `Style.Additional-Shadow-Saturation-Very-High`

### Separators
It is possible to set the saturation of tab separators and disable the first separator.

##### Low Saturation
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)
##### Very High Saturation
![изображение](https://user-images.githubusercontent.com/85301851/152351155-3f7e22a7-b7f0-453a-88ff-0b708b50a955.png)

#### Separators

- `Style.Separators-Saturation-Low`
- `Style.Separators-Saturation-Normal`
- `Style.Separators-Saturation-High`
- `Style.Separators-Saturation-Very-High`
- `Style.Disable-First-Separator`

### AMO
Compatible with AMO. Since shadows do not work with these themes, the selected tab may be hard to see. It is possible to activate the tab frame for better visibility.

##### Without Tab Frame 
![изображение](https://user-images.githubusercontent.com/85301851/152528816-fd21f6ff-0a16-4c8e-bb2a-aaf69501f365.png)
##### With Tab Frame
![изображение](https://user-images.githubusercontent.com/85301851/152529473-628eaf15-6603-4282-b5d4-a146f818b318.png)

#### AMO Tab Frame

- `Style.AMO-Tab-Frame`

### Density
By default, context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

#### Density
- `Style.Context-Menus-Compact`
- `Style.Context-Menus-Normal`
- `Style.Context-Menus-Touch`

### Icons
There are two types of fluent style icons from Microsoft.

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

#### Icons
- `Style.Menu-Icons-Regular`
- `Style.Menu-Icons-Filled`













### Various interface densities
| Compact Plus | Compact | Normal | Touch |
|--------------|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151196005-5a35bb8f-faa1-49e1-a092-fffeeb24a6ec.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151195648-d0120335-87d0-41fa-afea-4daa7ae4057b.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151195788-8ed8a19b-64a0-48cc-9383-f582210cf3b3.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151195144-9424311d-fc1e-4d58-b2eb-38c06406dbb8.png) |














### Pinned Tabs 
Ability to control the width of pinned tabs

##### No Offset
![изображение](https://user-images.githubusercontent.com/85301851/152679216-f1303454-5f42-487b-854e-9f6874a46759.png)

##### Very High Offset
![изображение](https://user-images.githubusercontent.com/85301851/152679258-37628eff-ac26-4dab-b90f-838687867d79.png)

#### Pinned Tabs Width
- `Style.Pinned-Tabs-Width-Offset-Low`
- `Style.Pinned-Tabs-Width-Offset-Medium`
- `Style.Pinned-Tabs-Width-Offset-High`
- `Style.Pinned-Tabs-Width-Offset-Very-High`














### New Tab Button Like Pinned Tab
| New Tab Button | New Tab Button Like Pinned Tab |
|----------------|--------------------------------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151203456-3ead802b-110c-4687-919f-27cb26076c34.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151203609-e3d723a9-fcc3-4887-a16a-b20e3364dc52.png) |

### Drag space
You can control this setting in the "Custom settings" at the top of the css file
| Left Drag Space (0px) | Left Drag Space (40px) | Top Drag Space (0px) | Top Drag Space (8px) | Right Drag Space (0px) | Right Drag Space (40px) |
|-----------------------|------------------------|----------------------|----------------------|------------------------|-------------------------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151207587-ee6aac0a-529a-44fa-a349-05a71f7e0e42.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151207693-4ec2cefc-ae72-4bac-aadf-5d03c5821fa8.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151208756-236844a6-c2a2-4275-aadf-245872e5bf43.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151208590-b35da78d-99d2-4815-a465-23bb1cd78b3e.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151208486-ffadb816-5f58-4ba3-9c6f-8da735c1d5e8.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151208387-f6311b91-58d3-474f-b6c4-2eb99cc891ff.png) |

### Tab media icons and status bar
| Light | Dark |
|-------|------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151214450-d31ad03c-71d6-468a-9abb-8a43debf4fb8.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151214537-a130ad46-d57b-498b-ab53-863f9b5203b5.png) |

### Accent color (Windows 11 / Windows 10)
Accent color only works with system theme
| Light | Dark |
|-------|------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151212851-3aee4b2d-3766-47de-b701-1978ff7c6648.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151213171-70c40b46-24ff-4e19-868a-e9cf902ad2aa.png) |


-----------------------------------------------

Tabs can be made even more compact. Create the key below:
* `Style.Compact-Plus` > `True`

The new tab button may look like a pinned tab. Create the key below:
* `Style.New-Tab-Button-Like-Pinned-Tab` > `True`
