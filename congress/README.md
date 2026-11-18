# About one in seven press releases from Congress are now written by AI

About one in seven press releases from members of Congress in 2026 are written by AI, up from almost none in 2023. House against Senate, the member's quote, newer members and the words that rose.

**The study:** https://dropslop.ai/research/congress.html  
**How it was done:** https://dropslop.ai/research/method.html  
**Data built:** 2026-11-12  
**Detector fingerprint (SHA-256):** d9a6d4dad434ea65ccf608ff34586696467784e82d57d66ea7114825e3ea8a03  
**Licence:** CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/): use and share freely, with credit and a link to the study.  

## Files

| File | What it holds | Rows |
|---|---|---|
| `data/s21.csv` | Congress press releases | 324 |
| `data/s21.json` | Congress press releases |  |
| `data/s21-deep.csv` | AI-written press releases from members of Congress | 1151 |
| `data/s21-deep.json` | AI-written press releases from members of Congress |  |

## How to read them

Each CSV has two columns, `key` and `value`. A key is a path into the matching JSON file, with dots between
the levels (`headline.after.corrected` is `headline` → `after` → `corrected` in the JSON). The two files hold
the same numbers; use whichever is easier. Shares are fractions of 1 (0.257 is 25.7%).

The files hold counts, shares and ranges for groups of texts. They do not hold the texts that were scored,
and a figure for a group says nothing certain about any one text in it.

## Using and citing

Use these findings freely with a link back to https://dropslop.ai/research/congress.html.

> DropSlop (2026). About one in seven press releases from Congress are now written by AI. https://dropslop.ai/research/congress.html
