# *WaveFox*

##### Minimum Requirements
- Firefox 102 / ESR 102
- Windows
- MacOS
- Linux

##### Installation
- Download the `chrome` folder and put it in your user profile folder. For convenience, use `about:profiles`
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `svg.context-properties.content.enabled`
  - `layout.css.color-mix.enabled`

##### v1.2.103 Beta
- Specify the desired shape of the tabs

  - `Style.ProtonTabs-Enabled`
  - `Style.PhotonTabs-Enabled`
  - `Style.WaveFoxTabs-Enabled`
  - `Style.ChromeTabs-Enabled`
  - `Style.EdgeTabs-Enabled`
  - `Style.AustralisTabs-Enabled`
  - `Style.LegacyChromeTabs-Enabled`

- For compatibility with the ESR

  - `userChrome.EsrCompatibility-Enabled`

##### v1.2.102
- Specify the desired shape of the tabs. Create and activate one of the keys below

  - `Style.Proton`
  - `Style.Photon`
  - `Style.WaveFox`
  - `Style.Chrome`
  - `Style.Edge`
  - `Style.Australis`
  - `Style.Chrome-Old`

- For compatibility with the ESR, use the key below

  - `ESR-Compatibility-Enabled`

- Create and activate other keys. This step is optional

### How to create keys?
##### You need to restart your browser for the changes to take effect
![изображение](https://user-images.githubusercontent.com/85301851/151872252-87ff2a81-cb34-4bac-94fb-304f8f5210eb.png)
![изображение](https://user-images.githubusercontent.com/85301851/151872514-15bd77fd-929e-4d4d-a0e1-fa89385e0d0a.png)

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

### Windows System Effects
Works with modern versions of Windows 11 / Windows 10. System effects must be supported on the operating system side. Otherwise, you need third-party software, such as MikaForEveryone. Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/160720915-a055134a-357c-44cc-a638-8dd56e869111.png)

Download and install MicaForEveryone from the link below.

https://github.com/minusium/MicaForEveryone/releases

##### v1.2.103 Beta
- `userChrome.WindowsSystemEffects-Enabled`

##### v1.2.102
- `Style.Win11-Mica-Acrylic`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

##### v1.2.103 Beta
- `userChrome.SemiTransparentToolbar-Enabled`
- `userChrome.TransparentToolbar-Enabled`

##### v1.2.102
- `Style.Toolbar-Transparency-Low`
- `Style.Toolbar-Transparency-Medium`
- `Style.Toolbar-Transparency-High`
- `Style.Toolbar-Full-Transparency`

### Linux Transparency
Requires Linux with transparency support. Tested on Linux Manjaro KDE + ForceBlur. Transparency is active for all modes, but does not work everywhere. This may change with future browser updates. Works only with the system theme.

![изображение](https://user-images.githubusercontent.com/85301851/173119832-e82bc2f7-eda7-4167-9dcd-ccca50383816.png)

##### v1.2.103 Beta
- `userChrome.LinuxSemiTransparency-Enabled`
- `userChrome.LinuxTransparency-Enabled`
- `gfx.webrender.all` (Required key)

##### v1.2.102
- `Style.Linux-Transparency-Enabled`
- `gfx.webrender.all`

### Colorways

##### 1.2.103 Beta
https://www.reddit.com/r/firefox/comments/uq26ao/bringing_back_your_preferred_colorways/?utm_source=share&utm_medium=web2x&context=3

##### 1.2.102
Use with light/dark themes. On the system does not work.

##### Blue
![изображение](https://user-images.githubusercontent.com/85301851/165319656-490ad853-2dea-4eb8-abe4-8c4490b8c686.png)

##### Navy Blue
![изображение](https://user-images.githubusercontent.com/85301851/165319907-0126d0a3-34b5-4ea8-8f25-473acb4b2121.png)

#### Colorways
Light:
- `Style.Colorways-Light-Gray`
- `Style.Colorways-Mint`
- `Style.Colorways-Blue-Green`
- `Style.Colorways-Blue`
- `Style.Colorways-Light-Pink`
- `Style.Colorways-Pink`
- `Style.Colorways-Yellow`
- `Style.Colorways-Orange`

Dark:
- `Style.Colorways-Dark-Grey`
- `Style.Colorways-Gray-Blue`
- `Style.Colorways-Navy-Blue`
- `Style.Colorways-Purple`
- `Style.Colorways-Red`
- `Style.Colorways-Green`

### Additional Container Indicator
![изображение](https://user-images.githubusercontent.com/85301851/161597087-fc818bc5-c60e-48a9-8eb9-1bcafc030607.png)

##### 1.2.103 Beta
- `userChrome.AdditionalContainerIndicator-Enabled`

##### 1.2.102
- `Style.Additional-Container-Indicator`

### Tab Bar Highlight
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### v1.2.103 Beta
- `userChrome.LowBorderSaturation-Enabled`
- `userChrome.HighBorderSaturation-Enabled`
- `userChrome.LowShadowSaturation-Enabled`
- `userChrome.HighShadowSaturation-Enabled`

##### v1.2.102

Shadows are formed from a combination of blur and saturation. There are two shadows available for use.

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

### Tab Separators

![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

##### v1.2.103 Beta

- `userChrome.TabSeparators-Enabled`

##### v1.2.102

- `Style.Separators-Saturation-Low`
- `Style.Separators-Saturation-Normal`
- `Style.Separators-Saturation-High`
- `Style.Separators-Saturation-Very-High`

### Menu Density
By default context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

##### v1.2.103 Beta
- `userChrome.CompactContextMenu-Enabled`
- `userChrome.NormalContextMenu-Enabled`
- `userChrome.TouchContextMenu-Enabled`

##### v1.2.102
- `Style.Context-Menus-Compact`
- `Style.Context-Menus-Normal`
- `Style.Context-Menus-Touch`

### Icons

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

##### v1.2.103 Beta
- `userChrome.RegularMenuIcons-Enabled`
- `userChrome.FilledMenuIcons-Enabled`

##### v1.2.102
- `Style.Menu-Icons-Regular`
- `Style.Menu-Icons-Filled`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

##### v1.2.103 Beta
- `userChrome.DragSpaceAboveTabsWindowedMode-Disabled`
- `userChrome.DragSpaceAboveTabsMaximizedMode-Enabled`
- `userChrome.DragSpaceAboveTabsFullscreenMode-Enabled`

##### v1.2.102
- `Style.Left-Drag-Space-Disabled`
- `Style.Right-Drag-Space-Disabled`

##### Windowed Mode
- `Style.Drag-Space-Above-Tabs-Windowed-Mode-Low`
- `Style.Drag-Space-Above-Tabs-Windowed-Mode-Medium`
- `Style.Drag-Space-Above-Tabs-Windowed-Mode-High`
- `Style.Drag-Space-Above-Tabs-Windowed-Mode-Very-High`

##### Maximized Mode
- `Style.Drag-Space-Above-Tabs-Maximized-Mode-Low`
- `Style.Drag-Space-Above-Tabs-Maximized-Mode-Medium`
- `Style.Drag-Space-Above-Tabs-Maximized-Mode-High`
- `Style.Drag-Space-Above-Tabs-Maximized-Mode-Very-High`

##### Fullscreen Mode
- `Style.Drag-Space-Above-Tabs-Fullscreen-Mode-Low`
- `Style.Drag-Space-Above-Tabs-Fullscreen-Mode-Medium`
- `Style.Drag-Space-Above-Tabs-Fullscreen-Mode-High`
- `Style.Drag-Space-Above-Tabs-Fullscreen-Mode-Very-High`

### Pinned Tabs Width (v1.2.102)
Ability to control the width of pinned tabs.

No Offset
![изображение](https://user-images.githubusercontent.com/85301851/152679216-f1303454-5f42-487b-854e-9f6874a46759.png)

Very High
![изображение](https://user-images.githubusercontent.com/85301851/152679258-37628eff-ac26-4dab-b90f-838687867d79.png)

- `Style.Pinned-Tabs-Width-Offset-Low`
- `Style.Pinned-Tabs-Width-Offset-Medium`
- `Style.Pinned-Tabs-Width-Offset-High`
- `Style.Pinned-Tabs-Width-Offset-Very-High`

### Selected Tab Highlight
![изображение](https://user-images.githubusercontent.com/85301851/170877154-44db11c2-02ce-4aab-821e-c3cc68f26a2d.png)

##### v1.2.103 Beta
- `userChrome.SelectedTabHighlight-Enabled`

##### v1.2.102
On all themes except Proton/Photon, the indicator may not be visible on pinned tabs. Use the option to offset the width of pinned tabs. A very high offset is recommended.

- `Style.Tab-Indicator-Enabled`
