# *WaveFox*

![WaveFox_Preview](https://github.com/QNetITQ/WaveFox/assets/85301851/268bda8c-b987-45d1-966b-59992c18e66e)

<details>
  <summary>Counter</summary>
    <div align='center'><a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=52856&s=3' border='0' alt='Free Website Counter'></a><br / ><small><a href='https://www.websitecounterfree.com' title="Free Website Counter">Free Website Counter</a></small></div>
</details>

###### Have a question not related to this project? These resources will help you
- [Mozilla support](https://support.mozilla.org/en-US/)
- [Reddit](https://www.reddit.com/r/firefox)
- [Reddit (CSS)](https://www.reddit.com/r/FirefoxCSS)

## Installation

- ##### Minimum Requirements
  - Firefox 128 + WaveFox v1.6.128
  - Firefox 127 + [WaveFox v1.6.127](https://github.com/QNetITQ/WaveFox/tree/v1.6.127)
  - Firefox 115 ESR + [WaveFox v1.6.115.0.3](https://github.com/QNetITQ/WaveFox/tree/v1.6.115)
  - Windows
  - MacOS
  - Linux

- [Download Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release) / [Download WaveFox](https://github.com/QNetITQ/WaveFox/releases)

- Download the `chrome` folder and put it in your user profile folder

  <details>
  <summary>How to access user profile folder?</summary>

  ![Profile](https://github.com/QNetITQ/WaveFox/assets/85301851/d2b893ea-a62e-4d96-9385-108f83025075)
  ![Profile 2](https://github.com/QNetITQ/WaveFox/assets/85301851/2817ee70-793b-40e6-a77e-8e62f9bfa87e)

  </details>
  
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  
- Specify the desired shape of the tabs

  <details>
  <summary>How to create keys?</summary>

  ![Keys](https://github.com/QNetITQ/WaveFox/assets/85301851/9a3673d1-0d95-49fd-911c-dc91b366bc8b)

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

  ##### Tabs (Option 13)
  ![изображение](https://github.com/QNetITQ/WaveFox/assets/85301851/906299f9-94e6-4a69-9191-202c94525ae6)
  - `userChrome.Tabs.Option13.Enabled`

## Optional

### Adding third-party styles
Go to the `chrome` folder and paste the desired styles inside the `third_party_custom_styles.css` file. Please note that this file has maximum execution priority. It will overwrite all styles, regardless of selector specificity. I make no guarantees of compatibility and will not resolve any style conflicts you may encounter.

- `userChrome.Style.ThirdParty.Enabled`

<i>Functionality that will not be part of the style will be published in the [discussions](https://github.com/QNetITQ/WaveFox/discussions) section as requests from users.</i>

### Windows Accent Color
Works only with the system theme.
![изображение](https://github.com/QNetITQ/WaveFox/assets/85301851/55b01904-6620-4e36-9b6d-91b092db725c)

- `browser.theme.windows.accent-color-in-tabs.enabled`

### MacOS Tinting / Vibrancy
Works only with the system theme.

- `browser.theme.macos.native-theme` (MacOS 11+ / Tinting)
  - `widget.macos.titlebar-blend-mode.behind-window` (Vibrancy / Restart required)

### Linux Transparency
Requires Linux with transparency support. Tested on Manjaro KDE [Plasma 5](https://github.com/esjeon/kwin-forceblur) / [Plasma 6](https://github.com/taj-ny/kwin-forceblur). Works only with the system theme. If you encounter a ghosting effect, increase the blur.

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
