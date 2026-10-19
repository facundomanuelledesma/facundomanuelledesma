# Validation

Executed on 2026-10-19.

- GitHub Markdown API accepted and rendered the README, including picture/source, headings, links and table.
- Parsed all three SVG files as XML; checked for scripts and foreignObject. None present. Total SVG size: 2,780 bytes.
- Checked all local image references exist.
- About section: 69 words. English copy manually reviewed.
- Calculated text contrast on #0B1220: White 17.44:1, Steel 7.31:1, Cyan 9.84:1.
- All three distinct external README URLs returned HTTP 200.
- Generated four previews from the GitHub-rendered HTML in headless Edge: desktop 1100 px and mobile 390 px, both light and dark. All images loaded and no horizontal document overflow was detected.
- Visually inspected desktop dark and mobile light screenshots.
- git diff --check passed before publication.

## Limitations

Preview styling approximates GitHub; these images are local previews, not captures of the live profile. Native GitHub Desktop and physical mobile devices were not tested. Screen-reader behavior was not tested with assistive technology. The source Moodle helper was read, not executed; no migration success is claimed. Unconfirmed identity, background and contact details are omitted.

## Previews

- [Desktop dark](previews/desktop-dark.png)
- [Desktop light](previews/desktop-light.png)
- [Mobile dark](previews/mobile-dark.png)
- [Mobile light](previews/mobile-light.png)
