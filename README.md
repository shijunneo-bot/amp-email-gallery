# AMP Email Gallery

Interactive field guide to AMP for Email on CleverTap. 72 template prototypes across
9 industry verticals, each with a feasibility rating and extractable production code.

**Live:** https://shijunneo-bot.github.io/amp-email-gallery/

## What is inside

| Tab | Contents |
| --- | --- |
| AMP Gallery | 72 template prototypes, previewable in a Gmail frame, desktop and mobile |
| Award Journeys | DBS journey builder walkthrough |
| Partner Stack | The five partner layers an email passes through, and which one gates AMP |

## Copy and download

Every template modal carries **Copy HTML** and **Download** buttons. These do not hand
back the gallery page. They extract just the email body, strip the browser chrome and
preview JavaScript, and wrap the result in a valid AMP4Email skeleton with the right
component scripts detected automatically. The output is ready to paste into CleverTap
under Campaigns > Email > Custom HTML & AMP Template.

Downloaded files carry an `_amp` suffix, for example `amp_c1_titan_eye_amp.html`.

## Before you send anything from here

1. Replace merge tags with CleverTap Liquid Tags, for example `{{ profile["Name"] }}`
2. Point any form `action-xhr` at `@SpecialLinks - Submit Form`
3. Paste a fallback into the Fallback HTML tab, for Outlook and Apple Mail recipients
4. Confirm the ESP is SendGrid and the plan carries Email Booster Max or Advanced Email
5. Convert preview JavaScript to AMP components, since custom JS is not valid in AMP email

The Partner Stack tab covers points 4 and 5 in more detail.

## Structure

Single self-contained `index.html`. No build step, no dependencies beyond Google Fonts.
Deployed from the `main` branch root.

## Accuracy

Partner lists and capability statements were read from docs.clevertap.com and are current
as of July 2026. Product documentation changes, so please check the linked pages before
committing anything to a client. Sample values in template code are illustrative.

## The gallery series

This is No.01 of seventeen field guides. The full list is linked at the foot of the page.

Built and maintained by SJ Neo, Enterprise Customer Success Manager, CleverTap APAC.
