---
title: "Technical Specification: Antibodies"
description: "Technical specifications for Solarbio primary and secondary antibodies — validation data, recommended dilutions, application compatibility, purity specifications, and conjugation options for Western blot, IHC, IF, flow cytometry, and ELISA applications."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Antibodies",
 "description": "Technical specifications for Solarbio primary and secondary antibodies — validation data, recommended dilutions, application compatibility, purity specifications, and conjugation options for Western blot, IHC, IF, flow cytometry, and ELISA applications.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Antibodies

## 1. Product Types

Solarbio antibodies are manufactured using hybridoma technology or recombinant expression and validated for specific research applications. Secondary antibodies are affinity-purified to minimize cross-reactivity. Isotype controls are matched to primary antibody species and subclass.

| Type | Format | Available Hosts | Available Conjugations |
|---|---|---|---|
| Primary antibodies — polyclonal | Purified IgG, whole antiserum | Rabbit, mouse, goat | Unconjugated |
| Primary antibodies — monoclonal | Purified IgG, ascites-free | Mouse, rabbit | Unconjugated, biotin |
| Secondary antibodies | Affinity-purified F(ab′)₂ or whole IgG | Goat anti-rabbit, goat anti-mouse, donkey anti-goat | HRP, FITC, TRITC, Cy3, Cy5, Biotin |
| Control antibodies | IgG isotype controls (matching subclass) | Mouse IgG1, IgG2a, IgG2b; rabbit IgG | Various |
| Antibody diluent | Ready-to-use | — | — |
| Antibody stripping buffer | Ready-to-use | — | — |

## 2. Recommended Dilutions by Application

### 2.1 Primary Antibody Dilutions

| Application | Starting Dilution | Optimal Range | Incubation | Buffer |
|---|---|---|---|---|
| Western blot | 1:500 | 1:500–1:2000 | 1 h at RT or overnight at 4°C | 5% BSA or 5% non-fat milk in TBST |
| IHC (paraffin) | 1:100 | 1:50–1:200 | Overnight at 4°C | PBS or Tris buffer |
| Immunofluorescence | 1:200 | 1:100–1:500 | 1 h at RT or overnight at 4°C | PBS + 1% BSA + 0.1% Triton X-100 |
| Flow cytometry | 1:100 | 1:50–1:200 | 30–60 min at 4°C (dark) | FACS buffer (PBS + 1% BSA + 0.1% NaN₃) |
| ELISA | 1:1000 | 1:500–1:5000 | 1 h at 37°C | ELISA diluent (blocking buffer) |
| Immunoprecipitation | 1:50 | 1:20–1:100 | 2 h at 4°C to overnight | Low-stringency lysis buffer |

### 2.2 Secondary Antibody Dilutions

| Application | Host – Target | Conjugate | Recommended Dilution | Storage After Dilution |
|---|---|---|---|---|
| Western blot | Goat anti-rabbit IgG | HRP | 1:5000–1:10000 | Prepare fresh; discard after use |
| Western blot | Goat anti-mouse IgG | HRP | 1:5000–1:10000 | Prepare fresh |
| IHC (paraffin) | Goat anti-rabbit IgG | HRP | 1:200–1:500 | Prepare fresh |
| Immunofluorescence | Goat anti-rabbit IgG | FITC | 1:500–1:1000 | Use within 1 h; protect from light |
| Immunofluorescence | Goat anti-mouse IgG | Cy3 | 1:500–1:1000 | Use within 1 h; protect from light |
| Flow cytometry | Goat anti-mouse IgG | FITC | 1:200–1:500 | Prepare fresh; protect from light |
| Flow cytometry | Goat anti-rabbit IgG | PE | 1:200–1:500 | Prepare fresh; protect from light |
| ELISA | Goat anti-rabbit IgG | HRP | 1:5000–1:10000 | Prepare fresh |

## 3. Quality Control Specifications

| Parameter | Specification | Test Method |
|---|---|---|
| Purity (SDS-PAGE) | ≥95% for affinity-purified; ≥90% for whole IgG | SDS-PAGE, Coomassie Blue staining |
| Antigen-specific ELISA titer | >1:10,000 for polyclonal; EC₅₀ ≤ 100 ng/mL for monoclonal | Indirect ELISA against immunogen |
| Endotoxin | <1.0 EU/mg for in vivo-grade antibodies | LAL chromogenic assay |
| BSA content | <5% (BSA-free formulations available on request) | Bradford assay |
| Aggregation (SEC-HPLC) | <5% aggregates for purified IgG | Size exclusion chromatography |
| Buffer | PBS (pH 7.4) with 0.02% sodium azide | — |
| Sterility | Sterile-filtered (0.22 μm) | USP <71> |
| Storage | -20°C (aliquoted) or 2–8°C | — |
| Shelf life | 12 months at -20°C; 6 months at 2–8°C | — |

