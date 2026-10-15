# DRIA Item Category Repository Build Register

**Source:** User-provided ItemCateogryExport.csv  
**Build mode:** GitHub-only planning; no assets attached to new shells tonight  
**Reference pattern:** DRIA_Appliances_BOM

## Source audit

| Audit field | Result |
|---|---:|
| Data rows | 837 |
| Unique description labels | 837 |
| Blank description labels | 0 |
| Rows with stated value of $45,000 USD | 837 |
| Arithmetic total of row values | $37,665,000 USD |

The total is a calculation from the supplied row values. It must not be represented as realized revenue, an independently assessed market valuation, or a binding offer.

## High-volume source families

The following are preliminary groupings based on repeated leading labels in the source. They are grouping candidates, not final repository boundaries. Preserve the exact source descriptions in the category register.

| Source family candidate | Rows |
|---|---:|
| Plumbing | 48 |
| Garden & irrig | 33 |
| Bolt & nut | 32 |
| Hardware | 32 |
| Tools | 32 |
| Building | 28 |
| Electrical | 28 |
| Lighting | 26 |
| Specials | 26 |
| Paint | 18 |
| Appliances | 16 |
| Powertools | 16 |
| Globes | 15 |
| Electrical cable | 14 |
| General hardware | 14 |
| Gas department | 12 |
| Pool | 12 |
| Bathroom | 11 |
| Electronic | 9 |
| Welding-brazing | 8 |

## Existing repository checkpoints

- [DRIA Appliances BOM](https://github.com/driahomebuilders-publisher-systems/DRIA_Appliances_BOM) — reference implementation; repository and PDF matrix verified through the GitHub connector.
- [DRIA 4IR public gateway](https://github.com/driahomebuilders-publisher-systems/driahomebuilders-publisher-systems.github.io) — Volume 4 Appliances PDF-matrix-only node committed.

The current connected GitHub actions support reading and writing files in existing repositories but do not expose a repository-creation action. Therefore, this register records the next build work without claiming that additional repository shells have been created.

## Next execution steps

1. Build the full source-row-to-family mapping, retaining the original description verbatim.
2. Normalize proposed repository slugs and check for collisions with existing repositories.
3. Create each repository shell when repository-creation permission is available.
4. Apply the reference README and procurement language.
5. Publish green gateway nodes only after each linked destination exists and is verified.

Copyright © 2026 DRIA Home Builders (Pty) Ltd. All rights reserved in original DRIA-owned material, subject to applicable third-party rights.
