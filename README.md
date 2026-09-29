# Novi sajtovi

A launch and migration website built around controlled releases, preserved URLs and clear handover steps.

**[novisajtovi.com](https://novisajtovi.com/)** · [Golden Pets Hotel case study](https://novisajtovi.com/en/control-board/golden-pets-hotel/) · [Srpski](README.sr.md)

> [!NOTE]
> This is an independent project by D. Svilenković. The production source stays in a private repository; this public repository documents the work.

<table>
  <tr><td><b>Type</b></td><td>Launch and migration website</td></tr>
  <tr><td><b>Languages</b></td><td>Serbian and English</td></tr>
  <tr><td><b>Public routes</b></td><td>22 canonical pages</td></tr>
  <tr><td><b>Role</b></td><td>Research, design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Purpose

A new website is only useful when the move is controlled. The project explains content inventory, redirects, DNS, release checks and the handover in the order they actually happen.

## Design direction

The page behaves like a launch console. Midnight blue panels and copper indicators advance through preparation, release and verification as the visitor moves down the page.

## What I built

- Migration planning before any DNS change
- Redirect and old-URL preservation explained as part of the build
- A staged launch sequence with verification at each point
- Serbian and English content with matching canonical and language links
- Contact, privacy, service and process pages instead of a single sales screen

## Release checks

Every canonical route was checked at 390, 768, 1440 and 1920 px. The release was also tested without JavaScript and with reduced motion. Live checks covered HTTPS, redirects, response headers, structured data, sitemap files, protected paths and invalid contact requests without sending test mail.

These are engineering checks, not claims about search ranking or field performance.

---

<sub>Designed and built by [D. Svilenković](https://svilenkovic.com).</sub>
