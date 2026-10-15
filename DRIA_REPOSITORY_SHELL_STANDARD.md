# DRIA Repository Shell Standard

**Control status:** Approved working standard  
**Reference implementation:** DRIA_Appliances_BOM  
**Scope:** GitHub repository shells and the central DRIA 4IR gateway  
**Operating rule:** GitHub-only preparation; no local asset bundles are required during the shell-building phase.

## 1. Repository pattern

Use the Appliances repository as the reference for the next product-family repositories:

- One repository per approved product family or defined infrastructure asset.
- A concise repository description (maximum 350 characters).
- A README that states the asset purpose, category count when confirmed, evaluation status, commercial baseline when approved, scope limitations, and procurement terms.
- An index.html only when that repository needs its own evaluation landing page.
- A PDF matrix only when the matrix has actually been generated and verified. Do not create placeholder or fake PDF files.
- Keep source category labels unchanged. Record spelling or data-quality issues separately; do not silently rewrite source labels.
- Do not claim compatibility, certification, endorsement, deployment, or sales that have not been verified.

## 2. Central gateway node pattern

Each gateway node should use the established vault-row, vault-info, and btn-green classes already present in index.html.

Required node fields:
- Volume or node title.
- Status label such as EVALUATION or LIVE, used only when accurate.
- Stable verification framework code.
- One green access button.

For a shell without an attached asset, do not publish a button to a file that does not exist. Add the node only when its target file or destination is committed and verified. For the Appliances reference, the button is intentionally PDF-matrix-only.

## 3. Commercial data controls

The supplied ItemCateogryExport.csv source contains 837 category rows. Each row has a stated value of $45,000 USD. The arithmetic row-value total is $37,665,000 USD if every row is treated as a separately valued item. This is a source-derived arithmetic total, not evidence of realized revenue, market value, a binding offer, or independently verified demand.

Do not use category counts or row-value totals as portfolio totals until duplicate checks, grouping rules, and the intended unit of sale have been confirmed.

## 4. Build sequence

1. Inventory source labels without changing them.
2. Map each label to a proposed product-family grouping and repository slug.
3. Check the organization for an existing repository before creating a new one.
4. Create the repository shell and README.
5. Add source files only when provided or deliberately generated and verified.
6. Add or update the central gateway node only after the destination is live.
7. Re-read committed files and verify every published link.
8. Keep an explicit pending status for anything that cannot be completed with available GitHub permissions.

## 5. Reference

- [DRIA Appliances BOM repository](https://github.com/driahomebuilders-publisher-systems/DRIA_Appliances_BOM)
- [DRIA 4IR gateway](https://driahomebuilders-publisher-systems.github.io/)

Copyright © 2026 DRIA Home Builders (Pty) Ltd. All rights reserved in original DRIA-owned material, subject to applicable third-party rights.
