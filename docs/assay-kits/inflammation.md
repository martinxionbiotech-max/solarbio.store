---
title: "Technical Specification: Inflammation & Oxidative Stress Assays"
description: "Technical specifications for Solarbio inflammation marker assay kits — myeloperoxidase (MPO), nitric oxide (NO), inducible nitric oxide synthase (iNOS), xanthine oxidase (XOD), lipase, and eosinophil peroxidase (EPO) with validated performance data, sample preparation protocols, and interference charts."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Inflammation & Oxidative Stress Assays",
 "description": "Full specifications for Solarbio inflammation marker assay kits — MPO, NO, iNOS, XOD, lipase, and EPO with detection limits, linear ranges, CV data, and detailed protocol information.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Inflammation Assay"}
}
</script>

# Technical Specification: Inflammation & Oxidative Stress Assays

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Product Range

| Assay | SKU | Detection | Wavelength | Detection Limit | Linear Range | Sample Types |
|---|---|---|---|---|---|---|
| Myeloperoxidase (MPO) | BC1305 | o-Dianisidine colorimetric (kinetic) | 460 nm | 0.1 U/L | 0.2–30 U/L | Tissue, cells, neutrophil lysate, BALF |
| Nitric Oxide (NO/NOS) | BC1470 | Griess reagent (nitrate reductase + sulfanilamide) | 540 nm | 0.5 μmol/L | 1–100 μmol/L | Serum, tissue, cell culture supernatant |
| Inducible NOS (iNOS) | BC1670 | NOS activity assay (L-arginine → NO) | 540 nm | 25 pmol/min/mg | 25–500 pmol/min/mg | Tissue lysate, macrophages |
| Xanthine Oxidase (XOD) | BC1790 | Xanthine → uric acid (direct UV) | 290 nm | 0.2 U/L | 0.5–30 U/L | Serum, tissue |
| Lipase | BC2450 | Triglyceride hydrolysis (1,2-diglyceride → glycerol) | 546 nm | 2 U/L | 5–200 U/L | Serum, plasma |
| Eosinophil Peroxidase (EPO) | BC1310 | o-Phenylenediamine/H₂O₂ | 492 nm | 0.1 mU/mL | 0.2–20 mU/mL | Tissue, cell lysate, BALF |

## 2. Detailed Assay Principles

### 2.1 Myeloperoxidase (MPO)

MPO, a heme-containing enzyme expressed primarily in azurophilic granules of neutrophils, catalyzes the production of hypochlorous acid from H₂O₂ and chloride ions. MPO activity serves as a quantitative marker of neutrophil infiltration in inflamed tissues.

```
H₂O₂ + Cl⁻ ──[MPO]──→ HOCl + H₂O
HOCl + o-dianisidine (reduced, colorless) → o-dianisidine (oxidized, brown, 460 nm)
```

**Unit Definition**: 1 U of MPO = amount decomposing 1 μmol H₂O₂ per minute at 37°C.

**Kinetic Read Parameters**:

| Parameter | Specification |
|---|---|
| Assay type | Kinetic colorimetric (rate measurement) |
| Wavelength | 460 nm |
| Readings | 3–5 readings at 30 s intervals |
| Incubation temperature | 37°C |
| Substrate | o-Dianisidine dihydrochloride (0.167 mg/mL final) |
| H₂O₂ concentration | 0.5 mmol/L final |
| Sample volume | 50–100 μL (tissue homogenate) |
| Buffer | 50 mM PBS, pH 6.0 (phosphate-based, optimal for MPO) |

**Performance Data**:

| Parameter | Value |
|---|---|
| Limit of detection | 0.1 U/L |
| Lower limit of quantification | 0.2 U/L |
| Linear range | 0.2–30 U/L |
| Intra-assay CV | <5% (n=20, 10 U/L) |
| Inter-assay CV | <10% (n=8 lots) |
| Recovery (spiked neutrophil lysate) | 92–108% |
| Reaction time | 3 min kinetic |

**Sample Preparation for MPO**:

| Sample Type | Buffer | Homogenization | Notes |
|---|---|---|---|
| Tissue (muscle, lung, gut) | 50 mM PBS, pH 6.0 + 0.5% HTAB | 10% w/v homogenate, freeze-thaw 3× | HTAB solubilizes membrane-bound MPO |
| Bronchoalveolar lavage (BALF) | Concentrate 10× by centrifugation | Resuspend pellet in 300 μL HTAB buffer | Requires multiple freeze-thaw cycles |
| Neutrophil lysate | 50 mM PBS, pH 6.0 + 0.5% HTAB | 1×10⁶ cells/0.5 mL, sonicate 10 s | Keep on ice |

