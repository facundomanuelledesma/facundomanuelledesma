# Validation — centered violet edition

Executed on 2026-10-20.

- GitHub Markdown API accepted and rendered the README, preserving picture/source, centered blocks, details/summary, links and images.
- All ten SVGs parsed successfully as XML; none contains scripts, foreignObject or remote resources. README image paths exist and all images have alternative text.
- About paragraph: 63 words; English manually reviewed. Spanish greeting follows the requested reference.
- Text contrast: hero dark colors 7.84:1–10.05:1 on #0D1117; light colors 6.39:1–9.03:1 on white; tile text 8.75:1–13.52:1 on #211B2B.
- All three distinct external README URLs returned HTTP 200.
- Four local previews were rendered with headless Edge using GitHub-rendered HTML: desktop at 1100 px and mobile at 390 px, light and dark. All images loaded; none had horizontal document overflow.
- Visually inspected desktop dark and mobile light, including natural tile wrapping and centered hero/contact alignment.
- git diff --check passed.

## Limits

Previews use approximate local GitHub styling, not captures of the live profile. Native GitHub Desktop, physical devices and assistive-technology behavior were not tested. The source Moodle script was not executed, and no successful migration is claimed. All images are static, with no runtime image provider or animation to fail.

## Previews

- [Desktop dark](previews/desktop-dark.png)
- [Desktop light](previews/desktop-light.png)
- [Mobile dark](previews/mobile-dark.png)
- [Mobile light](previews/mobile-light.png)
