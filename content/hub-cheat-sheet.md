---
title: Hub Cheat-Sheet
emoji: 🗺️
category: library
updated: 2026-07-03
---

A short, practical reference I keep for running my AI Hub.

## What a card is

A card is just a Markdown file (`.md`) living in the `content/` folder of this repo. Each card starts with a small block of frontmatter between `---` lines:

- `title` — the name shown on the card.
- `emoji` — the little icon on the card.
- `category` — must be exactly `tools` or `library` (lowercase).
- `updated` — the date I last touched it (YYYY-MM-DD).

Everything below the frontmatter is normal Markdown and becomes the body of the card.

## The two categories

- **tools** — things my AI runs or produces for me: generated reports, briefings, spreadsheets, brochures, anything that's an output or an action.
- **library** — saved references I come back to: prompts, checklists, templates, my "DNA" (my voice, my style, my standard details). This cheat-sheet lives here.

## Cards can write themselves

A scheduled task can automatically drop its result into my Hub as a card. So a "run every morning" job doesn't just email me — it can commit a fresh `tools` card to `content/` each day. That's the real power of the Hub: it fills up on its own as my automations run.

## Ideas and Wins

- Add a rough idea to the **Ideas board** whenever it strikes — no need for it to be polished.
- When an idea is finished and shipped, it graduates to a **Win**. The board is my backlog; Wins are the trophy shelf.

## What's next: starter ideas

Grounded in what I actually have set up today — Team David Howe at Raine & Horne Lower North Shore (Northbridge), the document skills I already carry (schedule, pptx, xlsx/spreadsheet, docx, pdf), no scheduled tasks yet, and no plugins installed. Pick one and build it:

- **Daily morning briefing** — add a scheduled task (I have the `schedule` skill) that each morning writes a `tools` card with today's appointments, appraisals and follow-ups. My first automation, since I have none yet.
- **Weekly Lower North Shore market snapshot** — a scheduled task that writes a `tools` card each Monday with median prices and auction clearance for Northbridge/Willoughby/Castlecrag, ready to quote to vendors.
- **Buyer-enquiry triage** — a daily card summarising new buyer enquiries grouped by property and hot vs. cold, so nothing slips between David and me.
- **CMA spreadsheet on demand** — use my `xlsx` skill to generate a Comparative Market Analysis workbook per address and save it as a `tools` card I can reuse.
- **Listing presentation template** — a `pptx` vendor pitch deck in the brand colours (#ffb300 / #3d3935) saved as a reusable `library` card, so every appraisal starts from the same polished base.
- **Property flyer / brochure generator** — a `docx`/`pdf` one-pager template for new listings, saved as a `library` card and filled per property.
- **My listing-copy DNA** — a `library` card holding my best prompts and my voice/tone rules for writing ad copy, so AI-drafted listings always sound like Team Howe.
- **Weekly wins log** — a scheduled task that each Friday writes a `tools` card of the week's new listings, opens and settlements — feeding straight into the Wins board.
