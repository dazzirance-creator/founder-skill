# ASA colour retention: evidence request to polymer compounder

Status: **request sent** by Darren to the compounder. Follow-up pending.

## Goal

Get supporting evidence that our ASA product colours keep their colour for 10+ years outdoors.

## Parties

- **Sent from:** darren@drsjlegacy.co.uk (sent from Zoho Mail by Darren)
- **Sent to:** c.millinson@polymer-compounders.co.uk
- **Supplier:** polymer-compounders.com (ASA plastic product page)

## What we know

Published evidence found so far is thin and mostly vendor-sourced. It does not support a 10-year colour claim on its own.

- BASF Luran S literature (manufacturer claim, not independent): over 85% impact retention after 3 years outdoors. No ΔE values given.
- Mechanism: ASA's acrylate rubber has no C=C double bonds, so it avoids the photooxidation route that degrades ABS. A mechanism argument, not a lifetime figure.
- SAE paper 890591 (1989): colourfastness of an ASA polyblend in ten colours under accelerated, Xenon-arc, Florida and under-glass exposure. Only the abstract was read; results not verified.
- Yildirim et al. (via a materials-selection blog): ASA suitable for long-term outdoor use. ASA-specific ΔE numbers not seen.
- No independent ΔE-versus-years dataset for ASA was found.

Sources:
- https://issuu.com/mayfield/docs/asa_guide_and_uses
- https://saemobilus.sae.org/papers/correlations-accelerated-outdoor-weathering-asa-polymer-system-890591
- https://entecpolymers.com/resources/product-guides/ineos-styrolution-luran-s-product-guide
- https://www.formerra.com/products/chemistries/acrylonitrile-styrene-acrylate-asa
- https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/6482893

## Supplier page

The compounder's ASA page (https://polymer-compounders.com/asa-plastic/) could not be read. It sits behind a Cloudflare "Performing security verification" check, which returned HTTP 403 to both the fetch tool and headless Chromium. The page's claims are therefore unknown.

## Reference colour palette

Colours are bespoke, so the evidence request uses a fixed reference palette. Results are to be reported against these, not against individual shades.

| Reference | Hex (sRGB, approx.) |
|---|---|
| White | #F2F2F2 |
| Black | #1A1A1A |
| Grey (mid) | #808080 |
| Red | #C00000 |
| Yellow | #FFC000 |
| Green | #00703C |
| Blue | #0047AB |
| Light/pastel | #D9D2C5 |

Decision: master chip / RAL references were removed from the email. The compounder will work from hex codes. Hex is only approximate for ΔE work, so the compounder should confirm how they match each colour and which CIELAB values they use.

## What was asked of the compounder

For each reference colour:

1. ΔE*ab (CIELAB, D65/10°) at 1, 3, 5 and 10 years, or the longest outdoor exposure (Florida/Arizona, ASTM G7 / G90 or equivalent).
2. Accelerated weathering (ISO 4892-2 / ASTM G155 or QUV), with correlation to outdoor exposure.
3. Stabiliser package: UV absorber and HALS types and loadings, TiO2 grade.
4. Test standards and labs, and whether in-house or independent.
5. Confirmation they can reproduce each reference colour, and production tolerance.

If no 10-year data exists: the longest exposure covered and the extrapolation method. Also: whether they would give a 10-year colour-retention warranty, and under what conditions.

## Email drafts

- A Gmail draft exists in dazzi.rance@gmail.com (not Darren's address). It still contains the `[ref]` placeholders that were later removed. Not deleted. Deletion awaits confirmation.
- The sent Zoho email should be checked against the Sent folder to confirm the final text.

## Open items

- [ ] Confirm the exact text sent (Zoho Sent folder).
- [ ] Decide whether to delete the Gmail draft in dazzi.rance@gmail.com.
- [ ] Set the pass/fail threshold before results arrive (e.g. ΔE*ab ≤ 3 at 10 years).
- [ ] Get the compounder's response. Chase if no reply.
- [ ] Obtain the compounder's technical data sheet and weathering reports, or confirm they don't exist.
- [ ] Decide on an in-house exposure test if the compounder has no 10-year data. A 10-year programme cannot be completed quickly.
- [ ] Read the compounder's ASA product page from a browser that passes the Cloudflare check, and record its claims here.

## Working notes

- "Compounders" means polymer compounders (the resin suppliers), not another group.
- Do not cite the BASF 3-year figure as proof of 10 years.
- Lifespan claims depend heavily on shade. Pastels and yellows usually show change first.
