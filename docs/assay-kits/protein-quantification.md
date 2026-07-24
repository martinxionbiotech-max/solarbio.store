---
title: "Technical Specification: Protein Quantification Kits"
description: "Technical specifications for Solarbio protein quantification assay kits — BCA, Bradford, Lowry, UV direct, and biuret methods with comprehensive interference tables, linear ranges, detection limits, CV data, and protocol optimization guides."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Protein Quantification Kits",
 "description": "Full specifications for Solarbio protein quantification assay kits — BCA, Bradford, Lowry, UV A₂₈₀, and biuret methods with optimization guides and interference data.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Protein Quantification Assay"}
}
</script>

# Technical Specification: Protein Quantification Kits

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Product Range

| Product | SKU | Principle | Wavelength | Detection Limit | Linear Range | Assay Time | Sample Volume |
|---|---|---|---|---|---|---|---|
| BCA Protein Assay Kit | BC3180 | Cu²⁺ reduction (biuret) + BCA chromophore | 562 nm | 5 μg/mL | 20–2000 μg/mL | 30 min (60°C) or 2 h (RT) | 25 μL |
| Bradford Protein Assay Kit | BC3200 | Coomassie Brilliant Blue G-250 (CBB shift) | 595 nm | 5 μg/mL | 50–1500 μg/mL | 10 min (RT) | 50 μL |
| Lowry Protein Assay Kit | BC3220 | Folin-Ciocalteu reagent (phosphomolybdic-tungstate reduction) | 650 nm | 2 μg/mL | 5–200 μg/mL | 45 min (RT) | 50 μL |
| UV Protein Assay (A₂₈₀) | BC3240 | Direct tryptophan/tyrosine absorbance | 280 nm | 50 μg/mL | 100–3000 μg/mL | Immediate | 100–500 μL |
| Biuret Protein Assay Kit | BC3260 | Cu²⁺-peptide complex (violet) | 540 nm | 200 μg/mL | 500–15000 μg/mL | 30 min (RT) | 200 μL |

## 2. Method Comparison

| Feature | BCA | Bradford | Lowry | UV A₂₈₀ | Biuret |
|---|---|---|---|---|---|
| Sensitivity (detection limit) | 5 μg/mL (++) | 5 μg/mL (++) | 2 μg/mL (+++) | 50 μg/mL (+) | 200 μg/mL (−) |
| Linear range | 20–2000 μg/mL | 50–1500 μg/mL | 5–200 μg/mL | 100–3000 μg/mL | 500–15000 μg/mL |
| Detergent compatibility | Good (≤5% SDS) | Poor (≤0.1% SDS) | Fair (≤1% SDS) | Excellent | Fair |
| Reducing agent compatibility | Poor (DTT, β-ME interfere) | Good | Poor (DTT, β-ME interfere) | Excellent | Fair |
| Protein-to-protein variation | Low (±10%) | High (±40%) | Medium (±20%) | Highest (±60%) | Low (±10%) |
| Assay time | 30 min (60°C) | 10 min (RT) | 45 min (RT) | Immediate | 30 min (RT) |
| One-step protocol | Yes (mix & incubate) | Yes | No (multi-reagent, timing critical) | N/A | Yes |
| Standard required | BSA or IgG | BSA or IgG | BSA or IgG | None (extinction coefficient) | BSA |
| pH sensitivity | Moderate (pH 9–11) | Low (pH 1–12.5) | High (pH 10–10.5) | None | Low |
| Interferences | Many | Few | Many | Few | Moderate |
| Cost per assay | $$ | $ | $$ | Free (no reagents) | $ |

## 3. Detailed Protocol Specifications

### 3.1 BCA Assay Kit (BC3180)

**Reaction Chemistry**:

```
Protein peptide bonds + Cu²⁺ ──[50–60°C, alkaline pH]──→ Cu⁺ (reduced)

Cu⁺ + 2 × BCA⁺ (pale green) → BCA₂-Cu⁺ complex (purple, λ_max = 562 nm)
```

