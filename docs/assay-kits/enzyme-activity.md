---
title: "Technical Specification: Enzyme Activity Assay Kits"
description: "Technical specifications for Solarbio enzyme activity assay kits covering 200+ validated assays — NAD(P)H-coupled kinetics, chromogenic endpoint, fluorometric, turbidimetric, and coupled enzymatic detection for dehydrogenases, kinases, peroxidases, hydrolases, and transferases."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Enzyme Activity Assay Kits",
 "description": "Full specifications for Solarbio enzyme activity assay kits — detection principles, selection guide, reaction equations, performance parameters, and optimization protocols for 200+ validated assays.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Enzyme Activity Assay"}
}
</script>

# Technical Specification: Enzyme Activity Assay Kits

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Common Assay Types and Detection Principles

| Detection Principle | Mechanism | Example Assays | Wavelength/Detection | Typical CV |
|---|---|---|---|---|
| **NAD(P)H-coupled kinetics** | NAD(P)H has A₃₄₀; its consumption (↓A) or production (↑A) tracks enzyme activity | Dehydrogenases (LDH, SDH, G6PD), kinases (HK, PK, PFK), reductases (GR, DHFR) | 340 nm (UV) | <8% |
| **Chromogen formation (endpoint)** | Enzyme product reacts to form a colored dye measurable at visible wavelength | Peroxidases (GPx), oxidases (XO), esterases (AChE, lipase), phosphatases (ALP, ACP) | 400–600 nm | <5% |
| **Chromogen formation (kinetic)** | Continuous monitoring of chromogen production rate | MPO (460 nm), trypsin (405 nm), ACE (340 nm) | 400–600 nm | <5% |
| **Fluorescence** | Fluorescent product (Ex/Em specific), 10–100× more sensitive than colorimetric | Proteases (Zymogen), caspases, cathepsins, MMPs, phosphatases | Ex/Em varies | <10% |
| **Turbidimetric** | Decrease in turbidity (↓A) as substrate is hydrolyzed | Lysozyme (450 nm, Micrococcus lysate substrate), amylase (660 nm, starch | 450–660 nm | <8% |
| **Coupled enzymatic** | Primary reaction produces a substrate for a secondary indicator enzyme (NAD(P)H or chromogen) | PK (LDH coupling), HK (G6PDH coupling), PEPCK (PK+LDH) | 340 nm (most common) | <10% |
| **Chemiluminescent** | Light emission via luciferase/luciferin system (ATP quantification) | ATP content (firefly luciferase), luciferase reporter | Luminometer | <15% |
| **Colorimetric (phosphate detection)** | Free phosphate reacts with molybdate to form molybdenum blue | ATPase, phosphatase, G6Pase, 5′-NT, adenylate kinase | 660 nm | <6% |

## 2. Kit Selection Guide

| Research Area | Recommended Assays | Relevant Models |
|---|---|---|
| Hepatotoxicity | ALT (BC1550), AST (BC1560), ALP (BC2140), GGT (BC1225), LDH (BC0680), 5′-NT (BC1230) | CCl₄, APAP, ANIT, ethanol |
| Cardiac function | CK (BC1140), LDH (BC0680), AST (BC1560), cTnI (E-EL-0121) | Ischemia-reperfusion, doxorubicin |
| Kidney function | Creatinine (BC4780), BUN (BC1520), NAG (BC0765), β₂-microglobulin | Cisplatin, gentamicin, ischemia |
| Energy metabolism | ATP (BC0300), PK (BC2800), HK (BC0740), PFK (BC1270), LDH (BC0680), SDH (BC0950), PEPCK (BC2170), G6Pase (BC0745) | Diabetes, obesity, exercise physiology |
| Inflammation | MPO (BC1305), NO/NOS (BC1470), iNOS (BC1670), XOD (BC1790), COX-2 (BC2060) | LPS, DSS, carrageenan, air pouch |
| Antioxidant defense | SOD (BC0170–BC0175), CAT (BC0200–BC0205), GPx (BC1190–BC1195), GR (BC1250–BC1255), GST (BC1260–BC1265) | Oxidative stress models, aging |
| Apoptosis | Caspase-3 (BC3830), Caspase-8 (BC3840), Caspase-9 (BC3850), Cytochrome c release | Chemotherapy, UV, Fas activation |
| Glycolysis | HK (BC0740), PFK (BC1270), PK (BC2800), LDH (BC0680), PFKFB3 (BC5240) | Warburg effect, cancer metabolism |
| Gluconeogenesis | PEPCK (BC2170), G6Pase (BC0745), FBPase (BC1110) | Fasting, diabetes |
| Pentose phosphate pathway | G6PD (BC1050), 6PGD (BC1060), transketolase | Oxidative stress, NADPH requirement |
| Proteolysis | Trypsin, chymotrypsin, MMP-2/9, cathepsin B/L, calpain | Cancer invasion, inflammation |
| Lysosomal function | Acid phosphatase (ACP, BC2200), β-hexosaminidase (BC5510), cathepsin D | Lysosomal storage diseases |

## 3. Assay Principle Details by Class

### 3.1 NAD(P)H-Coupled Kinetics

The universal detection principle for NAD(P)H-dependent enzymes relies on the molar extinction coefficient of NADH/NADPH at 340 nm (ε = 6.22 × 10³ M⁻¹cm⁻¹).

**Forward direction (↓A₃₄₀)**: Enzyme produces NAD⁺ or NADP⁺ from NADH or NADPH.
```
Substrate + NAD(P)H + H⁺ ──[Enzyme]──→ Product + NAD(P)⁺
(NADH consumption monitored at 340 nm, absorbance decreases)
```

**Reverse direction (↑A₃₄₀)**: Enzyme produces NADH or NADPH from NAD⁺ or NADP⁺.
```
Substrate + NAD(P)⁺ ──[Enzyme]──→ Product + NAD(P)H + H⁺
(NADPH production monitored at 340 nm, absorbance increases)
```

**Activity Calculation**:

```
Activity (U/L) = (ΔA/min) × V_total × 1000 / (ε × d × V_sample)
```

Where V_total = total reaction volume (mL), V_sample = sample volume (mL), ε = 6.22 mM⁻¹cm⁻¹, d = light path (cm).

**Critical Parameters for Kinetic Assays**:

| Parameter | Optimal Range | Effect of Deviation |
|---|---|---|
| Substrate concentration | 5–10× Kₘ | Below: non-linear kinetics; above: substrate inhibition |
| NAD(P)H concentration | 0.2–0.5 mM | Low: substrate depletion; high: excessive background A₃₄₀ >2.0 |
| Enzyme concentration | ΔA/min 0.01–0.10 | Low: insufficient signal; high: non-linear (substrate/NADH depletion) |
| Temperature | 37°C ± 0.5°C | ±1°C → ~7% change in reaction rate |
| pH | ±0.1 of optimal | Deviations reduce enzyme activity and may denature enzyme |
| Reaction time | Linear phase only (first 3–5 min) | Extended time → substrate depletion, product inhibition |

### 3.2 Chromogenic Endpoint Assays

**General principle**: An enzyme product reacts with a chromogenic reagent to produce a colored compound measured at visible wavelength.

```
Substrate (colorless) ──[Enzyme]──→ Product (reactive)
Product + Chromogen → Colored adduct (λ_max = 405–660 nm)
```

**Key Parameters**: Incubation time must be within the linear the product accumulation window. Stop the reaction at a fixed time with an acidic or alkaline stop solution for reproducible endpoint measurement.

### 3.3 Fluorometric Assays

Fluorometric assays offer 10–100× higher sensitivity than colorimetric methods, appropriate for low-abundance enzymes and small sample volumes.

| Probe Type | Example | Ex/Em (nm) | Sensitivity |
|---|---|---|---|
| AMC (7-amino-4-methylcoumarin) | Caspase-3 (DEVD-AMC), trypsin | 380/460 | Low nM range |
| AFC (7-amino-4-trifluoromethylcoumarin) | Caspase-8 (IETD-AFC) | 400/505 | Low nM range |
| MCA (7-methoxycoumarin-4-acetic acid) | MMP-2/9, ADAM proteases | 328/393 | Low pM range |
| Resorufin-based | Esterases, phosphatases | 571/585 | pM range |
| DCFH-DA | ROS, H₂O₂ | 488/525 | Relative |

### 3.4 Turbidimetric Assays

**Lysozyme example**:

```
Micrococcus lysodeikticus cells (suspension, turbid)
    ──[Lysozyme, 37°C]──→ Cell wall hydrolysis → Decreased turbidity (↓A₄₅₀)
```

**Unit Definition**: 1 U of lysozyme = amount causing a 0.001 decrease in A₄₅₀ per minute at 37°C, pH 6.24.

## 4. Reaction Optimization Guidelines

### 4.1 Determining Linear Reaction Range

For any new enzyme assay, establish the linear range empirically:

| Step | Protocol |
|---|---|
| 1 | Prepare serial dilutions of sample (1:2, 1:5, 1:10, 1:20, 1:50) |
| 2 | Run kinetic assay with readings every 30 s for 10 min |
| 3 | Plot ΔA/min vs. sample concentration (or dilution factor) |
| 4 | Identify the linear region where ΔA/min doubles with 2× concentration |
| 5 | Select the dilution where ΔA/min = 0.02–0.08 (reliable kinetics) |

### 4.2 Substrate Saturation Check

```  
Run assay at 0.5×, 1×, 2×, 5× standard substrate concentration
If activity increases >10% from 1× to 5× → substrate is not saturating
→ Use 5× substrate (or higher; check solubility)
If activity decreases >10% → substrate inhibition → reduce substrate concentration
```

### 4.3 Temperature Optimization

| Temperature | Effect | Recommendation |
|---|---|---|
| 25°C | Lower activity (30–50% of 37°C), stable kinetics | For thermolabile enzymes |
| 30°C | Moderate activity, good stability | General use |
| 37°C | Maximum activity (standard reference) | For mammalian enzymes |
| 42°C | 10–15% higher activity, but risk of denaturation | Short incubations only |

## 5. Sample Preparation Guidelines

### 5.1 Tissue Homogenization for Enzyme Assays

| Enzyme Location | Homogenization Buffer | Extraction Method |
|---|---|---|
| Cytosolic (most metabolic enzymes) | 50 mM Tris-HCl, pH 7.4, 1 mM EDTA, 1 mM DTT | Glass-Teflon homogenizer, 4°C |
| Mitochondrial | 50 mM Tris-HCl, pH 7.4, 250 mM sucrose, 1 mM EDTA | Differential centrifugation |
| Membrane-bound | Buffer + 0.5–1% Triton X-100 or 1% CHAPS | Sonicate 3×10 s on ice |
| Nuclear | 10 mM HEPES, pH 7.9, 10 mM KCl, 0.5% NP-40 | Dounce homogenizer, 15 strokes |

### 5.2 Stabilization of Enzyme Activity

| Condition | Recommended | Notes |
|---|---|---|
| Protease inhibitors | Add protease inhibitor cocktail | Essential for tissue samples |
| Reducing environment | 1 mM DTT or 0.5 mM TCEP | Protect thiol-dependent enzymes |
| Cold temperature | Keep at 0–4°C at all times | Enzymes may lose activity at RT |
| Quick processing | Complete assay within 4 h of homogenization | Freeze aliquots at -80°C for longer storage |
| Freezing | Snap-freeze in liquid N₂, store at -80°C | Avoid slow freezing (ice crystal damage) |

## 6. Troubleshooting Common Issues

| Problem | Likely Cause | Solution |
|---|---|---|
| No activity detected | Sample degraded or not enough enzyme | Check sample storage; increase sample volume 2× |
| Activity decreases during kinetic read | Substrate depletion | Reduce sample volume; increase substrate concentration |
| Non-linear progress curve | Product inhibition or enzyme instability | Reduce incubation time or sample concentration |
| High background absorbance | NADH auto-oxidation or chromogen precipitation | Prepare fresh NADH; filter chromogen solution |
| Absorbance > 2.5 | Sample too concentrated | Dilute sample 2–20 fold |
| No difference from blank | Reagent expired or incorrectly prepared | Check reagent storage; remake fresh |
| Non-reproducible results (high CV) | Pipetting inconsistency or temperature variation | Use calibrated pipettes; pre-warm all reagents |
| Bubbles in microplate | Air trapped during mixing | Tap plate gently; use longer mixing but avoid vortex |

## 7. Representative Performance Specifications

| Assay Class | Typical LOD | Typical Linear Range | Typical Intra-CV | Standard Enzyme Used |
|---|---|---|---|---|
| Dehydrogenase (NAD) | 0.5–2 U/L | 2–500 U/L | <5% | LDH (rabbit muscle) |
| Kinase (ATP-dependent) | 0.2–1 U/L | 0.5–100 U/L | <6% | HK (yeast), PK (rabbit muscle) |
| Peroxidase | 0.1 U/L | 0.5–50 U/L | <4% | HRP |
| Hydrolase (phosphatase) | 1 U/L | 3–500 U/L | <4% | ALP (calf intestine) |
| Transferase | 0.5 U/L | 2–300 U/L | <5% | GGT (bovine kidney) |
| Protease | 1 pM (fluor) | 1 pM–10 nM | <8% | Trypsin (bovine pancreas) |

## 8. General Reaction Mix Template (Most Kinetic Assays)

| Component | Standard Volume | Volume for Low Activity | Notes |
|---|---|---|---|
| Sample | 50 μL | 100 μL | Tissue homogenate or enzyme |
| Substrate mix | 150 μL | 100 μL | Contains substrate + cofactors |
| NAD(P)H (if needed) | 0.2 mM final | — | Add fresh, protect from light |
| Buffer | To 250 μL total | — | pH-optimized for each enzyme |
| Total volume | 250 μL | 250 μL | Adjust proportions for microplate |

## 9. Related Products & Cross-References

- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Inflammation & Injury Assay Kits](inflammation.md)
- [▶ Hepatotoxicity Assay Kits](hepatotoxicity.md)
- [▶ Metabolism Assay Kits](metabolism.md)
- [▶ Protein Quantification Kits](protein-quantification.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
