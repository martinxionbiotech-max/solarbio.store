---
title: "Technical Specification: Competent Cells"
description: "Technical specifications for Solarbio competent cells — DH5α, DH5α-T1, JM109, BL21(DE3) and other strains with transformation efficiency data, full genotypes, protocol guidance, and troubleshooting for cloning and protein expression."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Competent Cells",
 "description": "Technical specifications for Solarbio competent cells — DH5α, DH5α-T1, JM109, BL21(DE3) and expression strains. Full genotypes, transformation efficiencies, heat-shock protocols, blue-white screening guidance, and troubleshooting.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Competent Cells"}
}
</script>

# Technical Specification: Competent Cells

!!! note "Official Source"
    Technical documentation published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial orders: **[solarbio.store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Strain Type | Transformation Efficiency | Key Features | Applications |
|---|---|---|---|---|---|
| DH5α Competent Cell | C1100 | Cloning strain | ≥1×10⁸ CFU/μg | recA1 endA1, blue-white screening | Routine cloning, plasmid propagation, blue-white screening |
| DH5α-T1 Competent Cell | C1180 | High-efficiency cloning | ≥1×10⁹ CFU/μg | tonA (T1 phage resistance) | Library construction, difficult ligations, high-throughput cloning |
| JM109 Competent Cell | C1200 | Cloning strain | ≥1×10⁸ CFU/μg | M13 phage permissive, lacIq | Routine cloning, M13 phage production, blue-white screening |
| BL21(DE3) Competent Cell | C1300 | Expression strain | ≥1×10⁷ CFU/μg | T7 RNA polymerase | T7-driven protein expression |
| BL21(DE3)pLysS Competent Cell | C1350 | Expression strain with T7 suppression | ≥1×10⁶ CFU/μg | pLysS (chloramphenicol R) | Toxic protein expression, T7 leaky expression control |
| TOP10 Competent Cell | C1400 | High-efficiency cloning | ≥1×10⁹ CFU/μg | StrR, endA1, lacZΔM15 | High-efficiency cloning, plasmid preparation |

### 1.1 Cell Competence Preparation Technology

Solarbio competent cells are prepared by the **Rubidium chloride / calcium chloride chemical method** which yields transformation efficiencies of 10⁸–10⁹ CFU/μg. The cells are treated with CaCl₂ (100 mM) to create transient pores in the cell membrane, allowing DNA entry during the heat-shock step. The addition of RbCl and glycerol during preparation enhances the competence level and maintains viability during -80°C storage.

**Competence mechanism:** Divalent cations (Ca²⁺, Rb⁺) neutralize electrostatic repulsion between the negatively charged DNA phosphate backbone and the negatively charged outer membrane of *E. coli*. During the 42°C heat shock, thermal convection drives DNA through the membrane pores. The cells are then recovered in nutrient-rich SOC medium to repair membrane damage and initiate β-lactamase or other selection marker expression.

## 2. Genotype

| Strain | Genotype | Phenotypic Markers |
|---|---|---|
| DH5α | F⁻ φ80lacZΔM15 Δ(lacZYA-argF)U169 recA1 endA1 hsdR17(rₖ⁻ mₖ⁺) phoA supE44 λ⁻ thi-1 gyrA96 relA1 | lacZ⁻, recA⁻ (recombination deficient), endA1 (reduces plasmid degradation), hsdR17 (no restriction of unmethylated DNA) |
| DH5α-T1 | F⁻ φ80lacZΔM15 Δ(lacZYA-argF)U169 recA1 endA1 hsdR17(rₖ⁻ mₖ⁺) phoA supE44 λ⁻ thi-1 gyrA96 relA1 tonA | Same as DH5α + tonA (T1 phage resistance) |
| JM109 | endA1 glnV44 thi-1 relA1 gyrA96 recA1 mcrB⁺ Δ(lac-proAB) e14⁻ [F′ traD36 proAB⁺ lacIq lacZΔM15] hsdR17(rₖ⁻ mₖ⁺) | F′ episome carries lacIq (overproduces Lac repressor for controlled expression) |
| BL21(DE3) | F⁻ ompT hsdSₙ(rₙ⁻ mₙ⁻) gal dcm (DE3) | ompT (lacks outer membrane protease), DE3 (T7 RNA polymerase gene in chromosome) |
| BL21(DE3)pLysS | F⁻ ompT hsdSₙ(rₙ⁻ mₙ⁻) gal dcm (DE3) pLysS (Cmᴿ) | Contains pLysS plasmid with T7 lysozyme (suppresses T7 RNA polymerase) |

### 2.1 Key Genotype Features Explained

| Genetic Marker | Meaning | Practical Benefit |
|---|---|---|
| recA1 | Inactivated RecA protein — no homologous recombination | Plasmid stability; prevents rearrangements of cloned inserts |
| endA1 | Inactivated Endonuclease I | Higher quality plasmid preps (less nicking of plasmid DNA) |
| hsdR17 (rₖ⁻ mₖ⁺) | No Type I restriction activity; methylation intact | Accepts unmethylated DNA (PCR products, non-E. coli DNA) |
| lacZΔM15 | β-galactosidase ω-fragment deletion | Blue-white screening with α-complementation vectors (pUC, pBluescript) |
| tonA (DH5α-T1) | T1 phage receptor absent | T1 phage-resistant; suitable for library construction |
| DE3 (BL21 strains) | T7 RNA polymerase gene under lacUV5 promoter | IPTG-inducible T7-driven expression |
| ompT (BL21) | Lacks outer membrane protease | Reduced proteolysis of expressed proteins |
| pLysS (BL21-DE3 pLysS) | T7 lysozyme (inhibits T7 RNA polymerase) | Reduces basal expression; essential for toxic proteins |

## 3. Transformation Protocol

### 3.1 Heat-Shock Method

| Step | DH5α/DH5α-T1 (C1100/C1180) | BL21(DE3) (C1300) |
|---|---|---|
| Thaw cells | On ice, 5 min | On ice, 5 min |
| Add DNA | 1–10 μL ligation or 1 μL (10 pg–10 ng) plasmid | 1–10 μL plasmid (1–100 ng) |
| Incubate | Ice 30 min (critical — longer is NOT better) | Ice 30 min |
| Heat shock | 42°C, 45 s (exact timing ±5 s) | 42°C, 45 s |
| Recovery | Ice 2 min | Ice 2 min |
| Add SOC/LB | 500–950 μL (SOC preferred for highest recovery) | 500–950 μL |
| Incubate | 37°C, 200 rpm, 1 h | 37°C, 200 rpm, 1 h |
| Plate | 50–200 μL on LB+antibiotic (use 100 μL for ligations) | 50–200 μL on LB+antibiotic |

### 3.2 Efficiency Calculation

\[
\text{Efficiency (CFU/μg)} = \frac{\text{Colony count} \times \text{Dilution factor} \times 1000}{\text{ng DNA plated}}
\]

**Example:** 200 colonies from 100 μL of a 1:10 dilution of 1 ng pUC19 transformation plated:
- Total cells: 200 × 10 × (950 μL / 100 μL) = 19,000 CFU
- Efficiency: 19,000 / 1 ng × 1000 = 1.9×10⁷ CFU/μg

### 3.3 Quality Control Specification

| QC Parameter | DH5α (C1100) | DH5α-T1 (C1180) | BL21(DE3) (C1300) |
|---|---|---|---|
| Minimum efficiency (pUC19) | 1×10⁸ CFU/μg | 1×10⁹ CFU/μg | 1×10⁷ CFU/μg |
| Freeze-thaw stability | ≤ 1 cycle | ≤ 1 cycle | ≤ 1 cycle |
| Viability at -80°C (12 months) | ≥ 80% | ≥ 80% | ≥ 80% |
| Contamination (non-E. coli) | None | None | None |
| Blue-white screening | > 98% blue colonies with intact lacZ | > 98% | N/A |
| Expression induction (BL21) | N/A | N/A | > 90% induced cultures show target protein |

## 4. Blue-White Screening Procedure

### 4.1 Required Materials

| Item | Specification |
|---|---|
| LB agar plates | Containing 100 μg/mL ampicillin (or other selection antibiotic) |
| IPTG | 0.1 M stock; add 40 μL per plate (final 0.4 mM) |
| X-gal | 20 mg/mL in DMF; add 40 μL per plate (final 80 μg/mL) |
| Spread on LB agar plates | 15 min drying at 37°C before use |

### 4.2 Interpretation

| Colony Color | Interpretation |
|---|---|
| Blue | Vector re-ligated without insert (intact lacZ) |
| White | Insert successfully cloned (disrupted lacZ) |
| Pale blue | Small insert may not fully disrupt lacZ; sequence-confirm |
| Mixed blue/white sectors | Colony derived from multiple cells; re-streak |

## 5. Storage and Handling

| Parameter | Requirement |
|---|---|
| Storage temperature | -80°C (constant) |
| Shipping | Dry ice (≤ 48 h transit) |
| Freeze-thaw | Do NOT re-freeze (single-use aliquots: 50–100 μL) |
| Thawing | On ice only (5–10 min); never warm to RT |
| Handling | Use cold pipette tips; work quickly on ice; minimize handling |
| Shelf life | 12 months from manufacture (if stored continuously at -80°C) |

## 6. Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| Few or no transformants | Cells thawed incorrectly | Always thaw on ice; never warm to RT |
| | Heat-shock temperature/timing wrong | Calibrate water bath to exactly 42°C; do not exceed 45 s |
| | DNA amount too high (> 50 ng) | Use 1–10 ng per 50 μL cells (plasmid) or 5–10 μL ligation |
| | Antibiotic concentration too high | Verify working concentration (e.g., ampicillin 100 μg/mL, kanamycin 50 μg/mL) |
| | SOC/LB too cold after heat shock | Use pre-warmed SOC (37°C) |
| | Ligase salts inhibit transformation | Purify ligation (ethanol precipitation or column clean-up) before transforming |
| Too many blue colonies (white screening) | Incomplete X-gal/IPTG spread | Spread fresh; use foil-wrapped X-gal (light-sensitive) |
| | Vector lacZ intact (re-ligation) | CIP-treat vector after linearization; use gel-purified vector |
| All white colonies (no blue control) | No IPTG/X-gal added | Always include pUC19 + X-gal/IPTG positive control |
| | lacZΔM15 strain mixed up | Verify strain genotype |
| Cells clump or precipitate | Improper thawing | Discard and use fresh aliquot |
| | Multiple freeze-thaw cycles | Aliquot at first use; never re-freeze |
| Low transformation with ligation | Insert-to-vector ratio wrong | Use 3:1 molar ratio (sticky) or 5:1 (blunt) |
| | Insert contains secondary structures | Linearize insert; use gel-purified DNA |

[▶ Related Protocol: Competent Cell Transformation Protocol](../protocols/competent-cell-transformation.md)
[▶ See also: Cloning & Ligation Reagents](cloning-reagents.md)

*Product procurement: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