## 4. Conjugate Selection Guide

| Conjugate | Ex/Em (nm) | Laser Line | Application | Relative Brightness |
|---|---|---|---|---|
| Unconjugated | — | — | WB, IHC, IP, ELISA | N/A |
| HRP | 370/420 (TMB), 550/570 (DAB) | — | WB, IHC, ELISA | High |
| Biotin | — | — | Amplification systems (WB, IHC, ELISA) | Very high (streptavidin amplification) |
| FITC | 495/520 | 488 nm | FACS, IF | Medium |
| TRITC | 557/576 | 543 nm | IF, FACS | Medium |
| Cy3 | 552/570 | 543 nm | IF, FACS | High |
| Cy5 | 649/670 | 633 nm | FACS, multiplex IF | High |
| PE (R-Phycoerythrin) | 565/576 | 488 nm | FACS | Very high |
| APC (Allophycocyanin) | 650/660 | 633 nm | FACS | High |
| PerCP | 479/675 | 488 nm | FACS (FL3) | Medium |

## 5. Antibody Validation Strategy

Solarbio antibodies are validated using a three-tier approach:

| Validation Tier | Method | Acceptance Criterion |
|---|---|---|
| Tier 1 — Binding | Direct ELISA against recombinant immunogen | EC₅₀ ≤ 100 ng/mL (monoclonal); titer >1:10,000 (polyclonal) |
| Tier 2 — Specificity | Western blot of cell lysates ± blocking peptide | Single dominant band at predicted MW; band eliminated by peptide competition |
| Tier 3 — Application | Application-specific testing | Matches published MW in 2+ independent cell lines (WB); correct subcellular localization (IF) |

### 5.1 Western Blot Validation (Example — Anti-β-Actin, Mouse Monoclonal)

| Cell Lysate | Expected MW | Observed MW | Specificity |
|---|---|---|---|
| HEK293 | 42 kDa | 42 kDa | Single band |
| HeLa | 42 kDa | 42 kDa | Single band |
| A549 | 42 kDa | 42 kDa | Single band |
| Recombinant β-actin | 42 kDa | 42 kDa | Single band |

## 6. Storage and Handling

| Formulation | Short-term (≤3 months) | Long-term (>3 months) | Notes |
|---|---|---|---|
| Purified IgG (liquid) | 2–8°C | -20°C in aliquots | Do not refreeze thawed aliquots |
| Purified IgG (lyophilized) | 2–8°C | -20°C after reconstitution | Reconstitute at 1 mg/mL |
| Conjugated IgG (HRP) | 2–8°C | -20°C with 50% glycerol | Store dark; avoid freeze-thaw |
| Conjugated IgG (FITC/Cy3/Cy5) | 2–8°C (dark) | -20°C in aliquots (dark) | Protect from light |
| Whole antiserum | 2–8°C | -20°C | 0.02% NaN₃ present |
| Isotype controls | 2–8°C | -20°C in aliquots | Match to primary antibody |

## 7. Troubleshooting

| Issue | Possible Cause | Solution |
|---|---|---|
| High background (WB) | Secondary antibody too concentrated; insufficient blocking | Reduce secondary 1:10,000; increase blocking to 1 h at RT or overnight at 4°C |
| No signal (WB) | Primary antibody expired; antigen degraded | Verify antibody with positive control lysate; use fresh sample; add protease inhibitors |
| Multiple bands (WB) | Non-specific binding; sample degradation | Use blocking peptide competition; reduce gel loading; add fresh protease inhibitors |
| High background (IHC) | DAB incubation too long; insufficient blocking | Reduce DAB to 1–3 min; block with 10% normal serum for 30 min |
| Weak staining (IF) | Primary antibody too dilute; fixation over-aggressive | Titrate primary antibody 1:50; use 2–4% PFA instead of methanol fixation |
| Granular staining (IF) | Antibody aggregates | Centrifuge antibody at 12,000 × g for 10 min before use |

## 8. Cross-References

- [▶ See also: Immunohistochemistry Reagents](immunohistochemistry.md)
- [▶ See also: ELISA Kits](elisa-kits.md)
- [▶ See also: Flow Cytometry Reagents](flow-cytometry.md)
- [▶ Related Protocol: Western Blot](../protocols/western-blot.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
