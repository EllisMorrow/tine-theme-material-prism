<div align="center">

# Material · Prism

**A teal thread crosses the quiet stone; morning opens in silver light. Let each thought find its clear surface.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-80cbc4?labelColor=263238)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-80cbc4?labelColor=263238)
[![License: MIT](https://img.shields.io/badge/license-MIT-80cbc4?labelColor=263238)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-material-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-material-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-material-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Material Night Eighties and Material Night meet in one theme: the deep charcoal-gray of the classic palette after dark, and its light companion in soft white, with teal and violet notes.

### Dark mode

![Material · Prism in Tine dark mode](docs/material-dark.png)

### Light mode

![Material · Prism in Tine light mode](docs/material-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-material-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FAFAFA` | `#212121` |
| Sidebar | `#F5F5F5` | `#1b1b1b` |
| Body | `#455A64` | `#CDD3DE` |
| Heading | `#37474F` | `#EEFFFF` |
| Accent | `#39ADB5` | `#80CBC4` |
| Links | `#007C91` | `#80CBC4` |
| Tags | `#75458F` | `#C792EA` |
| Mark background | `#FFF1C2` | `#4A3C2E` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Material Night Eighties / Material Night](https://github.com/microsoft/vscode-themes) at `2a810696b25f1b681138e9c8129e03f463413a85`, under MIT; see [LICENSE](LICENSE). The dark mode follows Material Night Eighties (Material Theme Darker) from Microsoft's archived Material Theme Kit, based on equinusocio/material-theme. The light mode uses that kit's native Material Night light theme. This is a community Tine adaptation; no Codex code or assets are included.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-material-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
