# Community & Student Affairs (CSA) Standard Operating Procedures

A home for how CSA does its recurring work. Staff can search procedures, review drafts, and start new guidance.

> **Status: placeholder.** The procedures here are being updated with the CSA teams. Until that work is finished, treat what's here as a working draft, not approved guidance.

**Live site:** https://melatkins2-ops.github.io/csa-operating-process-library/

## What's here

- `index.html`: the front door (search, browse, review drafts, start new guidance)
- `sop-library.html`: all procedures, filterable by status and department
- `sop.html`: a single procedure
- `sop-builder.html`: start or draft new guidance
- `draft-data.js`: the procedure records, including status (Approved, Source-derived draft, Identified only)
- `images/`: GRPS logo and page photography

## Good to know

- Status matters: a *source-derived draft* is written but not yet validated, and is not approved guidance.
- To add or update a procedure, edit its record in `draft-data.js`.

## Updating the site

Edit the files on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths and fails if the page throws a JavaScript error, a local file or image is missing, or the page scrolls sideways. See the Actions tab for results.

Maintained by GRPS Community & Student Affairs.
