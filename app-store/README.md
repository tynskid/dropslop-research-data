# Just over one in three apps launched in 2026 have descriptions written by AI

How many descriptions of new apps on a major mobile app store are written by AI, by launch year, genre, ratings and length.

**The study:** https://dropslop.ai/research/app-store.html  
**How it was done:** https://dropslop.ai/research/method.html  
**Data built:** 2026-11-12  
**Detector fingerprint (SHA-256):** d9a6d4dad434ea65ccf608ff34586696467784e82d57d66ea7114825e3ea8a03  
**Licence:** CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/): use and share freely, with credit and a link to the study.  

## Files

| File | What it holds | Rows |
|---|---|---|
| `data/s10-deep.csv` | App descriptions | 1676 |
| `data/s10-deep.json` | App descriptions |  |

## How to read them

Each CSV has two columns, `key` and `value`. A key is a path into the matching JSON file, with dots between
the levels (`headline.after.corrected` is `headline` → `after` → `corrected` in the JSON). The two files hold
the same numbers; use whichever is easier. Shares are fractions of 1 (0.257 is 25.7%).

The files hold counts, shares and ranges for groups of texts. They do not hold the texts that were scored,
and a figure for a group says nothing certain about any one text in it.

## Using and citing

Use these findings freely with a link back to https://dropslop.ai/research/app-store.html.

> DropSlop (2026). Just over one in three apps launched in 2026 have descriptions written by AI. https://dropslop.ai/research/app-store.html
