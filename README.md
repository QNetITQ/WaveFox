# *WaveFox*

##### Minimum Requirements
- Firefox 115
- Firefox 115 ESR
- Windows
- MacOS
- Linux

###### Have a question not related to this project? These resources will help you
  
[Firefox community (Former r/firefox)](https://fedia.io/m/firefox) / [Firefox CSS community (Former r/Firefox CSS)](https://lemmy.world/c/firefoxcss)

##### Installation

[Download Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release) / [Download WaveFox](https://github.com/QNetITQ/WaveFox/releases)

- Download the `chrome` folder and put it in your user profile folder. For convenience, use `about:profiles`
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `layout.css.has-selector.enabled`
  - `svg.context-properties.content.enabled` (Activate this key if the menu icons don't follow the general design color. Previously seen only on MacOS)
  
- Specify the desired shape of the tabs.

  <details>
  <summary>Creation of keys</summary>
  Restart your browser for the changes to take effect.
  
  ![изображение](https://user-images.githubusercontent.com/85301851/180253017-22325fad-2f53-47f5-b409-618ca7fe6084.png)
  ![изображение](https://user-images.githubusercontent.com/85301851/180253209-3e6965a9-641a-4ac2-bf3d-242ac8b3451c.png)
  </details>
  
  ##### Tabs (Option 1)
  ![1](https://user-images.githubusercontent.com/85301851/233114797-1495824d-9f46-474f-aeb2-a8dcc5608066.PNG)
  - `userChrome.Tabs.Option1.Enabled`
  
  ##### Tabs (Option 2)
  ![2](https://user-images.githubusercontent.com/85301851/233114845-1904b615-7c6b-43c4-9422-ae6b2ed6e3b1.PNG)
  - `userChrome.Tabs.Option2.Enabled`
  
  ##### Tabs (Option 3)
  ![3](https://user-images.githubusercontent.com/85301851/233114878-baae0abb-2779-453a-9a2f-30e6fd015952.PNG)
  - `userChrome.Tabs.Option3.Enabled`
  
  ##### Tabs (Option 4)
  ![4](https://user-images.githubusercontent.com/85301851/233114921-b386502c-2b73-496b-9536-5350227ae78b.PNG)
  - `userChrome.Tabs.Option4.Enabled`
  
  ##### Tabs (Option 5)
  ![5](https://user-images.githubusercontent.com/85301851/233114950-68595ae9-27dc-4384-8f71-61ae873b1a3b.PNG)
  - `userChrome.Tabs.Option5.Enabled`
  
  ##### Tabs (Option 6)
  ![9](https://user-images.githubusercontent.com/85301851/233115069-913b318e-5503-4d54-916e-e3cbd3626c96.PNG)
  - `userChrome.Tabs.Option6.Enabled`
  
  ##### Tabs (Option 7)
  ![10](https://user-images.githubusercontent.com/85301851/233115104-2a4e527f-15cf-47f9-9a8f-60159a5bb570.PNG)
  - `userChrome.Tabs.Option7.Enabled`
  
  ##### Tabs (Option 8)
  ![11](https://user-images.githubusercontent.com/85301851/233115136-eba3fb57-1591-4318-86ee-ecdf673609b7.PNG)
  - `userChrome.Tabs.Option8.Enabled`
  
  ##### Tabs (Option 9)
  ![12](https://user-images.githubusercontent.com/85301851/233115162-1cd61c70-5826-4712-8692-603b04147660.PNG)
  - `userChrome.Tabs.Option9.Enabled`
  
  ##### Tabs (Option 10)
  ![14](https://user-images.githubusercontent.com/85301851/233115224-fbada5b2-35f8-41bb-81c7-52552e62d829.PNG)
  - `userChrome.Tabs.Option10.Enabled`
  
  ##### Tabs (Option 11)
  ![15](https://user-images.githubusercontent.com/85301851/233115260-c6cb7c9a-192c-4a20-9327-392c6afae755.PNG)
  - `userChrome.Tabs.Option11.Enabled`
  
  ##### Tabs (Option 12)
  ![16](https://user-images.githubusercontent.com/85301851/233115285-feb26903-ab9f-4e38-b28a-7207b0459ebe.PNG)
  - `userChrome.Tabs.Option12.Enabled`

## Optional

### Windows System Effects
Works with modern versions of Windows 11 / Windows 10. System effects must be supported on the operating system side. Otherwise, you need third-party software, such as Mica For Everyone. You also need to disable the accent color in the operating system settings, if it was enabled. Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/160720915-a055134a-357c-44cc-a638-8dd56e869111.png)

Download and install Mica For Everyone from [here](https://github.com/minusium/MicaForEveryone/releases).

- `userChrome.Windows.SystemEffects.Enabled`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `userChrome.Toolbar.Transparency.Low.Enabled`
- `userChrome.Toolbar.Transparency.Medium.Enabled`
- `userChrome.Toolbar.Transparency.High.Enabled`
- `userChrome.Toolbar.Transparency.VeryHigh.Enabled`

### Linux Transparency
Requires Linux with transparency support. Tested on Linux Manjaro KDE + ForceBlur. Transparency is active for all modes, but does not work everywhere. This may change with future browser updates. Works only with the system theme.

![изображение](https://user-images.githubusercontent.com/85301851/173119832-e82bc2f7-eda7-4167-9dcd-ccca50383816.png)

- `userChrome.Linux.Transparency.Enabled`
- `gfx.webrender.all` (Required key)

### Tab Frame
The tab frame consists of type, color and saturation. Not compatible with themes that use a translucent toolbar.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### Light Theme

###### Type
- `userChrome.LightTheme.TabFrameType.Border.Enabled`
- `userChrome.LightTheme.TabFrameType.Shadow.Enabled`
###### Color
- `userChrome.LightTheme.TabFrameColor.Auto.Enabled`
- `userChrome.LightTheme.TabFrameColor.White.Enabled`
- `userChrome.LightTheme.TabFrameColor.Black.Enabled`
###### Saturation
- `userChrome.LightTheme.TabFrameSaturation.Low.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.Medium.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.High.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.VeryHigh.Enabled`

##### Dark Theme

###### Type
- `userChrome.DarkTheme.TabFrameType.Border.Enabled`
- `userChrome.DarkTheme.TabFrameType.Shadow.Enabled`
###### Color
- `userChrome.DarkTheme.TabFrameColor.Auto.Enabled`
- `userChrome.DarkTheme.TabFrameColor.White.Enabled`
- `userChrome.DarkTheme.TabFrameColor.Black.Enabled`
###### Saturation
- `userChrome.DarkTheme.TabFrameSaturation.Low.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.Medium.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.High.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.VeryHigh.Enabled`

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `userChrome.TabSeparatorsLowSaturation-Enabled`
- `userChrome.TabSeparatorsMediumSaturation-Enabled`

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

- `userChrome.DragSpace.Left.Disabled`
- `userChrome.DragSpace.Right.Disabled`
- `userChrome.DragSpace.Top.Windowed.Enabled`
- `userChrome.DragSpace.Top.Maximized.Enabled`
- `userChrome.DragSpace.Top.Fullscreen.Enabled`

### Pinned Tabs Width
![Снимок](https://user-images.githubusercontent.com/85301851/185612113-7bb0445f-8993-45bd-916d-d066e88ea7f4.PNG)

- `userChrome.PinnedTabsWidthLowIncrease-Enabled`
- `userChrome.PinnedTabsWidthHighIncrease-Enabled`

### Selected Tab Indicator
![изображение](https://github.com/QNetITQ/WaveFox/assets/85301851/c5b7c4b8-81d2-4ca2-9944-574af7e88f1d)

- `userChrome.Tabs.SelectedTabIndicator.Enabled`
