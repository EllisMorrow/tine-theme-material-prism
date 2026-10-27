# Local check summary

- Theme: Material · Prism 0.1.1
- Manifest SHA-256: `a5aebec5b32cda9b2430437c3cebe85402d7697f1d32bffc7bded735f4140ee4`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 6.94:1, title 9.24:1, link 4.69:1, tag 6.7:1, code 6.27:1, mark 6.42:1, chosen 6.26:1.
  - Dark: body 10.71:1, title 15.63:1, link 8.63:1, tag 6.69:1, code 9.68:1, mark 7.08:1, chosen 8.4:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
