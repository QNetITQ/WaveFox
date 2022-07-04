# *WaveFox*

##### Minimum Requirements
- Firefox 102 / ESR 102
- Windows
- MacOS
- Linux

##### Installation

##### Installation instructions for version 1.2.102 are located in the corresponding tag.

- Download the `chrome` folder and put it in your user profile folder. For convenience, use `about:profiles`
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `svg.context-properties.content.enabled`
  - `layout.css.color-mix.enabled`

- Specify the desired shape of the tabs

  - `userChrome.ProtonTabs-Enabled`
  - `userChrome.PhotonTabs-Enabled`
  - `userChrome.WaveFoxTabs-Enabled`
  - `userChrome.ChromeTabs-Enabled`
  - `userChrome.EdgeTabs-Enabled`
  - `userChrome.AustralisTabs-Enabled`
  - `userChrome.LegacyChromeTabs-Enabled`

- For compatibility with the ESR

  - `userChrome.EsrCompatibility-Enabled`

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

- `userChrome.WindowsSystemEffects-Enabled`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `userChrome.SemiTransparentToolbar-Enabled`
- `userChrome.TransparentToolbar-Enabled`

### Linux Transparency
Requires Linux with transparency support. Tested on Linux Manjaro KDE + ForceBlur. Transparency is active for all modes, but does not work everywhere. This may change with future browser updates. Works only with the system theme.

![изображение](https://user-images.githubusercontent.com/85301851/173119832-e82bc2f7-eda7-4167-9dcd-ccca50383816.png)

- `userChrome.LinuxSemiTransparency-Enabled`
- `userChrome.LinuxTransparency-Enabled`
- `gfx.webrender.all` (Required key)

### Colorways
https://www.reddit.com/r/firefox/comments/uq26ao/bringing_back_your_preferred_colorways/?utm_source=share&utm_medium=web2x&context=3

### Additional Container Indicator
![изображение](https://user-images.githubusercontent.com/85301851/161597087-fc818bc5-c60e-48a9-8eb9-1bcafc030607.png)

- `userChrome.AdditionalContainerIndicator-Enabled`

### Tab Bar Highlight
It is possible to enable border and shadow at the same time.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

- `userChrome.LowBorderSaturation-Enabled`
- `userChrome.HighBorderSaturation-Enabled`
- `userChrome.LowShadowSaturation-Enabled`
- `userChrome.HighShadowSaturation-Enabled`

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `userChrome.TabSeparators-Enabled`

### Menu Density
By default context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

- `userChrome.CompactContextMenu-Enabled`
- `userChrome.NormalContextMenu-Enabled`
- `userChrome.TouchContextMenu-Enabled`

### Icons

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

- `userChrome.RegularMenuIcons-Enabled`
- `userChrome.FilledMenuIcons-Enabled`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

- `userChrome.DragSpaceAboveTabsWindowedMode-Disabled`
- `userChrome.DragSpaceAboveTabsMaximizedMode-Enabled`
- `userChrome.DragSpaceAboveTabsFullscreenMode-Enabled`

### Selected Tab Highlight
![изображение](https://user-images.githubusercontent.com/85301851/170877154-44db11c2-02ce-4aab-821e-c3cc68f26a2d.png)

- `userChrome.SelectedTabHighlight-Enabled`