The BCA assay is based on two reactions: (1) reduction of Cu²⁺ to Cu⁺ by protein peptide bonds in alkaline solution (biuret reaction), and (2) specific chelation of Cu⁺ by bicinchoninic acid to form a stable purple complex.

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 562 nm |
| Limit of detection | 5 μg/mL (BSA) |
| Lower limit of quantification | 20 μg/mL |
| Linear range | 20–2000 μg/mL (extended to 20–5000 with microplate) |
| Intra-assay CV | <5% (n=20, 500 μg/mL) |
| Inter-assay CV | <10% (n=10 lots) |
| Recovery (BSA spike) | 95–105% |
| Recommended incubation | 30 min at 60°C (enhanced sensitivity) |
| Alternative incubation | 2 h at RT (convenience) or overnight at 37°C |
| Color stability | ≥1 h at RT after cooling |
| Standard | BSA (2 mg/mL ampule, 5×1 mL) |
| Capacity | 500 assays (microplate) or 250 (cuvette) |
| Storage | RT, 24 months |

**Standard Curve Preparation (96-well plate)**:

| BSA Standard (μg/mL) | A₅₆₂ (60°C, 30 min) | A₅₆₂ (RT, 2 h) |
|---|---|---|
| 0 (blank) | 0.000 | 0.000 |
| 25 | 0.037 | 0.022 |
| 50 | 0.068 | 0.040 |
| 125 | 0.164 | 0.098 |
| 250 | 0.320 | 0.195 |
| 500 | 0.625 | 0.385 |
| 750 | 0.912 | 0.565 |
| 1000 | 1.180 | 0.735 |
| 1500 | 1.620 | 1.040 |
| 2000 | 2.010 | 1.310 |

R² > 0.998 for both incubation conditions.

**Interference in the BCA Assay**:

| Substance | Concentration Causing 10% Error | Mechanism |
|---|---|---|
| DTT | >1 mM | Reduces Cu²⁺ directly |
| β-Mercaptoethanol | >1 mM | Reduces Cu²⁺ directly |
| EDTA | >10 mM | Chelates Cu²⁺ |
| Tris | >250 mM | Slight Cu²⁺ reduction |
| Glucose | >10 mM | Reduces Cu²⁺ at high temperature |
| Sucrose | >10% | Minimal interference |
| SDS | ≤5% (below 2% preferred) | Slight enhancement |
| Triton X-100 | ≤1% | Minimal interference |
| Glycerol | ≤10% | Minimal interference |

**Method for Reducing Agent-Containing Samples**:
1. Dilute sample to bring reducing agent below threshold
2. Use the included "compatible reagent" to mask DTT/β-ME up to 5 mM
3. Alternative: use the Bradford method instead

### 3.2 Bradford Assay Kit (BC3200)

**Reaction Chemistry**:

```
Coomassie Blue G-250 + Protein (pH <1) → CBB-Protein complex (λ shift 465→595 nm)
├─ CBB (free): 465 nm (red/brown)
└─ CBB (bound to protein): 595 nm (blue)
```

The free dye is red/brown (absorbing at 465 nm) in the acidic reagent. Upon binding to protein (primarily arginine, aromatic residues), the dye yields a blue shift to 595 nm with a large increase in molar absorptivity.

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 595 nm |
| Limit of detection | 5 μg/mL |
| Linear range | 50–1500 μg/mL (BSA); 50–2000 (IgG) |
| Intra-assay CV | <6% |
| Inter-assay CV | <12% |
| Reaction time | 10 min at RT |
| Color stability | 1 h at RT |
| Standard | BSA (2 mg/mL ampule) or IgG |
| Capacity | 500 assays (microplate) |