### 2.2 Nitric Oxide (NO) — Griess Method

Nitric oxide produced by NOS isoforms is rapidly oxidized to nitrite (NO₂⁻) and nitrate (NO₃⁻). The kit reduces NO₃⁻ to NO₂⁻ using nitrate reductase, then detects total NO₂⁻ via the Griess diazotization reaction.

```
NO₃⁻ ──[Nitrate Reductase + NADPH, 37°C, 30 min]──→ NO₂⁻
NO₂⁻ + Sulfanilamide (acidic) → Diazonium salt
Diazonium salt + N-(1-naphthyl)ethylenediamine (NED) → Azo dye (λ max = 540 nm)
```

**Reaction Scheme in 96-Well Plate**:

| Step | Reagent | Volume | Incubation |
|---|---|---|---|
| 1 | Sample/supernatant | 100 μL | — |
| 2 | Nitrate reductase + NADPH | 50 μL | 37°C, 30 min |
| 3 | Griess Reagent I (sulfanilamide) | 50 μL | RT, 10 min |
| 4 | Griess Reagent II (NED) | 50 μL | RT, 10 min |
| 5 | Read at 540 nm | — | — |

**Performance Data**:

| Parameter | Specification |
|---|---|
| Limit of detection | 0.5 μmol/L |
| Lower limit of quantification | 1.0 μmol/L |
| Linear range | 1–100 μmol/L NaNO₂ |
| Intra-assay CV | <6% (n=20, 25 μmol/L) |
| Inter-assay CV | <12% (n=8 lots) |
| Recovery rate | 90–110% |
| Total assay time | ~50 min |
| Capacity | 100 assays |
| Standard | 100 μmol/L NaNO₂ solution (provided) |

**Critical Protocol Notes**:
- Serum and plasma must be deproteinized before assay using the included ZnSO₄/NaOH precipitation method.
- NADPH in the reaction interferes with the Griess reagent; the kit includes a pyruvate/pyruvate oxidase step to remove residual NADPH.
- Culture media containing phenol red produce a high background — use phenol red-free media for NO quantification.

**Reference NO Values**:

| Sample Type | Baseline (μmol/L) | Stimulated (e.g., LPS) |
|---|---|---|
| Human serum | 10–40 | — |
| Mouse serum | 20–60 | — |
| RAW 264.7 supernatant (untreated) | <5 | 20–80 (LPS 1 μg/mL, 24 h) |
| Rat serum after LPS (5 mg/kg, 6 h) | 15–30 | 50–120 |

### 2.3 Inducible NOS (iNOS) Activity Assay

iNOS catalyzes the conversion of L-arginine to L-citrulline and NO in a NADPH-dependent reaction. The kit quantifies NO production as a surrogate for iNOS activity.

