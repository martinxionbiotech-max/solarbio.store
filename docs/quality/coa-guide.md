---
title: "Certificate of Analysis Guide"
description: "Guide to Solarbio Certificate of Analysis (COA) — document structure, test parameters, lot traceability, and how to request a COA."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Certificate of Analysis Guide",
 "description": "Guide to Solarbio Certificate of Analysis (COA) — document structure, test parameters, lot traceability, and how to request a COA.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Certificate of Analysis Guide

## COA Document Structure

Each Solarbio COA includes:

| Section | Content | Example Values |
|---|---|---|
| Header | Product name, SKU, lot number, manufacturing date | lot: SR20240401, mfg: 2024-04-15 |
| Specification Table | Parameter, specification limit, test result, test method | Appearance: white powder; Conforms |
| Physical Properties | Appearance, color, physical state, solubility | White crystalline powder; soluble in DMSO |
| Chemical Analysis | Purity (HPLC/GC), pH, moisture, identity (NMR, MS) | HPLC ≥99.0%; found 99.3% |
| Biological Testing | Activity assay, endotoxin, sterility (if applicable) | Endotoxin <0.5 EU/mL |
| Approval | QA signature, release date, approval status | Approved 2024-04-20 |

## Test Parameters by Product Category

| Product Category | QC Tests | Specification Limit | Method |
|---|---|---|---|
| PCR master mixes | Activity assay, DNase test, RNase test, sterility | Amplification efficiency >90% of reference; Nuclease negative | qPCR (GAPDH target); Fluorogenic substrate |
| DNA polymerases | Specific activity, exonuclease, endonuclease | 50–100 U/µL; Nuclease negative | Radioactive substrate; Plasmid digestion |
| ELISA kits | Calibrator recovery, precision, linearity | Recovery 90–110%; CV <10% | Four-parameter logistic curve fit |
| Antibodies | Titer, specificity, concentration, purity | Titer >512,000; >95% by SDS-PAGE | ELISA; A₂₈₀; SDS-PAGE densitometry |
| Assay kits | Standard curve R², blank OD, precision | R² >0.99; Blank <0.10 OD; CV <5% | Microplate reader |
| Small molecules | Purity, identity, moisture, heavy metals | ≥95–98%; NMR match; <0.5% H₂O; <10 ppm | HPLC; ¹H NMR; KF; ICP-MS |
| Buffers | pH, osmolality, sterility, endotoxin | ±0.1; ±5%; Sterile; <0.5 EU/mL | Meter; Osmometer; Filtration; LAL |
| Competent cells | Transformation efficiency, contamination | >10⁹ cfu/µg pUC19; No contamination | Plate counting; 3-day sterility test |

## Sample COA Entry Format

```
----------------------------------------------------------------------
Certificate of Analysis
----------------------------------------------------------------------
Product: 2×Taq PCR Master Mix
SKU: PC1100                    Lot: PC20240501
MFG Date: 2024-05-10           EXP Date: 2026-05-09
----------------------------------------------------------------------
Parameter              Specification         Result
----------------------------------------------------------------------
Appearance             Clear, colorless      Conforms
                       viscous liquid
pH                     8.5 ± 0.5            8.7
Activity               Amplify 1 kb target  Cq = 18.2 ± 0.5
                       (50 ng gDNA)
DNase                  Not detectable       <1 pg/reaction
RNase                  Not detectable       <1 pg/reaction
Sterility              No growth (14 d)     No growth
Endotoxin              <0.5 EU/mL           0.12 EU/mL
----------------------------------------------------------------------
QA Approval: __________________
Date: 2024-05-15
----------------------------------------------------------------------
```

## How to Request a COA

COAs can be requested via four methods:

1. **Solarbio Store — Order history page**: COA available as PDF download for each purchased lot
2. **Customer service email**: Send product SKU and lot number to technical support
3. **Product packaging — QR code**: Scan the QR code on the label to access COA via mobile browser
4. **Bulk order COA**: Available on request for wholesale and institutional accounts

### Typical Response Time

| Request Method | Response Time |
|---|---|
| Store download | Instant |
| QR code scan | Instant |
| Email request | Within 24 hours |
| Bulk order COA | Within 48 hours |

## COA Verification

To verify the authenticity of any Solarbio COA:

- Check the lot number format: YYYYMMDD + product code
- Verify the COA QR code links to https://solarbio.store/coa/{lot-number}
- Confirm QA approval signature and date
- Compare physical product packaging lot number against COA lot number

## Cross-References

- [▶ ISO Certifications](iso-certifications.md)
- [▶ GMP Compliance & Medical Device Registration](gmp-compliance.md)
- [▶ Storage & Shelf Life](storage-shelf-life.md)
- [▶ Quality Index](index.md)
- [▶ FAQ](../faq/index.md)

*[solarbio.store](https://solarbio.store)*
