# Synthesis Discord Theme
[![GitHub downloads](https://img.shields.io/github/downloads/saltssaumure/synthesis-discord-theme/total?color=purple&label=GitHub%20downloads&style=flat-square)](https://github.com/Saltssaumure/synthesis-discord-theme/releases/latest "Latest release")
![Total size](https://img.shields.io/github/repo-size/saltssaumure/synthesis-discord-theme?style=flat-square "Total size")

***A vibrant neon synthwave Discord theme.***

![Screenshot of Synthesis Discord Theme applied to Discord](https://user-images.githubusercontent.com/29710355/187690344-9369a7a6-a424-48af-a020-bc9582b1d3ee.png)
![Screenshot of Synthesis Discord Theme applied to Discord, with background image](https://user-images.githubusercontent.com/29710355/188302911-efd255ea-77f6-4f62-9aea-37159406e7f3.png)

## Installation

### BetterDiscord
1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download the theme file:
    - [GitHub](https://github.com/Saltssaumure/synthesis-discord-theme/releases/latest)
    - [BD Store](https://betterdiscord.app/theme/?id=770)
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged](https://replugged.dev/).
2. Install the theme:
    - [GitHub](https://github.com/Saltssaumure/synthesis-discord-theme/releases/latest)
    - [Replugged.dev](https://replugged.dev/install?identifier=Saltssaumure/synthesis-discord-theme&source=github)

### Vencord
1. Install [Vencord](https://github.com/Vendicated/Vencord).
2. Paste the following in Themes:
    - `https://saltssaumure.github.io/synthesis-discord-theme/Synthesis.theme.css`

## Customisation

| Description                | Variable name                                 | Valid values                                                                                                                          | Default value                                                                         |
|----------------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Background image           | `--synth-bg-image`                            | Any image link encased in `url()`. [Suggested images](https://github.com/Saltssaumure/synthesis-discord-theme/tree/main/backgrounds). | `url(https://saltssaumure.github.io/synthesis-discord-theme/backgrounds/default.avif)` |
| Overlay tint colour        | `--synth-overlay-color`                       | Any CSS-recognised colour. Low opacity value recommended.                                                                             | `rgba(255, 165, 0, 0.1)`                                                              |
| CRT scanline colour        | `--crt-scanline-light`, `--crt-scanline-dark` | Any CSS-recognised colour. Low opacity value recommended.                                                                             | `rgba(255, 255, 255, 0.05)`, `rgba(0, 0, 0, 0.1)`                                     |
| &#9888; CRT flicker effect | `--crt-flicker`                               | `flicker` (on) or `none` (off)                                                                                                        | `none`                                                                                |

&#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
2. Copy and paste line 31-37 of [`Synthesis.theme.css`](https://github.com/Saltssaumure/synthesis-discord-theme/blob/main/Synthesis.theme.css).
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 30-36 of [`Synthesis.theme.css`](https://github.com/Saltssaumure/synthesis-discord-theme/blob/main/Synthesis.theme.css).
4. Edit the variable values.

## License
[GNU General Public License v3.0](https://github.com/Saltssaumure/synthesis-discord-theme/blob/main/LICENSE)
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue](https://github.com/Saltssaumure/synthesis-discord-theme/issues) on GitHub.
- Post in `#theme-support` on [my support server](https://discord.gg/uy8nKQVatp).
