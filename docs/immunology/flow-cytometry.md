---
title: "Technical Specification: Flow Cytometry Reagents"
description: "Technical specifications for Solarbio flow cytometry products — fluorophore-conjugated antibodies (CD3, CD4, CD8, CD19, CD45), compensation beads, cell preparation buffers, and validated multi-color panel recommendations for immunophenotyping, apoptosis, and cell cycle analysis."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Flow Cytometry Reagents",
 "description": "Technical specifications for Solarbio flow cytometry products — fluorophore-conjugated antibodies (CD3, CD4, CD8, CD19, CD45), compensation beads, cell preparation buffers, and validated multi-color panel recommendations for immunophenotyping, apoptosis, and cell cycle analysis.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Flow Cytometry Reagents

## 1. Product Range

Solarbio flow cytometry reagents cover fluorophore-conjugated antibodies for immunophenotyping, apoptosis detection reagents, cell preparation buffers, and DNA content analysis reagents. All antibodies are titrated and validated for flow cytometry applications.

| Product | SKU Range | Available Conjugations | Clone | Reactivity |
|---|---|---|---|---|
| CD3 Antibody (Flow) | F1001–F1010 | FITC, PE, APC, PerCP-Cy5.5, PE-Cy7 | UCHT1 (human), 17A2 (mouse) | Human, mouse |
| CD4 Antibody (Flow) | F1020–F1029 | FITC, PE, APC, BV421, PerCP | RPA-T4 (human), GK1.5 (mouse) | Human, mouse |
| CD8 Antibody (Flow) | F1040–F1049 | FITC, PE, APC, BV421, PE-Cy7 | RPA-T8 (human), 53-6.7 (mouse) | Human, mouse |
| CD19 Antibody (Flow) | F1060–F1069 | FITC, PE, APC, PerCP-Cy5.5 | HIB19 (human), 6D5 (mouse) | Human, mouse |
| CD45 Antibody (Flow) | F1080–F1089 | FITC, PE, APC, PerCP, BV421 | HI30 (human), 30-F11 (mouse) | Human, mouse |
| Annexin V-FITC/PI | CA1020 | FITC + PI | — | All species |
| 7-AAD Viability Staining Solution | P8110 | — | — | All species |
| RNase A (DNase-free) | R1030 | — | — | For cell cycle analysis |

## 2. Fluorophore Selection and Spectral Characteristics

| Fluorophore | Ex Max (nm) | Em Max (nm) | Laser Line | Typical Detector | Relative Brightness | Photostability |
|---|---|---|---|---|---|---|
| FITC | 495 | 520 | 488 nm | FL1 (530/30) | Medium | Moderate |
| PE (R-Phycoerythrin) | 565 | 576 | 488 nm | FL2 (585/40) | Very high | High |
| PerCP | 479 | 675 | 488 nm | FL3 (670/LP) | Medium | Low |
| PerCP-Cy5.5 | 482 | 695 | 488 nm | FL3 (695/40) | High | Moderate |
| PE-Cy7 | 565 | 774 | 488 nm | FL4 (780/60) | High | Low (use with care) |
| APC | 650 | 660 | 633/640 nm | FL5 (660/20) | High | High |
| APC-Cy7 | 650 | 775 | 633/640 nm | FL6 (780/60) | High | Low |
| BV421 (Brilliant Violet 421) | 405 | 421 | 405 nm | FL7 (450/50) | Very high | Moderate |
| BV510 | 405 | 510 | 405 nm | FL8 (525/50) | High | Moderate |
| PI (Propidium Iodide) | 535 | 615 | 488 nm | FL3 (670/LP) | Medium | High |
| 7-AAD | 546 | 647 | 488 nm | FL3 (670/LP) | Medium | High |

## 3. Recommended Multi-Color Panels

### 3.1 Human T-cell Subtyping Panel (4-Color)

| Marker | Fluorophore | Function | Expected Population |
|---|---|---|---|
| CD45 | PerCP | Pan-leukocyte gate | All leukocytes |
| CD3 | FITC | T-cell marker | CD45⁺CD3⁺: 55–85% of lymphocytes |
| CD4 | PE | Helper T-cells | CD3⁺CD4⁺: 30–60% of T cells |
| CD8 | APC | Cytotoxic T-cells | CD3⁺CD8⁺: 15–40% of T cells |

### 3.2 Human B-cell Identification (3-Color)

| Marker | Fluorophore | Function | Expected Population |
|---|---|---|---|
| CD45 | PerCP | Pan-leukocyte gate | All leukocytes |
| CD19 | FITC | B-cell marker | CD45⁺CD19⁺: 5–15% of lymphocytes |
| CD20 | PE | Mature B-cell marker | CD19⁺CD20⁺: >90% of B cells |

### 3.3 Mouse Immunophenotyping (6-Color)

