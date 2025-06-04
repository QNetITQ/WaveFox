# *WaveFox*

![WaveFox_Preview](https://github.com/QNetITQ/WaveFox/assets/85301851/268bda8c-b987-45d1-966b-59992c18e66e)

## Installation

[Download Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release) / [Download WaveFox](https://github.com/QNetITQ/WaveFox/releases) / [WaveFox Nightly](https://github.com/QNetITQ/WaveFox/tree/WaveFox-Nightly)

<details>
  <summary>WaveFox v1.8.140 ESR</summary>

- ##### Minimum Requirements
  - Firefox 140 ESR
  - Windows / MacOS / Linux

- Download the `chrome` folder and put it in your user profile folder
- Go to `about:config` and activate the key `toolkit.legacyUserProfileCustomizations.stylesheets`

## Optional

### Tab Shapes

##### Shape 1
![изображение](https://github.com/user-attachments/assets/98d808c0-de87-4328-bd19-c885060adaec)

- `WaveFox.Tabs.Shape` > 1
  
##### Shape 2
![изображение](https://github.com/user-attachments/assets/15244c8d-e073-47f7-a84c-500bcf1f056d)

- `WaveFox.Tabs.Shape` > 2
  
##### Shape 3
![изображение](https://github.com/user-attachments/assets/ec6f06df-5f83-4408-8f39-8480cff5ca8b)

- `WaveFox.Tabs.Shape` > 3
  
##### Shape 4
![изображение](https://github.com/user-attachments/assets/112843be-7182-4a48-bc04-0f9211ddf7c7)

- `WaveFox.Tabs.Shape` > 4
  
##### Shape 5
![изображение](https://github.com/user-attachments/assets/cd6fb4a9-8cc7-4fd1-9f26-9acef5a4a121)

- `WaveFox.Tabs.Shape` > 5
  
##### Shape 6
![изображение](https://github.com/user-attachments/assets/21c6644f-f579-419d-92b8-cb614a726742)

- `WaveFox.Tabs.Shape` > 6
  
##### Shape 7
![изображение](https://github.com/user-attachments/assets/b648e7c3-2dc4-478d-9ee0-8ac9b727c37d)

- `WaveFox.Tabs.Shape` > 7
  
##### Shape 8
![изображение](https://github.com/user-attachments/assets/8cce9ecd-2005-4aba-9c66-6e49f2ccb76a)

- `WaveFox.Tabs.Shape` > 8
  
##### Shape 9
![изображение](https://github.com/user-attachments/assets/d720364a-88f3-4fe6-a61f-0747f93e5f20)

- `WaveFox.Tabs.Shape` > 9
  
##### Shape 10
![изображение](https://github.com/user-attachments/assets/88d1d2de-2d0c-4837-b15f-a10694e5093a)

- `WaveFox.Tabs.Shape` > 10
  
##### Shape 11
![изображение](https://github.com/user-attachments/assets/084a7915-12d9-44da-a3d1-a0b17267d356)

- `WaveFox.Tabs.Shape` > 11
  
##### Shape 12
![изображение](https://github.com/user-attachments/assets/2d38da42-f304-468c-bb52-1190d936bc19)

- `WaveFox.Tabs.Shape` > 12

### Windows 10 Transparency
Install [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass). Configure to your liking and activate the keys below. Works only with the system theme.
![изображение](https://github.com/user-attachments/assets/632c972f-b48a-4ca6-8c69-28859e34485b)

- `WaveFox.Windows10.Transparency.Enabled` and `browser.tabs.inTitlebar > 1`

### Linux Transparency
Requires Linux with transparency support. Works only with the system theme.

![Снимок5](https://github.com/QNetITQ/WaveFox/assets/85301851/3b4dcfc8-217d-48a1-aba7-1621f9375f67)

- `WaveFox.Linux.Transparency.Enabled` and `browser.tabs.inTitlebar > 1`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `WaveFox.Toolbar.Transparency` > 1 or 2 or 3 or 4 and `browser.tabs.inTitlebar > 1`

### Tab Bar Shadows
Works only with System / Light / Dark theme.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### Shadows (Light Theme)
- `WaveFox.LightTheme.Tabs.Shadows` > 1 or 2 or 3 or 4

##### Shadows (Dark Theme)
- `WaveFox.DarkTheme.Tabs.Shadows` > 1 or 2 or 3 or 4

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `WaveFox.Tabs.Separators` > 1 or 2 or 3 or 4

### Background For Inactive Tabs
![изображение](https://github.com/user-attachments/assets/56fc829a-3cb6-4009-a58c-485fc84f65e9)

- `WaveFox.Tabs.Background.Inactive.Enabled`

### Icons (MrOtherGuy / Lepton)
This is third-party code. I will update this code according to the original source.

![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png)

- `svg.context-properties.content.enabled` (Required key)
- `WaveFox.Icons` > 1 or 2 (Required key)

The keys below are relevant only for the second option.
  - `userChrome.icon.panel_full` or `userChrome.icon.panel_photon`
  - `userChrome.icon.library`
  - `userChrome.icon.panel`
  - `userChrome.icon.menu`
  - `userChrome.icon.context_menu`
  - `userChrome.icon.global_menu`
  - `userChrome.icon.global_menubar`
  - `userChrome.icon.1-25px_stroke`
  - `userChrome.icon.account_image_to_right`
  - `userChrome.icon.account_label_to_right`
  - `userChrome.icon.menu.full`
  - `userChrome.icon.global_menu.mac`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

- `WaveFox.DragSpace.Tabs` > 1 or 2 or 3
- `WaveFox.DragSpace.TabBarLeftSide.Disabled`
- `WaveFox.DragSpace.TabBarRightSide.Disabled`

### Selected Tab Indicator
![изображение](https://github.com/user-attachments/assets/e6d221d2-38b0-4890-9bbc-d5abc9b027c0)

- `WaveFox.Tabs.SelectedTabIndicator.Enabled`

### Tabs Below URL
![Снимок](https://github.com/QNetITQ/WaveFox/assets/85301851/514cf30d-a417-48cb-bfd1-0e77c9df1bf4)

- `WaveFox.TabsBelowURL.Enabled` and `browser.tabs.inTitlebar > 0`

### One Line
![Снимок](https://github.com/QNetITQ/WaveFox/assets/85301851/05bba314-643d-46f3-a09c-b3ac31f9761d)

- `WaveFox.OneLine` > 1 or 2

### Floating Web Page
![изображение](https://github.com/user-attachments/assets/26a19f9a-642b-4a10-a4f9-80d87cc42bdc)

- `WaveFox.WebPage.Floating.Enabled`

### Transparent Web Page (Experimentally)
Works only with system theme. Requires transparency support from the operating system. The quality of this option depends heavily on the specific website.
![изображение](https://github.com/user-attachments/assets/99afc380-027a-46b3-b0d6-5cdf3c55a33e)

- `WaveFox.WebPage.Transparency` > 1 or 2 and `browser.tabs.allow_transparent_browser` (1 - Browser windows only / 2 - Browser windows and all websites)

</details>

<details>
  <summary>WaveFox v1.6.128 ESR</summary>

- ##### Minimum Requirements
  - Firefox 128 ESR
  - Windows / MacOS / Linux

- Download the `chrome` folder and put it in your user profile folder
- Go to `about:config` and activate the key `toolkit.legacyUserProfileCustomizations.stylesheets`
- Specify the desired shape of the tabs

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

  ##### Tabs (Option 13)
  ![изображение](https://github.com/QNetITQ/WaveFox/assets/85301851/906299f9-94e6-4a69-9191-202c94525ae6)
  - `userChrome.Tabs.Option13.Enabled`

## Optional

### Adding third-party styles
Go to the `chrome` folder and paste the desired styles inside the `third_party_custom_styles.css` file. Please note that this file has maximum execution priority. It will overwrite all styles, regardless of selector specificity. I make no guarantees of compatibility and will not resolve any style conflicts you may encounter.

- `userChrome.Style.ThirdParty.Enabled`

<i>Functionality that will not be part of the style will be published in the [discussions](https://github.com/QNetITQ/WaveFox/discussions) section as requests from users.</i>

### Linux Transparency
Requires Linux with transparency support. Works only with the system theme.

![Снимок5](https://github.com/QNetITQ/WaveFox/assets/85301851/3b4dcfc8-217d-48a1-aba7-1621f9375f67)

- `userChrome.Linux.Transparency.Low.Enabled`
- `userChrome.Linux.Transparency.Medium.Enabled`
- `userChrome.Linux.Transparency.High.Enabled`
- `userChrome.Linux.Transparency.VeryHigh.Enabled`
- `browser.tabs.inTitlebar` > `1` (Required key)

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `userChrome.Toolbar.Transparency.Low.Enabled`
- `userChrome.Toolbar.Transparency.Medium.Enabled`
- `userChrome.Toolbar.Transparency.High.Enabled`
- `userChrome.Toolbar.Transparency.VeryHigh.Enabled`

### Tab Bar Borders and Shadows
Incompatible with AMO themes.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### Borders (Light Theme)
- `userChrome.LightTheme.Tabs.Borders.Saturation.Low.Enabled`
- `userChrome.LightTheme.Tabs.Borders.Saturation.Medium.Enabled`
- `userChrome.LightTheme.Tabs.Borders.Saturation.High.Enabled`
- `userChrome.LightTheme.Tabs.Borders.Saturation.VeryHigh.Enabled`

##### Borders (Dark Theme)
- `userChrome.DarkTheme.Tabs.Borders.Saturation.Low.Enabled`
- `userChrome.DarkTheme.Tabs.Borders.Saturation.Medium.Enabled`
- `userChrome.DarkTheme.Tabs.Borders.Saturation.High.Enabled`
- `userChrome.DarkTheme.Tabs.Borders.Saturation.VeryHigh.Enabled`

##### Shadows (Light Theme)
- `userChrome.LightTheme.Tabs.Shadows.Saturation.Low.Enabled`
- `userChrome.LightTheme.Tabs.Shadows.Saturation.Medium.Enabled`
- `userChrome.LightTheme.Tabs.Shadows.Saturation.High.Enabled`
- `userChrome.LightTheme.Tabs.Shadows.Saturation.VeryHigh.Enabled`

##### Shadows (Dark Theme)
- `userChrome.DarkTheme.Tabs.Shadows.Saturation.Low.Enabled`
- `userChrome.DarkTheme.Tabs.Shadows.Saturation.Medium.Enabled`
- `userChrome.DarkTheme.Tabs.Shadows.Saturation.High.Enabled`
- `userChrome.DarkTheme.Tabs.Shadows.Saturation.VeryHigh.Enabled`

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `userChrome.TabSeparators.Saturation.Low.Enabled`
- `userChrome.TabSeparators.Saturation.Medium.Enabled`

### Menu Density
By default context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

- `userChrome.Menu.Size.Compact.Enabled`
- `userChrome.Menu.Size.Normal.Enabled`
- `userChrome.Menu.Size.Touch.Enabled`

### Icons

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

- `userChrome.Menu.Icons.Regular.Enabled`
- `userChrome.Menu.Icons.Filled.Enabled`

### Lepton Icons
Icons from Lepton.css are now available. Please note that this is third-party code. I am not its author and do not support it. I will not solve any problems associated with these icons. They were added at the request of some users and work "As is". I will update this code according to the original source.

- `svg.context-properties.content.enabled`
- `userChrome.Menu.Icons.LeptonIcons.Enabled`
  - `userChrome.icon.panel_full` or `userChrome.icon.panel_photon`
  - `userChrome.icon.library`
  - `userChrome.icon.panel`
  - `userChrome.icon.menu`
  - `userChrome.icon.context_menu`
  - `userChrome.icon.global_menu`
  - `userChrome.icon.global_menubar`
  - `userChrome.icon.1-25px_stroke`
  - `userChrome.icon.account_image_to_right`
  - `userChrome.icon.account_label_to_right`
  - `userChrome.icon.menu.full`
  - `userChrome.icon.global_menu.mac`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

- `userChrome.DragSpace.Left.Disabled`
- `userChrome.DragSpace.Right.Disabled`
- `userChrome.DragSpace.Top.Windowed.Enabled`
- `userChrome.DragSpace.Top.Maximized.Enabled`
- `userChrome.DragSpace.Top.Fullscreen.Enabled`

### Pinned Tabs Width
![Снимок](https://user-images.githubusercontent.com/85301851/185612113-7bb0445f-8993-45bd-916d-d066e88ea7f4.PNG)

- `userChrome.Tabs.Pinned.Width.LowOffset.Enabled`
- `userChrome.Tabs.Pinned.Width.HighOffset.Enabled`

### Selected Tab Indicator
![изображение](https://github.com/QNetITQ/WaveFox/assets/85301851/c5b7c4b8-81d2-4ca2-9944-574af7e88f1d)

- `userChrome.Tabs.SelectedTabIndicator.Enabled`

### Tabs On Bottom
![Снимок](https://github.com/QNetITQ/WaveFox/assets/85301851/514cf30d-a417-48cb-bfd1-0e77c9df1bf4)

- `userChrome.Tabs.TabsOnBottom.Enabled`
- `browser.tabs.inTitlebar` (Required key. Set the value to 0)

### One Line
![Снимок](https://github.com/QNetITQ/WaveFox/assets/85301851/05bba314-643d-46f3-a09c-b3ac31f9761d)

- `userChrome.OneLine.TabBarFirst.Enabled`
- `userChrome.OneLine.NavBarFirst.Enabled`

</details>

<details>
  <summary>WaveFox v1.6.115.0.3 ESR</summary>

- ##### Minimum Requirements
  - Firefox 115 ESR
  - Windows / MacOS / Linux

- Download the `chrome` folder and put it in your user profile folder
- Go to `about:config` and activate the keys below
  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `layout.css.has-selector.enabled`
  - `svg.context-properties.content.enabled`
- Specify the desired shape of the tabs

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
Requires Linux with transparency support. Works only with the system theme.

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

### One Line
![Снимок](https://user-images.githubusercontent.com/85301851/181300272-d1ecfc93-898a-4eb3-80b9-9974fc471b45.PNG)

- `userChrome.OneLine.TabBarFirst.Enabled`
- `userChrome.OneLine.NavBarFirst.Enabled`
- `browser.tabs.inTitlebar` (Enable this key if there are problems with window control buttons. Set the value to 0)

Low values are more suitable for high resolution monitors.
- `userChrome.OneLine.NavBarWidth.Low.Enabled`
- `userChrome.OneLine.NavBarWidth.Medium.Enabled`
- `userChrome.OneLine.NavBarWidth.High.Enabled`

### Tabs On Bottom
![изображение](https://user-images.githubusercontent.com/85301851/182421633-3ec6948a-85cb-47ac-8b6d-6e92293e4ca3.png)

- `userChrome.TabsOnBottom-Enabled`
- `browser.tabs.inTitlebar` (Required key. Set the value to 0)

</details>

## FAQ

<details>
  <summary>How to find/open user profile folder?</summary>

  ![Profile](https://github.com/QNetITQ/WaveFox/assets/85301851/d2b893ea-a62e-4d96-9385-108f83025075)

</details>

<details>
  <summary>How to create custom keys?</summary>

  ![Bool1](https://github.com/user-attachments/assets/cab70491-bd9b-4e3a-86f5-6f8532cd68c9)
  ![Num1](https://github.com/user-attachments/assets/28f2bf7e-ffae-44af-86d5-6e6246a50d17)

</details>

<details>
  <summary>How to enable blur on Linux?</summary>

- [KDE Plasma 5](https://github.com/esjeon/kwin-forceblur)
- [KDE Plasma 6](https://github.com/taj-ny/kwin-effects-forceblur)
- [GNOME](https://github.com/aunetx/blur-my-shell)

</details>

<details>
  <summary>How to add third-party styles to WaveFox v1.x.130+?</summary>

Open `userChrome.css` and paste your code under the appropriate comment. Your code has the highest priority by default.

</details>

###### If you do not find the desired key, then your browser version does not support it.

<details>
  <summary>How to enable Accent Color on Windows 11 / Windows 10?</summary>

- `browser.theme.windows.accent-color-in-tabs.enabled`

</details>

<details>
  <summary>How to enable Mica / Acrylic / MicaAlt on Windows 11?</summary>

- `widget.windows.mica`
  - `widget.windows.mica.toplevel-backdrop` > 0 or 1 or 2 or 3 (Auto / Mica / Acrylic / MicaAlt)
- `widget.windows.mica.popups` > 0 or 1 or 2 (Disabled / Enabled / Auto)

</details>

<details>
  <summary>How to enable Tinting / Vibrancy on MacOS?</summary>

- `browser.theme.native-theme`
- `widget.macos.titlebar-blend-mode.behind-window`
- `widget.macos.sidebar-blend-mode.behind-window`

</details>

###### Have a question not related to this project? These resources will help you
- [Mozilla support](https://support.mozilla.org/en-US/)
- [Reddit](https://www.reddit.com/r/firefox)
- [Reddit (CSS)](https://www.reddit.com/r/FirefoxCSS)
