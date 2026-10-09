<a href="https://novisajtovi.com/"><img src="media/cover.jpg" alt="Novi sajtovi, home page on a laptop and a phone" width="100%"></a>

# Novi sajtovi

The steps I follow when a site launches or moves, with a pre-launch checklist and a 301 redirect generator.

**[novisajtovi.com](https://novisajtovi.com/)** · [Case study (in Serbian)](https://svilenkovic.rs/radovi/novi-sajtovi) · [Srpski](README.sr.md)

> [!NOTE]
> My own project, not client work. The source code is private. This page describes what the site does and how it is built.

<table>
  <tr><td><b>Client</b></td><td>Own project</td></tr>
  <tr><td><b>Industry</b></td><td>Website launches and migrations</td></tr>
  <tr><td><b>Location</b></td><td>Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Multi-page website with tools</td></tr>
  <tr><td><b>My role</b></td><td>Research, design, development, SEO and hosting</td></tr>
  <tr><td><b>Stack</b></td><td>Astro 7, TypeScript, PHP 8.3, SQLite, nginx</td></tr>
</table>

## About the project

A new site loses the most on launch day: old addresses lead nowhere, Google sees the wrong version and nobody watches the first week. On novisajtovi.com I collected the tools and steps I use for every launch and every move. The guides follow the order I work in myself: a list of old addresses, one change at a time, then monitoring after launch.

The home page is an airport departures board listing sites I launched in 2025 and 2026, with industry, town, type, mobile score and the month each went live. I wrote the split-flap tiles myself, without an animation library. The HTML text does not change while the tiles flip, so search engines and screen readers read it normally, and with reduced motion the board simply shows its final state.

## What I built

- A pre-launch checklist with 52 checks in eight groups, ticked in the browser with nothing sent
- A 301 generator for nginx and Apache that first finds chains, loops and duplicates
- Common failures taken from my own case studies, such as an IPv6 record pointing at a server that does not answer
- Hand-made split-flap tiles that leave the HTML text untouched
- Guides for moving to a new site, changing a domain, Search Console and the first 30 days after launch

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, October 2026. Security headers: 6 of 6. axe accessibility check: no violations. Structured data: `FAQPage`, `Person`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Novi sajtovi, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Novi sajtovi, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="301 generator after checking for chains, loops and duplicates">
<sub>301 generator after checking for chains, loops and duplicates</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