**Critical Notes**:
- The dye reagent is acidic (phosphoric acid ~2.5%, methanol ~5%) and protein-to-protein variation is high. BSA produces a different slope than IgG or most sample proteins. For accurate absolute quantification, use a standard matching the target protein.
- Detergents (SDS >0.1%, Triton X-100 >0.1%) cause severe interference and precipitate the dye reagent.
- The Bradford response is nonlinear at high protein concentrations. Always construct a curve with 5–7 points.

**Standard Curve Values**:

| BSA (μg/mL) | A₅₉₅ | IgG (μg/mL) | A₅₉₅ |
|---|---|---|---|
| 0 | 0.000 | 0 | 0.000 |
| 50 | 0.050 | 50 | 0.035 |
| 100 | 0.098 | 100 | 0.068 |
| 250 | 0.244 | 250 | 0.170 |
| 500 | 0.478 | 500 | 0.335 |
| 1000 | 0.895 | 1000 | 0.640 |
| 1500 | 1.250 | 1500 | 0.910 |

**Interference in the Bradford Assay**:

| Substance | Maximum Tolerated |
|---|---|
| SDS | ≤0.1% |
| Triton X-100 | ≤0.05% |
| NP-40 | ≤0.05% |
| Tween-20 | ≤0.1% |
| Tris | ≤100 mM |
| EDTA | ≤5 mM |
| GSH | ≤1 mM |
| DTT | ≤5 mM |
| Urea | ≤3 M |
| Guanidine·HCl | ≤1 M |

### 3.3 Lowry Assay Kit (BC3220)

**Reaction Chemistry**:

```
Protein + Cu²⁺ ──[Alkaline, RT, 20 min]──→ Cu⁺-protein complex
Cu⁺-protein + Folin-Ciocalteu reagent (phosphomolybdic/phosphotungstic acid)
    ──[RT, 30 min]──→ Reduced chromogen (λ_max = 650 nm, blue)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint (dual reagent, sequential addition) |
| Wavelength | 650 nm |
| Limit of detection | 2 μg/mL |
| Linear range | 5–200 μg/mL |
| Intra-assay CV | <6% |
| Timing sensitivity | High (30 min exactly for Folin step) |
| Capacity | 200 assays |

**Critical Notes**:
- The Folin-Ciocalteu reagent reacts with Cu⁺ and also with tyrosine and tryptophan residues. The Lowry assay is 3–5× more sensitive than BCA for most proteins but has higher protein-to-protein variation.
- Timing of the Folin addition and incubation is critical — the 30 min incubation must be consistent across all tubes.
- The Folin reagent is light-sensitive; protect during storage.
- The assay is incompatible with EDTA (>1 mM), Tris (>50 mM), and reducing agents (DTT, β-ME >0.5 mM).

### 3.4 UV A₂₈₀ Method (BC3240)

**Principle**:

Protein concentration is estimated directly from absorbance at 280 nm, based on tryptophan and tyrosine content. No chromogenic reagents are required.

| Parameter | Specification |
|---|---|
| Wavelength | 280 nm |
| Limit of detection | 50 μg/mL (BSA) |
| Linear range | 100–3000 μg/mL |
| Instrument | Requires a UV-capable spectrophotometer |
| Cuvette requirement | Quartz (plastic/polystyrene absorbs at 280 nm) |
| Standard | N/A (use extinction coefficient) |

**Extinction Coefficients**:

| Protein | A₂₈₀ (1 mg/mL, 1 cm) |
|---|---|
| BSA (bovine serum albumin) | 0.66 |
| IgG (human γ-globulin) | 1.38 |
| Lysozyme | 2.64 |
| Ovalbumin | 0.67 |
| Trypsin | 1.53 |
| Generic (if composition unknown) | 1.0 |

**Correction for Nucleic Acid Contamination**:

```
A₂₈₀ (corrected protein) = A₂₈₀ − 1.55 × A₂₆₀
Protein (mg/mL) = A₂₈₀ (corrected) / ε
```

The factor 1.55 corrects for nucleic acids at A₂₆₀, where A₂₆₀/A₂₈₀ > 0.5 indicates significant nucleic acid contamination.

### 3.5 Biuret Assay Kit (BC3260)

```
Protein + Cu²⁺ ──[NaOH, pH >12, RT]──→ Cu²⁺-peptide complex (violet, 540 nm)
```

| Parameter | Specification |
|---|---|
| Linear range | 0.5–15 mg/mL |
| Detection limit | 200 μg/mL |
| Application | High-concentration samples, plasma/serum total protein |

The biuret method is the standard clinical chemistry method for total serum protein (coupled with albumin/bromocresol green for albumin).

## 4. Sample Preparation Guide

### 4.1 General Recommendations

| Sample Type | Recommended Method | Notes |
|---|---|---|
| Purified protein (PBS/Buffer) | UV A₂₈₀ (if pure) or BCA | UV is fastest; BCA for low concentrations |
| Cell lysate (RIPA buffer) | BCA (RIPA-compatible) | Bradford incompatible with SDS in RIPA |
| Serum/plasma | BCA or Biuret | Dilute 1:50–1:200 for BCA; use biuret for clinical |
| Tissue homogenate | BCA or Lowry | Homogenize in PBS or RIPA |
| Column fractions (FPLC) | Bradford (quick check) or BCA (accurate) | Detergents in elution buffer affect choice |
| Bacterial lysate (E. coli) | BCA or Lowry | Include lysozyme, sonication |
| Membrane protein extract | BCA (with SDS included) | Bradford fails due to detergents |
| Plant extracts | BCA or Lowry | Account for phenolics interference |

### 4.2 Choosing the Right Method — Decision Flowchart

```
Is sample pure protein (>90%)?
    ├─ Yes → UV A₂₈₀ (fastest, no reagent cost)
    │          └─ 280 nm quartz cuvette required
    └─ No → Does sample contain reducing agents (DTT, β-ME)?
               ├─ Yes → Bradford method (reducing agent compatible)
               └─ No → Does sample contain detergents (>0.1%)?
                           ├─ Yes → BCA (compatible up to 5% SDS)
                           └─ No → Either BCA or Bradford (check linear range)
                                      └─ Low volume (<5 μL protein)? → Lowry (most sensitive)
