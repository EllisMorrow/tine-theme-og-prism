# Local check summary

- Theme: OG · Prism 0.1.1
- Manifest SHA-256: `32e92187352ac7406eaaa252cfa03da78781058d0f7ecd01b2adb91777d2d52b`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 10.65:1, title 10.65:1, link 5.28:1, tag 5.28:1, code 9.71:1, mark 9.46:1, chosen 9.36:1.
  - Dark: body 8.23:1, title 8.23:1, link 5.39:1, tag 5.39:1, code 7.18:1, mark 7.13:1, chosen 7.06:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
