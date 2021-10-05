# vsCodeConfig

## Table of Contents
1. [Welcome](#welcome)
2. [Fonts](#fonts)
3. [Terminal](#terminal)
4. [VS Code](#vs-code)
5. [Afterwards](#afterwards)

## Welcome
Hello, and welcome to my quick and easy 'Pimp Yr VsCode' repo!
This is meant mostly as a resource for me to reference in case I ever get a new machine and would like to quickly set it up.

## Fonts
Fonts are included within this repo.
For Mac, simply download the [Fonts.zip](https://github.com/airpick/vsCodeConfig/raw/main/Fonts.zip) found in this repo.

Afterwards, you will need to unzip the file and Open each of the font files within.

This may be a little tedious, but it is a small bit better than having to download this individually just to do the same.

## Terminal
![iTerm2](https://github.com/airpick/vsCodeConfig/blob/main/Images/iTerm2.png)
Next, let's set up the following for terminal:

### Install `oh my zsh`
http://ohmyz.sh/

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Download `iTerm2` (Optional)
https://iterm2.com/

### Change Settings in `iTerm2`
Download the [Agnoster.json](https://raw.githubusercontent.com/airpick/vsCodeConfig/main/Agnoster.json) file included in this repo.

In `iTerm2`, do the following:
1. Open `Preferences`.
2. Select the `Profiles` tab.
3. Select `Other Actions...`.
4. Select `Import JSON Profiles`.
5. Import the downloaded file.

This profile is using a custom Color Theme, though many color schemes look good with this configuration.
For more on `Color Presets...`, be sure to visit this [page](https://iterm2colorschemes.com/)!

## VS Code
![VSCode](https://github.com/airpick/vsCodeConfig/blob/main/Images/vsCode.png)
Finally, we'll pimp out VS Code!

### Extensions
Before we begin, please download the following Themes/Extensions within VS Code.
1. Power Mode
2. Night Owl

Alternatively, you can edit the [settings.json](https://github.com/airpick/vsCodeConfig/blob/main/settings.json) to not expect Night Owl for the following:
1. `"workbench.preferredDarkColorTheme": "Night Owl,`
2. `"workbench.colorTheme": "Night Owl",`

You may also remove the Power Mode features (all keys with `powermode.`).
For more on Power Mode, please visit their [Marketplace](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode) listing.
They also have a very active community thread for alternative gifs/explosions which can be defined [here](https://github.com/hoovercj/vscode-power-mode/issues/1).

## Afterwards
If you have any issues with installation or suggestions for improving this readme, please feel free to reach out!
