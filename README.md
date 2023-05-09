[backgroundless]: https://user-images.githubusercontent.com/29710355/187690344-9369a7a6-a424-48af-a020-bc9582b1d3ee.png
[backgrounded]: https://user-images.githubusercontent.com/29710355/188302911-efd255ea-77f6-4f62-9aea-37159406e7f3.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/rgb
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/synthesis-discord-theme/Synthesis.theme.css?color=purple&label=BD%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/synthesis-discord-theme/net.saltssaumure.Synthesis.asar?color=purple&label=Replugged%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/saltssaumure/synthesis-discord-theme?style=flat-square "Total size"

[license]:          https://github.com/Saltssaumure/synthesis-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/synthesis-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/synthesis-discord-theme/blob/main/Synthesis.theme.css

[release-gh]:       https://github.com/Saltssaumure/synthesis-discord-theme/releases/latest "Latest release"
[release-bd]:       https://betterdiscord.app/theme/?id=770 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/install?identifier=Saltssaumure/synthesis-discord-theme&source=github "Replugged addon installer"

[backgrounds]:      https://github.com/Saltssaumure/synthesis-discord-theme/tree/main/backgrounds

# Synthesis Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-gh]
[![Replugged downloads][shield-asar-dl]][release-rp]
![Total size][shield-repo-size]

***A vibrant neon synthwave Discord theme.***

| Without background                              | With background                                                     |
| ----------------------------------------------- | ------------------------------------------------------------------- |
| ![Synthesis applied to Discord][backgroundless] | ![Synthesis with background image applied to Discord][backgrounded] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [GitHub][release-gh]
    - [BD Store][release-bd]
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [GitHub][release-gh]
    - [Installer][release-rp]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/synthesis-discord-theme/Synthesis.theme.css`

## Customisation

| Description                | Variable name                           | Valid values                                                        | Default value                                                                          |
| -------------------------- | --------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Background image           | `--synth-background-image`              | Any image link encased in `url()`. [Suggested images][backgrounds]. | `url(https://saltssaumure.github.io/synthesis-discord-theme/backgrounds/default.avif)` |
| Overlay tint colour        | `--synth-overlay-color`                 | Space-separated [`RGB`][css-color] value.                           | `255 165 0  `                                                                          |
| CRT scanline colour        | `--synth-crt-light`, `--synth-crt-dark` | Space-separated [`RGB`][css-color] value.                           | `255 255 255`, `0   0   0`                                                             |
| &#9888; CRT flicker effect | `--synth-crt-flicker`                   | `flicker` (on) or `none` (off)                                      | `none`                                                                                 |
| Background colour          | `--synth-color-background`              | Space-separated [`RGB`][css-color] value.                           | `20  6   36 `                                                                          |
| Foreground colour          | `--synth-color-foreground`              | Space-separated [`RGB`][css-color] value.                           | `255 165 0  `                                                                          |
| Shadow colour              | `--synth-color-shadow`                  | Space-separated [`RGB`][css-color] value.                           | `0   0   128`                                                                          |
| Button colour              | `--synth-color-button`                  | Space-separated [`RGB`][css-color] value.                           | `84  63  251`                                                                          |
| Highlight colour           | `--synth-color-pop`                     | Space-separated [`RGB`][css-color] value.                           | `206 63  251`                                                                          |
| Discord colour             | `--synth-color-blurple`                 | Space-separated [`RGB`][css-color] value.                           | `88  101 242`                                                                          |
| Text colour                | `--synth-color-text`                    | Space-separated [`RGB`][css-color] value.                           | `255 255 255`                                                                          |
| DND colour                 | `--synth-color-red`                     | Space-separated [`RGB`][css-color] value.                           | `243 67  131`                                                                          |
| Idle colour                | `--synth-color-yellow`                  | Space-separated [`RGB`][css-color] value.                           | `255 165 0  `                                                                          |
| Online colour              | `--synth-color-green`                   | Space-separated [`RGB`][css-color] value.                           | `52  172 140`                                                                          |
| Streaming colour           | `--synth-color-twitch`                  | Space-separated [`RGB`][css-color] value.                           | `89  54  149`                                                                          |

&#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
2. Copy and paste lines 15-35 of [`Synthesis.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 15-35 of [`Synthesis.theme.css`][.theme.css].
4. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
