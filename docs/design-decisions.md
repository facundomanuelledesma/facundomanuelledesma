# FML / DEV — design decisions

## Evidence and scope

Only the profile repository is changed. The public profile identifies its owner as Facundo. Full name, education, professional title, employment history and contact details remain unconfirmed and are omitted.

The reviewed main branches support one substantive candidate: moodle_actualizacion. Its PHP template selects MariaDB, and its PowerShell helper wraps Moodle CLI commands. Its upgrade log contains placeholders. The profile labels the collaborative work in progress and claims neither completed migrations nor individual authorship of the team's implementation. Frontend/backend placeholders are not featured. The taller1 ZIP was not inspected.

## Visual direction

Midnight #0B1220, Graphite #17263B, Cyan #60C8F2, White #F4F7FC and Steel #8FA4BC form the palette. Both theme variants retain a dark banner; the light variant has a darker outer border. The 4:1 hero contains branding rather than essential biography, which remains selectable Markdown below it. Content inherits GitHub's native theme and flows in one column.

The single creative signature, fml --next, expresses explore → build → document. It is static decoration, not an executable command, live status or metric. No motion fallback is needed. SVGs include titles/descriptions and README images have alternative text. Essential information is not embedded in images.

## Content

Technology labels describe evidence rather than proficiency. Moodle is a platform, and MariaDB is described as configuration rather than demonstrated administration expertise. One project is featured because the audit did not support two completed projects. GitHub is the only verified professional link. No external statistics service, badges service, remote font, JavaScript, iframe, token or scheduled workflow is necessary.

## References

- https://github.com/Andrew6rant/Andrew6rant — theme-aware SVG selection; independent artwork here.
- https://github.com/gautamkrishnar — purpose-led project descriptions and clear links.
- https://github.com/BrunnerLivio/BrunnerLivio — a memorable personal signature; no copied artwork or guestbook.
- https://github.com/tobiager/readme-builder — modular asset organization. Its rendered README was unavailable during the audit, limiting that comparison.

## Maintenance

Update factual content in README.md. Synchronize the two heroes except their borders. Add projects when public code and documentation substantiate their descriptions, and contact information only when authorized. See validation.md for actual checks and limitations.
