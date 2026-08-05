# AMP Email Gallery

Interactive field guide to AMP for Email on CleverTap. 72 template prototypes across
9 industry verticals, each with a feasibility rating and extractable production code.

**Live:** https://shijunneo-bot.github.io/amp-email-gallery/
**Series hub:** https://shijunneo-bot.github.io/ct-gallery-hub/

## What is inside

| Tab | Contents |
| --- | --- |
| AMP Gallery | 72 template prototypes, previewable in a Gmail frame, desktop and mobile |
| Award Journeys | DBS journey builder walkthrough |
| Partner Stack | The five partner layers an email passes through, and which one enables AMP |

## Day and night

The page carries a day and night theme with a toggle in the top corner. It defaults to
night, follows the reader's saved choice on return visits, and both modes meet WCAG AA
contrast on all text.

## Copy and download

Every template modal carries **Copy HTML** and **Download**. These return just the email
body wrapped in a valid AMP4Email skeleton, with the right component scripts detected
automatically, ready to paste into CleverTap under Campaigns > Email > Custom HTML & AMP
Template. Downloaded files carry an `_amp` suffix.

## Before you send from here

1. Replace merge tags with CleverTap Liquid Tags, for example `{{ profile["Name"] }}`
2. Point any form `action-xhr` at `@SpecialLinks - Submit Form`
3. Paste a fallback into the Fallback HTML tab, for Outlook and Apple Mail recipients
4. Confirm the sending route is SendGrid and the plan carries Email Booster Max or
   Advanced Email, which is what enables the interactive AMP layer
5. Convert preview JavaScript to AMP components, since custom JS is not valid in AMP email

The Partner Stack tab covers points 4 and 5 in more detail.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The gallery, single self-contained file |
| `og-preview.png` | Social share card, 1200x630 |
| `robots.txt` | Crawler directives, AI crawlers welcomed |
| `sitemap.xml` | Sitemap with image entry |
| `llms.txt` | Structured summary for AI engines |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |

## Structure

Single self-contained `index.html`, no build step, no dependencies beyond Google Fonts.
Deployed from the `main` branch root.

## The series

This is one of eighteen field guides covering the CleverTap channel and platform stack,
grouped by plan tier. The full set is linked from the Gallery Hub and at the foot of the page.

## Accuracy

Partner lists and capability statements reflect CleverTap documentation as of August 2026.
Product documentation evolves, so the linked pages carry the current detail. Sample values
in template code are illustrative.

Built and maintained by SJ Neo, Enterprise Customer Success Manager, CleverTap APAC.