| Marker | Fluorophore | Laser | Cell Type |
|---|---|---|---|
| CD45 | BV510 | 405 nm | All leukocytes |
| CD3 | FITC | 488 nm | T cells |
| CD4 | PE | 488 nm | Helper T cells |
| CD8 | APC | 633 nm | Cytotoxic T cells |
| CD19 | PerCP-Cy5.5 | 488 nm | B cells |
| NK1.1 | PE-Cy7 | 488 nm | NK cells |

### 3.4 Apoptosis Detection

| Marker | Fluorophore | Detection | Interpretation |
|---|---|---|---|
| Annexin V | FITC | FL1 (530/30) | Phosphatidylserine externalization |
| PI | PI | FL3 (670/LP) | Membrane integrity |
| 7-AAD | 7-AAD | FL3 (670/LP) | Alternative to PI for live/dead gating |

### 3.5 Cell Cycle Analysis (PI DNA Staining)

| Parameter | Specification |
|---|---|
| Cell number | 1×10⁶ cells per sample |
| Fixation | 70% ethanol at -20°C, ≥2 h (up to 1 week) |
| RNase A | 100 μg/mL, 30 min at 37°C |
| PI staining | 50 μg/mL, 30 min at RT (dark) |
| Acquisition mode | Linear (not log) for PI-Area; doublet discrimination with PI-W vs. PI-A |

## 4. Buffer Specifications

| Buffer | Content | pH | Storage | Recommended Use |
|---|---|---|---|---|
| 10× Flow Cytometry Staining Buffer | PBS, 2% BSA, 0.1% NaN₃ | 7.4 | 2–8°C, 12 months | Antibody dilution, cell resuspension, washing |
| 1× RBC Lysis Buffer | 0.15 M NH₄Cl, 10 mM KHCO₃, 0.1 mM EDTA | 7.2 | RT, 12 months | Whole blood RBC lysis (10 min at RT) |
| Fixation Buffer | 4% paraformaldehyde in PBS | 7.4 | 2–8°C, 6 months (dark) | Cell fixation post-staining |
| Permeabilization Buffer | 0.1% saponin + 1% BSA in PBS | 7.4 | 2–8°C, 12 months | Intracellular staining; use with 0.3% saponin |
| Cell Cycle Staining Buffer | PBS + 0.1% Triton X-100 + RNase A + PI | 7.4 | Prepare fresh | Cell cycle analysis |

## 5. Antibody Titration Protocol

Accurate antibody titration is essential for optimal signal-to-noise ratio in flow cytometry. The recommended titration range is 1:25 to 1:800 (or 0.25–8 μg/mL).

| Dilution | Stain Index (Median Positive — Median Negative) / (2× rSD of Negative) | Recommendation |
|---|---|---|
| 1:25 | 25.3 | Slightly above saturation; high reagent consumption |
| 1:50 | 28.7 | Optimal (highest stain index) |
| 1:100 | 27.1 | Good; reduced reagent consumption |
| 1:200 | 21.5 | Acceptable for highly expressed antigens |
| 1:400 | 14.2 | Below optimal |

For a new antibody, titrate with 1×10⁵ positive cells per condition. The optimal dilution is the lowest concentration yielding maximal stain index.

## 6. Compensation and Controls

| Control Type | Purpose | Composition |
|---|---|---|
| Unstained control | Autofluorescence baseline | Cells only, no antibodies |
| Single-color compensation controls | Spectral overlap compensation | One fluorophore per tube; use compensation beads for each fluorophore |
| FMO (Fluorescence Minus One) controls | Gate boundary setting | All fluorophores except the one being gated |
| Isotype control | Confirm specific binding | Same concentration of isotype-matched non-specific antibody |

## 7. Troubleshooting

| Issue | Possible Cause | Solution |
|---|---|---|
| Low cell yield | Excessive washing/centrifugation | Reduce washing steps; use 300 × g, 5 min; resuspend gently |
| High debris (forward scatter low) | Dead cells; sample stored too long | Increase live/dead gate; add viability dye; use fresh samples |
| Doublet populations | Cell clumping; insufficient disaggregation | Filter through 40 μm mesh; reduce cell density; add DNase I |
| Poor separation (positive vs. negative) | Antibody under-titrated; target low expression | Titrate antibody; use brighter fluorophore; increase cell number |
| High background (all cells positive) | Non-specific binding; FC receptors | Add Fc block (2.4G2 for mouse; human IgG for human); include isotype control |
| Compensation errors (all in all channels) | Insufficient compensation controls; spectral overlap | Use single-color controls for each fluorophore; use compensation matrix |
| Dim signal despite high expression | Fluorophore degradation; photobleaching | Store antibodies at 4°C in dark; prepare fresh staining solution; add fixative after staining |

## 8. Cross-References

- [▶ See also: Apoptosis Detection Kits](../cell-biology/apoptosis-detection.md)
- [▶ See also: Antibodies](antibodies.md)
- [▶ See also: Cell Staining Reagents](../cell-biology/cell-staining.md)
- [▶ Related Protocol: Cell Culture Protocol](../protocols/cell-culture-protocol.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