```

## 5. Interference Summary Table

| Substance | BCA (BC3180) | Bradford (BC3200) | Lowry (BC3220) | UV A₂₈₀ (BC3240) |
|---|---|---|---|---|
| SDS (≤5%) | ✓ (compatible) | ✗ (<0.1%) | ✓ | ✓ |
| Triton X-100 (≤1%) | ✓ | ✗ (<0.1%) | ✓ | ✓ |
| Tween-20 (≤1%) | ✓ | ✗ (<0.1%) | ✓ | ✓ |
| NP-40 (≤1%) | ✓ | ✗ (<0.1%) | ✓ | ✓ |
| DTT (≤1 mM) | ✗ | ✓ | ✗ | ✓ |
| β-ME (≤1 mM) | ✗ | ✓ | ✗ | ✓ |
| EDTA (≤10 mM) | ✓ | ✓ | ✗ | ✓ |
| Tris (≤250 mM) | ✓ | ✓ | ✓ | ✓ |
| Urea (≤2 M) | ✓ | ✓ | ✓ | ✓ |
| GSH (≤1 mM) | ✗ | ✓ | ✗ | ✓ |
| Glucose (≤10 mM) | ✓ | ✓ | ✓ | ✓ |
| Glycerol (≤10%) | ✓ | ✓ | ✓ | ✓ |
| KCl/NaCl (≤1 M) | ✓ | ✓ | ✓ | ✓ |
| NaN₃ (≤0.1%) | ✓ | ✓ | ✓ | ✓ |

✓ = Compatible at indicated concentration; ✗ = Incompatible at this concentration.

## 6. Related Products & Cross-References

- [▶ Enzyme Activity Assay Kits](enzyme-activity.md)
- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)
- [▶ Related Protocol: Western Blot Protocol](../protocols/western-blot.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
