# Contract risk comparison

A clause-by-clause comparison of a 22-clause services agreement (client standard form v1 vs supplier counter-draft v2), produced with AutoClaw's Legal Assistant.

**Synthetic file.** Both parties, the addresses and the contract value are fictional. No client, personal or financial data appears in any document here. Not legal advice, not for execution.

## Headline numbers

- 22 clauses reviewed, **19 changed**
- **202 tracked changes** in the redline
- **34 risk points** removed, scoring each clause 1-5 for the supplier's exposure before and after
- Three clauses sat at severity 5 in v1: **7 (IP), 12 (indemnity), 13 (liability)**
- Maximum liability: **unlimited -> 100% of fees (BDT 12,00,000)**
- Cash received before build: **20% -> 70%** (BDT 2,40,000 -> 8,40,000)
- 8 statutory checkpoints, **4 expressly flagged "to verify"** rather than presented as checked

## What is in the repo

`index.html` is a single self-contained page -- the redline, the risk table, the memo excerpt and the downloadable files are all embedded in it, so it works with no build step and no external assets.

Downloadable from the page:

- `01` v1 client standard form (5 pages)
- `02` v2 counter-draft (7 pages)
- `03` tracked redline (202 revisions, editable in Word)
- `04` workbook: change table, risk delta, verification log, scoring rubric
- `05` research memo (4 pages)

## Viewing the redline

Open `03_Redline_v1_to_v2.docx` in Word and select **Review -> Display for Review -> All Markup**. Deleted text appears struck through in red; insertions appear underlined in blue.

## Method

1. Both versions compared clause by clause; every change described and classified.
2. Each clause scored 1-5 for the supplier's exposure in each version, with a written fallback position.
3. Legal propositions traced to statutory provisions, with an explicit verification status for each.
4. Results assembled into a memo addressed to the client, not to a file.

The reusable output is the scoring rubric, not the redline: it turns a list of edits into a negotiation order -- three must-hold clauses, seven to protect margin, four tradeable, four give-aways.
