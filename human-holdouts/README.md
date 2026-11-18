# The last mostly-human corners are starting to move

Local news, government websites, new encyclopedia articles, company filings, newsletters and job postings are still mostly not written by AI. They are starting to move.

**The study:** https://dropslop.ai/research/human-holdouts.html  
**How it was done:** https://dropslop.ai/research/method.html  
**Data built:** 2026-11-12  
**Detector fingerprint (SHA-256):** d9a6d4dad434ea65ccf608ff34586696467784e82d57d66ea7114825e3ea8a03  
**Licence:** CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/): use and share freely, with credit and a link to the study.  

## Files

| File | What it holds | Rows |
|---|---|---|
| `data/holdouts-deep.csv` | The slowest movers | 5585 |
| `data/holdouts-deep.json` | The slowest movers |  |
| `data/s11-deep.csv` | Newsletters and blogs | 733 |
| `data/s11-deep.json` | Newsletters and blogs |  |

## How to read them

Each CSV has two columns, `key` and `value`. A key is a path into the matching JSON file, with dots between
the levels (`headline.after.corrected` is `headline` → `after` → `corrected` in the JSON). The two files hold
the same numbers; use whichever is easier. Shares are fractions of 1 (0.257 is 25.7%).

The files hold counts, shares and ranges for groups of texts. They do not hold the texts that were scored,
and a figure for a group says nothing certain about any one text in it.

## Using and citing

Use these findings freely with a link back to https://dropslop.ai/research/human-holdouts.html.

> DropSlop (2026). The last mostly-human corners are starting to move. https://dropslop.ai/research/human-holdouts.html
