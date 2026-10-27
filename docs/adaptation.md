# Adaptation notes

The Codex Material reference is dark-only. This package pairs the native dark Material theme with the native light Material Night theme from Microsoft's archived Material Theme Kit. Its README states that the set is based on equinusocio/material-theme. The files name Mattia Astorino as theme author; the MIT license in this repository credits Microsoft Corporation.

## Sources

- Material dark palette: https://github.com/microsoft/vscode-themes/blob/2a810696b25f1b681138e9c8129e03f463413a85/material/themes/Material-Theme-Darker.tmTheme
- Material Night light palette: https://github.com/microsoft/vscode-themes/blob/2a810696b25f1b681138e9c8129e03f463413a85/material/themes/Material-Theme-Lighter.tmTheme
- Material Theme Kit metadata: https://github.com/microsoft/vscode-themes/blob/2a810696b25f1b681138e9c8129e03f463413a85/material/package.json (version 0.1.4)
- Upstream license: https://github.com/microsoft/vscode-themes/blob/2a810696b25f1b681138e9c8129e03f463413a85/material/LICENSE.txt
- Original theme reference: https://github.com/equinusocio/material-theme

## Mapping decisions

- Dark canvas and source foreground follow Material (#212121 and #CDD3DE); light canvas and primary surface follow Material Night (#FAFAFA and #F5F5F5).
- Tine surface tiers, selection, code and marks are independent semantic mappings. Light text uses readable slate; light link/tag and dark link/tag use deeper roles where needed.
- The 21-token API does not control fonts, task markers, arbitrary hover rules or every syntax color. This package does not claim Material Night is a Codex-native preset.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

## Codex reference verification

- Codex references Material Theme Darker. The dark canvas #212121 follows the pinned Material-Theme-Darker source (labeled Material Night Eighties in the package); Tine gray surface and selection tiers are adaptations.
- Light mode uses the pinned kit’s Material-Theme-Lighter (labeled Material Night), an upstream light companion rather than a native Codex light preset.
- Text and link roles are adapted for readability; the 21-token API does not control arbitrary CSS, fonts, task markers or full syntax colors.


Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
