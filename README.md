# Dracula High Contrast Theme for Visual Studio Code 🧛🏻‍♂️

> This Theme based on [evondev-dracula](https://github.com/evondev/evondev-dracula) which is based on [dracula-official](https://github.com/dracula/dracula-theme) 🙏

![Preview](https://raw.githubusercontent.com/shiftgeist/evondev-dracula-darker/main/assets/preview.png)

![Colors](https://raw.githubusercontent.com/shiftgeist/evondev-dracula-darker/main/assets/colors.png)

> This fork adds variants of background brightness to the theme "Dracula Darker Contrast New Color" with an adjusted lightness
> You can install this along side `evondev-dracula`
>
> <small>And a [fixed version](#fork-fixes) for Dracula Darker Contrast New Color</small>

## Installation

1. Clone repository

```sh
git clone git@github.com:shiftgeist/evondev-dracula-darker.git
```

2. Package and install extension

```sh
pnpm dlx vsce package && code --install-extension ./dracula-high-contrast-lightness-0.2.89.vsix
```

1. Restart extensions - In the extension tab: Select `Restart Extensions`

2. Open command pallet, select `> Preferences: Color Theme` and choose the `... minus 1` theme

## Fork Fixes

- [x] Same tab bar background gray -> dark purple (`Evondev Dracula Darker Contrast New Color (fixed)`)

  | Before                         | After                         |
  | ------------------------------ | ----------------------------- |
  | ![](./assets/fix-1-before.png) | ![](./assets/fix-1-after.png) |

- [x] Keep the same title bar background for inactive windows

## Scheme color

<!--
0.164 0.0111 268.01
0.040 0.0200  12.42
0.202 0.0279 280.43
-->

- Evondev Dracula Darker Contrast New Color (fixed) ✨
  - Background: #141523 (0.202 Lightness)
- Evondev Dracula Darker Contrast New Color Darker Bordered ✨
  - Background: #0c0d1a (0.1647 Lightness)
- Evondev Dracula Darker Contrast New Color Darkest ✨
  - Background: #050611 (0.1274 Lightness)
- Evondev Dracula Darker Contrast New Color Darkest Border ✨
  - Background: #050611 (0.1274 Lightness)

## Version

This fork aims to be one the same version as evondev's.

## Evondev's settings.json

[Settings Json](https://github.com/evondev/evondev-dracula/blob/master/evondev-settings.json)

## Evondev's other extensions

- [Evondev Snippets](https://marketplace.visualstudio.com/items?itemName=evondev.evondev-snippets)
- [Evondev - HTML to CSS Class](https://marketplace.visualstudio.com/items?itemName=evondev.generate-css-class)
- [Evondev - Indent Rainbow Palettes](https://marketplace.visualstudio.com/items?itemName=evondev.indent-rainbow-palettes)

## Evondev's Font

[SF Mono Ligatures](https://github.com/kube/sf-mono-ligaturized).

## Helper

- [oklch picker](https://oklch.com/) made by @evilmartians ([repo](https://github.com/evilmartians/oklch-picker))
- Color Names from [Name that Color](https://chir.ag/projects/name-that-color/) and [Color Name & Hue](https://www.color-blindness.com/color-name-hue/)
