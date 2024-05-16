[blue-dark]:        https://minidiscordthemes.github.io/SystemColor/preview/blue-dark.avif
[blue-light]:       https://minidiscordthemes.github.io/SystemColor/preview/blue-light.avif
[brown-dark]:       https://minidiscordthemes.github.io/SystemColor/preview/brown-dark.avif
[brown-light]:      https://minidiscordthemes.github.io/SystemColor/preview/brown-light.avif
[green-dark]:       https://minidiscordthemes.github.io/SystemColor/preview/green-dark.avif
[green-light]:      https://minidiscordthemes.github.io/SystemColor/preview/green-light.avif

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/SystemColor/SystemColor.theme.css?color=purple&label=Downloads&style=flat-square
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

| Dark mode                                          | Light mode                                           |
| -------------------------------------------------- | ---------------------------------------------------- |
| ![SystemColor in blue with dark mode][blue-dark]   | ![SystemColor in blue with light mode][blue-light]   |
| ![SystemColor in brown with dark mode][brown-dark] | ![SystemColor in brown with light mode][brown-light] |
| ![SystemColor in green with dark mode][green-dark] | ![SystemColor in green with light mode][green-light] |

## Installation

### [Vencord][Vencord] (recommended)
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

### [BetterDiscord][BetterDiscord]
BetterDiscord does not currently detect your system color, however this theme can still be used and customised with a manually set color.
1. Download `SystemColor.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

## Customisation

| Variable name        | Valid values            | Default value (Vencord)  | Default value (Other) |
| -------------------- | ----------------------- | ------------------------ | --------------------- |
| `--systemcolor-base` | Any [color][css-color]. | `var(--os-accent-color)` | `cyan`                |

### Vencord
#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `SystemColor.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-20 of [`SystemColor.theme.css`][.theme.css].
3. Edit the variable values.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].