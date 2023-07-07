# Diablo IV Companion - The Inventory Manager 

A companion app for Diablo IV, to make life easier in finding the correct affixes.

```diff
- Note: This app is still in early development. Bugs are to be expected. Suggestions and bug reports are welcome!
```

```diff
- Note: Under construction for the v1.1.0.0 update. Readme will be updated later today.
```

<img src="./readme/readme-001.png" width="500">

If you like my work you can sponsor me on Ko-fi.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H1H5GCR)

## Table of Contents

- [Features](https://github.com/josdemmers/Diablo4Companion#features)
- [Installation](https://github.com/josdemmers/Diablo4Companion#installation)
- [Configuration](https://github.com/josdemmers/Diablo4Companion#configuration)
- [Usage](https://github.com/josdemmers/Diablo4Companion#Usage)
- [Troubleshooting](https://github.com/josdemmers/Diablo4Companion#Troubleshooting)

## Features

- Specify your prefered affixes for each gear slot and monitor them ingame.

## Installation

- Download the latest version from [Releases](https://github.com/josdemmers/Diablo4Companion/releases)
- Extract files and run D4Companion.exe
  - Go to settings and select the **System preset** matching your resolution.
  - Go to tooltips and create a new **Gear Affix Preset**.
  - Select your prefered affixes for each item slot.
    - Double click affixes to add/remove them from the list.
  - Read [Usage](https://github.com/josdemmers/Diablo4Companion#Usage) for more details on using the app.

## Configurations

Currently the following system presets are included:
- 2560x1440_SMF: SDR (HDR off) with font set to medium.

Feel free to share you system presets with me so I can add them to the app.

See the following [wiki](https://github.com/josdemmers/Diablo4Companion/wiki/How-to-create-a-new-System-Preset) page to create your own.

### Performence

To get a small performance boost you can enable `Lite Mode` in `Settings`. This will combine all weapon types into one making it faster to detect the tooltip.

The `Lite` mode is roughly 100ms faster. However if you want different affixes for weapons, ranged and focus you should turn `Lite Mode` off.

## Usage

![Usage-1](./readme/readme-usage-001.png)

1. Navigation menu. In the following order, Tooltips, Debug, and Settings.
2. Add a new preset for your preferred affixes.
3. Select or delete an existing affix preset.
4. Toggle the overlay on/off. Note: This is also possible using the ingame button in the top left corner.
5. Selected gear slot for which you want to set the affixes.
6. Used item types for the selected gear slot.
7. Filter available affixes.
8. List of all available affixes. Use double click to add/remove them from the list.

![Usage-2](./readme/readme-usage-002.png)

1. Set the width of the tooltip. Default for 2560x1440 is 500.
2. Threshold sliders for filtering out background noise. Defaults should be fine (60/255).
3. Previous debug image.
4. Next debug image.

![Usage-3](./readme/readme-usage-003.png)

1. Select the preset matching your resolution. See [Configuration](https://github.com/josdemmers/Diablo4Companion#configuration) to create your own.
2. Toggle debug mode on/off. Should remain off. Allows you to use screenshots instead of running Diablo to do some testing.

## Troubleshooting

## Licensing

MIT

## Thirdparty packages

- [Emgu CV](https://www.emgu.com/wiki/index.php/Main_Page)
- [GameOverlay.Net](https://github.com/michel-pi/GameOverlay.Net)
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro)
- [PInvoke](https://github.com/dotnet/pinvoke)
- [Prism](https://github.com/PrismLibrary/Prism)

## Community

### The Hidden Gaming Lair

- [Discord](https://discord.gg/NTZu8Px)
- [www](https://www.th.gl/)

