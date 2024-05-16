[screenshot]:       https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SystemColor1.png
[light]:            https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SystemColor1.png
[dark]:             https://cdn.discordapp.com/attachments/946226984005025835/1140494116451532810/SystemColor1.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/SystemColor/SystemColor.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/SystemColor/net.saltssaumure.SystemColor.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/SystemColor?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/SystemColor
[issues]:           https://github.com/MiniDiscordThemes/SystemColor/issues
[license]:          https://github.com/MiniDiscordThemes/SystemColor/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/SystemColor/blob/main/SystemColor.theme.css

[release-bd-gh]:    https://github.com/MiniDiscordThemes/SystemColor/releases/latest/download/SystemColor.theme.css "Get latest release"

# SystemColor Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![Theme GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Total repository size][shield-repo-size]][github]

***A Discord recolor based on your system color.***

![Screenshot of SystemColor applied to Discord][screenshot]

| Light mode                                                        | Dark mode                                                       |
| ----------------------------------------------------------------- | --------------------------------------------------------------- |
| ![Screenshot of SystemColor light mode applied to Discord][light] | ![Screenshot of SystemColor dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `SystemColor.theme.css`:
    <!-- - [BetterDiscord store][release-bd] -->
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `SystemColor.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/SystemColor/SystemColor.theme.css`

## Customisation

| Description                    | Variable name     | Valid values                            | Default value |
| ------------------------------ | ----------------- | --------------------------------------- | ------------- |
| Background colour              | `--temp-bg-color` | Any [CSS-recognised][css-color] colour. | #000          |
| &#9936; Moving scanline on/off | `--temp-scanline` | `block` (on) or `none` (off).           | `block`       |
| &#9888; Screen flicker on/off  | `--temp-flicker`  | `flicker` (on) or `none` (off).         | `none`        |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Vencord
#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `SystemColor.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`SystemColor.theme.css`][.theme.css].
3. Edit the variable values.

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].