```
L-Arginine + O₂ + NADPH ──[iNOS]──→ L-Citrulline + NO + NADP⁺
NO + O₂ → NO₂⁻ + NO₃⁻  ──[Griess detection]──→ Azo dye (540 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint, NO detection |
| Substrate | L-Arginine (100 μmol/L final) |
| Cofactors | NADPH (1 mM), BH₄ (10 μmol/L), FAD (5 μmol/L), FMN (5 μmol/L) |
| Ca²⁺ requirement | None (Ca²⁺-independent — distinguishes iNOS from eNOS/nNOS) |
| Detection limit | 25 pmol/min/mg protein |
| Linear range | 25–500 pmol/min/mg |
| Intra-assay CV | <10% |
| Sample type | Tissue lysate (lung, liver, spleen), macrophage cell lysate |
| Assay time | 60 min at 37°C |

**Critical Notes**:
- For iNOS-specific measurement, protein lysates should be prepared in Ca²⁺-free buffer containing 1 mM EGTA.
- The assay measures total NOS activity in Ca²⁺-free conditions; any remaining activity is attributed to iNOS. For confirmation, use the iNOS-specific inhibitor 1400W (1 μmol/L included).
- Macrophage cells (RAW 264.7, J774) stimulated with LPS (1 μg/mL) + IFN-γ (10 ng/mL) for 12–24 h produce high levels of iNOS.

### 2.4 Xanthine Oxidase (XOD)

Xanthine oxidase catalyzes the oxidation of hypoxanthine to xanthine and xanthine to uric acid, generating O₂⁻ as a byproduct. XOD is a key source of reactive oxygen species in ischemia-reperfusion injury.

```
Xanthine + H₂O + O₂ ──[XOD]──→ Uric acid + O₂⁻ + H₂O₂
(Direct UV detection of uric acid at 290 nm, ↑A)
```

| Parameter | Specification |
|---|---|
| Assay type | Direct kinetic (UV) |
| Wavelength | 290 nm |
| Limit of detection | 0.2 U/L |
| Linear range | 0.5–30 U/L |
| Intra-assay CV | <7% |
| Substrate | Xanthine (0.5 mM final) |
| Reaction monitoring | 5 min at 37°C (every 30 s) |
| Unit definition | 1 U = 1 μmol uric acid formed per min |
| Sample types | Serum, tissue homogenate |


**Reference Values**:

| Species | Serum XOD (U/L) |
|---|---|
| Human | 3–15 |
| Mouse | 5–20 |
| Rat | 4–18 |

### 2.5 Lipase Assay

Lipase hydrolyzes triglycerides into glycerol and free fatty acids. The assay is used for pancreatitis diagnosis and inflammation monitoring in digestive tissues.

```
Triglyceride + H₂O ──[Lipase]──→ 1,2-Diglyceride + Fatty acid
1,2-Diglyceride + H₂O ──[Colipase]──→ 2-Monoglyceride + Fatty acid
Glycerol + 2-ATP ──[GK]──→ G-3-P + 2-ADP
G-3-P + O₂ ──[GPO]──→ Dihydroxyacetone phosphate + H₂O₂
H₂O₂ + Chromogen ──[POD]──→ Quinoneimine dye (546 nm)
```

| Parameter | Specification |
|---|---|
| Detection limit | 2 U/L |
| Linear range | 5–200 U/L |
| Intra-assay CV | <4% |
| Substrate | 1,2-Diglyceride (provided emulsion) |

## 3. Tissue Extraction and Sample Processing

### 3.1 MPO Extraction from Inflamed Tissues

| Tissue | Homogenization Buffer | Special Steps | Expected Activity (U/g tissue) |
|---|---|---|---|
| Lung (mouse) | 50 mM PBS + 0.5% HTAB, pH 6.0 | Perfuse with PBS before harvest | 0.5–5 (normal); 10–40 (LPS-induced) |
| Colon (mouse) | Same | Remove fecal matter, wash in PBS | 0.2–2 (normal); 5–25 (DSS-induced colitis) |
| Heart (mouse) | Same | Avoid calcium-containing buffers | 0.1–1 (normal); 2–10 (ischemia-reperfusion) |
| Skin (mouse) | Same; increase HTAB to 1% | Remove subcutaneous fat | 0.1–0.5 (normal); 2–20 (contact dermatitis) |

### 3.2 NO Extraction from Culture Supernatants

| Cell Type | Stimulation | Supernatant Collection | Expected NO (μmol/L) |
|---|---|---|---|
| RAW 264.7 | LPS 1 μg/mL, 24 h | Centrifuge 300×g, 10 min | 30–60 |
| BV-2 microglia | LPS 100 ng/mL, 24 h | Centrifuge, avoid harvesting debris | 15–40 |
| Primary macrophages | LPS+IFN-γ, 24 h | Filter through 0.22 μm if visible particles | 20–50 |

## 4. Interference Table

| Substance | MPO (o-Dianisidine) | NO (Griess) | iNOS (Activity) | XOD (UV) |
|---|---|---|---|---|
| Ascorbic acid (>0.1 mM) | None | Moderate | None | None |
| Hemoglobin (>0.5 mg/mL) | Strong | Strong | Moderate | None |
| DTT (>1 mM) | Strong reduction | None | None | None |
| NADPH (>0.5 mM) | None | Strong (if not removed) | — | Interference (290 nm) |
| EDTA (>5 mM) | None | None | None | None |
| BSA (>5%) | Moderate (quenching) | None | None | None |
| Phenol red (culture media) | None | Strong | None | None |
| DMSO (>2%) | None | None | Moderate | None |

## 5. Performance Validation Data

### 5.1 MPO Standard Curve

| MPO Standard (U/L) | ΔA₄₆₀/min |
|---|---|
| 0 | 0.000 |
| 0.2 | 0.008 |
| 1 | 0.040 |
| 5 | 0.198 |
| 10 | 0.395 |
| 20 | 0.780 |
| 30 | 1.150 |

R² > 0.995 in the full range.

### 5.2 NO Standard Curve (NaNO₂)

| NaNO₂ (μmol/L) | A₅₄₀ |
|---|---|
| 0 | 0.000 |
| 1 | 0.022 |
| 5 | 0.105 |
| 10 | 0.208 |
| 25 | 0.510 |
| 50 | 1.005 |
| 100 | 1.980 |

R² > 0.999; linear across full range.

## 6. Related Products & Cross-References

- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Hepatotoxicity Assay Kits](hepatotoxicity.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)
- [▶ Related Protocol: ELISA Protocol](../protocols/elisa-protocol.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
