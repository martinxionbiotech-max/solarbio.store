---
title: "Technical Specification: Plant Biology Assay Kits"
description: "Technical specifications for Solarbio plant biology assay kits — chlorophyll, carotenoids, proline, MDA, nitrate reductase, H₂O₂, plant hormones (ABA, IAA, GA₃), soluble sugars, starch, and total phenolic/flavonoid content with validated protocols and reference ranges."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Plant Biology Assay Kits",
 "description": "Full specifications for Solarbio plant biology assay kits covering chlorophyll, carotenoids, proline, MDA, nitrate/nitrite, H₂O₂, plant hormones, carbohydrates, and phenolic content analysis.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Plant Biology Assay"}
}
</script>

# Technical Specification: Plant Biology Assay Kits

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Product Range

| Assay | SKU | Detection Method | Wavelength | Detection Limit | Linear Range | Sample Types |
|---|---|---|---|---|---|---|
| Chlorophyll Content Assay | BC0990 | Ethanol extraction + spectrophotometry | 665/649 nm | 0.5 mg/L | 1–50 mg/L chl a+b | Leaf, algae, chloroplast |
| Carotenoid Assay | BC0995 | Spectrophotometric (ethanol extract) | 470 nm | 0.2 mg/L | 0.5–20 mg/L | Leaf, fruit, flower |
| Proline Content Assay | BC0290 | Ninhydrin colorimetric | 520 nm | 1 μg/g FW | 2–50 μg/g FW | Leaf, root, seed |
| MDA (Plant) Assay Kit | BC0020-Plant | TBA reaction (plant-optimized) | 532/600 nm | 0.5 nmol/mL | 1–50 nmol/mL | Leaf, root, fruit |
| Nitrate Reductase Assay | BC0080 | Sulfanilamide-NED (nitrite detection) | 540 nm | 0.1 μmol NO₂⁻/h/g FW | 0.5–20 μmol NO₂⁻/h/g FW | Leaf, root |
| H₂O₂ Assay (Plant) | BC0060-Plant | Titanium sulfate | 415 nm | 1 μmol/g FW | 2–100 μmol/g FW | Leaf, root |
| Soluble Sugar Assay | BC5450 | Anthrone-sulfuric acid | 620 nm | 10 μg/g FW | 20–500 μg/g FW | Leaf, root, fruit |
| Starch Content Assay | BC0700 | Anthrone (amylase digestion) | 620 nm | 50 μg/g FW | 100–2000 μg/g FW | Leaf, seed, tuber |
| Total Phenolic Assay | BC1065 | Folin-Ciocalteu (GAE equiv) | 760 nm | 5 μg GAE/g | 10–200 μg GAE/g | Leaf, fruit, bark |
| Flavonoid Assay | BC1070 | AlCl₃ colorimetric (rutin equiv) | 510 nm | 10 μg RE/g | 20–500 μg RE/g | Leaf, flower, herb |
| Abscisic Acid (ABA) Assay | BC1188 | ELISA (competitive) | 450 nm | 1 ng/mL | 2–100 ng/mL | Leaf, xylem sap |
| Indole-3-Acetic Acid (IAA) Assay | BC1193 | ELISA (competitive) | 450 nm | 0.5 ng/mL | 1–50 ng/mL | Leaf, root, stem |
| Gibberellic Acid (GA₃) Assay | BC1197 | ELISA (competitive) | 450 nm | 1 ng/mL | 2–50 ng/mL | Leaf, seed |

## 2. Detailed Assay Principles

### 2.1 Chlorophyll — Spectrophotometric Method (BC0990)

Chlorophylls a and b are extracted in 95% ethanol and quantified spectrophotometrically using the specific absorption coefficients in ethanol.

```
Chl a (in 95% ethanol): λ_max = 665 nm (ε = 83.9 L·g⁻¹·cm⁻¹)
Chl b (in 95% ethanol): λ_max = 649 nm (ε = 48.5 L·g⁻¹·cm⁻¹)
Carotenoids: λ = 470 nm (combined signal)
```

**Calculations** (Lichtenthaler 1987, ethanol-based):

```
Chl a (mg/L) = 13.95 × A₆₆₅ − 6.88 × A₆₄₉
Chl b (mg/L) = 24.96 × A₆₄₉ − 7.32 × A₆₆₅
Chl a + b (mg/L) = 6.63 × A₆₆₅ + 18.08 × A₆₄₉
Carotenoids (mg/L) = (1000 × A₄₇₀ − 2.05 × Chl a − 114.8 × Chl b) / 245
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint spectrophotometric |
| Wavelengths | 665, 649, 470 nm |
| Limit of detection | 0.5 mg/L (each pigment) |
| Linear range | 1–50 mg/L |
| Intra-assay CV | <5% (n=20, 10 mg/L) |
| Inter-assay CV | <8% (n=6 lots) |
| Extraction solvent | 95% ethanol (v/v) |
| Extraction time | 24 h at 4°C (dark) |
| Minimum sample | 0.05 g fresh leaf |
| Solvent volume | 1 mL / 0.1 g tissue |

**Protocol**:

| Step | Detail |
|---|---|
| 1 | Weigh 0.1 g fresh leaf (avoid major veins) |
| 2 | Add 1 mL 95% ethanol, grind in mortar or bead mill |
| 3 | Transfer to tube, incubate in dark at 4°C for 24 h (or 60°C for 30 min for rapid extraction) |
| 4 | Centrifuge at 5000×g, 5 min |   
| 5 | Read supernatant at 665, 649, 470 nm against ethanol blank |
| 6 | Calculate using equations above |


**Reference Values**:


| Plant Species | Chl a (mg/g FW) | Chl b (mg/g FW) | Chl a/b ratio |
|---|---|---|---|
| Arabidopsis (rosette) | 0.8–1.5 | 0.3–0.6 | 2.5–3.5 |
| Rice (flag leaf) | 2.0–4.0 | 0.6–1.2 | 3.0–3.5 |
| Maize (leaf) | 1.5–3.0 | 0.5–0.9 | 2.8–3.2 |
| Spinach (mature leaf) | 1.0–2.0 | 0.4–0.8 | 2.2–3.0 |
| Wheat (flag leaf) | 2.0–3.5 | 0.5–1.0 | 3.0–4.0 |
| Soybean (trifoliate) | 1.5–3.0 | 0.5–0.8 | 2.8–3.5 |

**Stress-Induced Changes**:
- Drought: Chl ↓ 20–50%, Chl a/b ratio increases
- Salt stress: Chl ↓ 30–60%, Chl a/b ratio may increase or decrease
- Nitrogen deficiency: Chl ↓ primarily, Chl a/b ratio increases
- Light stress: Chl a/b ratio decreases (increased antenna size)

**Critical Note**: Chlorophyll is photolabile. Perform all extraction steps in dim light or wrap tubes in aluminum foil. Do not use methanol or acetone without recalibrating equations (different absorption coefficients).

### 2.2 Carotenoid Assay (BC0995)

Carotenoids, including β-carotene and xanthophylls, are extracted together with chlorophyll and measured at 470 nm.

| Parameter | Specification |
|---|---|
| Wavelength | 470 nm |
| Limit of detection | 0.2 mg/L |
| Linear range | 0.5–20 mg/L |
| Reference range (leaf) | 0.2–0.8 mg/g FW |

**Calculation** (correcting for chlorophyll overlap at 470 nm):

```
Carotenoids (mg/L) = (1000 × A₄₇₀ − 2.05 × Chl a − 114.8 × Chl b) / 245
```

### 2.3 Proline — Ninhydrin Colorimetric Method (BC0290)

Proline accumulates in plants under osmotic stress (drought, salinity, cold) as a compatible osmolyte. The assay uses the specific reaction of proline with ninhydrin in acidic conditions to form a red chromophore.

```
Proline + Ninhydrin ──[Glacial acetic acid, 100°C, 30 min]──→
    Proline-ninhydrin complex (red, λ_max = 520 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 520 nm |
| Limit of detection | 1 μg/g FW |
| Linear range | 2–50 μg/g FW |
| Intra-assay CV | <6% |
| Reaction temperature | 100°C (boiling water bath) |
| Reaction time | 30 min |
| Extraction | 3% sulfosalicylic acid (1 mL per 0.1 g tissue) |
| Solvent for extraction | Toluene (separates proline-ninhydrin complex) |

**Protocol**:

| Step | Detail |
|---|---|
| 1 | Homogenize 0.1 g tissue in 1 mL 3% sulfosalicylic acid |
| 2 | Centrifuge at 5000×g, 10 min |
| 3 | Collect 200 μL supernatant, add 200 μL ninhydrin reagent + 200 μL glacial acetic acid |
| 4 | Boil at 100°C for 30 min (sealed tube) |
| 5 | Cool on ice, add 1 mL toluene, vortex 15 s |
| 6 | Allow phase separation (15 min), read upper toluene phase at 520 nm |


**Reference Values**:


| Species | Control (μg/g FW) | Stress (μg/g FW) | Stress Condition |
|---|---|---|---|
| Arabidopsis | 5–15 | 30–80 | 200 mM NaCl, 48 h |
| Rice | 10–30 | 50–200 | Drought (15% PEG), 5 d |
| Wheat | 10–25 | 40–150 | 150 mM NaCl, 24 h |
| Maize | 5–20 | 30–120 | Drought, 7 d |

### 2.4 MDA (Plant) — TBA Method (BC0020-Plant)

The plant-optimized MDA kit accounts for plant-specific interferences (phenolics, sugars) that are less abundant in animal tissues.

```
MDA + 2 × Thiobarbituric Acid ──[95°C, pH 3.5, 40 min]──→
    MDA-TBA₂ adduct (red, 532 nm; 600 nm correction)
```

| Parameter | Specification |
|---|---|
| Wavelength | 532 nm (600 nm correction) |
| Detection limit | 0.5 nmol/mL |
| Linear range | 1–50 nmol/mL |
| Intra-assay CV | <7% |
| Extraction buffer | 10% TCA (trichloroacetic acid) |
| Sample amount | 0.1 g tissue in 1 mL TCA |


**Reference Values**:

| Plant | Control (nmol/g FW) | Stress (nmol/g FW) |
|---|---|---|
| Rice leaf | 5–15 | 15–50 (salt stress) |
| Arabidopsis | 3–10 | 10–30 (drought) |
| Maize leaf | 5–20 | 20–60 (chilling) |

### 2.5 Nitrate Reductase (NR) Assay (BC0080)

Nitrate reductase catalyzes the first and rate-limiting step of nitrate assimilation, reducing NO₃⁻ to NO₂⁻.

```
NO₃⁻ + NADH ──[NR, 30°C, dark, 30 min]──→ NO₂⁻ + NAD⁺ + H₂O
NO₂⁻ + Sulfanilamide + NED ──[Acidic]──→ Azo dye (pink, 540 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | In vitro activity |
| Wavelength | 540 nm |
| Detection limit | 0.1 μmol NO₂⁻/h/g FW |
| Linear range | 0.5–20 μmol NO₂⁻/h/g FW |
| Intra-assay CV | <8% |
| Incubation | 30°C, 30 min, dark |
| Substrates | KNO₃ (50 mM) + NADH (0.2 mM) |

**Critical Note**: NR is highly labile. Harvest tissue in mid-morning (light phase), process immediately at 4°C, and complete the assay within 2 h. The assay must be performed in the dark (light inactivates NR).


**Reference Values**:

| Species | NR Activity (μmol NO₂⁻/h/g FW) |
|---|---|
| Maize leaf (light) | 5–15 |
| Rice leaf | 3–10 |
| Arabidopsis | 2–8 |
| Spinach | 4–12 |

### 2.6 H₂O₂ Assay (BC0060-Plant)

```
H₂O₂ + Ti⁴⁺ + 2 H₂O → H₂TiO₄ (yellow peroxotitanate complex, 415 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 415 nm |
| Detection limit | 1 μmol/g FW |
| Linear range | 2–100 μmol/g FW |
| Extraction | Cold acetone or TCA |
| Reaction time | 10 min at RT |


**Reference Values**:
 Leaf H₂O₂ is typically 5–20 μmol/g FW under normal conditions and can increase to 30–100 μmol/g FW under stress.

### 2.7 Soluble Sugar — Anthrone Method (BC5450)

```
Carbohydrate (furfurol derivative from conc. H₂SO₄) + Anthrone → Blue-green complex (620 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 620 nm |
| Detection limit | 10 μg/g FW |
| Linear range | 20–500 μg/g FW (glucose equivalents) |
| Extraction | 80% ethanol, 80°C, 30 min |
| Standard | Glucose (provided in kit) |


**Reference Values**:


| Species | Control (% DW) | Stress |
|---|---|---|
| Arabidopsis leaf | 1–3% | Up to 8% (drought) |
| Rice leaf | 3–8% | 5–15% (salt) |
| Maize leaf | 2–5% | 4–10% (cold) |

### 2.8 Starch Content (BC0700)

Starch is first digested to glucose by amylase/amyloglucosidase, then glucose is measured by the anthrone method.

```
Starch ──[Amylase, 60°C, 30 min]──→ Dextrins
Dextrins ──[Amyloglucosidase, 60°C, 30 min]──→ Glucose
Glucose ──[Anthrone/H₂SO₄]──→ Blue-green (620 nm)
```

| Parameter | Specification |
|---|---|
| Detection limit | 50 μg/g FW |
| Linear range | 100–2000 μg/g FW (glucose equiv) |

### 2.9 Total Phenolics — Folin-Ciocalteu (BC1065)

```
Phenolic OH + Folin-Ciocalteu reagent (Mo⁶⁺/W⁶⁺)
    ──[Na₂CO₃, alkalin]──→ Reduced Mo⁵⁺/W⁵⁺ (blue, 760 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 760 nm |
| Detection limit | 5 μg GAE/g |
| Linear range | 10–200 μg GAE/g |
| Standard | Gallic acid (GAE) |
| Reaction time | 30 min at RT (dark) |


**Reference Values**:


| Plant Material | Total Phenolics (mg GAE/g DW) |
|---|---|
| Green tea leaves | 50–150 |
| Grape (skin) | 20–50 |
| Blueberry | 15–40 |
| Spinach leaf | 5–15 |
| Arabidopsis leaf | 3–10 |

### 2.10 Flavonoid Assay (BC1070)

```
Flavonoid + AlCl₃ ──[Ethanol, RT]──→ Flavonoid-Al³⁺ complex (yellow, 510 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 510 nm |
| Detection limit | 10 μg RE/g |
| Linear range | 20–500 μg RE/g |
| Standard | Rutin (RE) |
| Reaction time | 10 min at RT |

### 2.11 Plant Hormone ELISAs (ABA, IAA, GA₃)

These competitive ELISA kits use a HRP-conjugated hormone tracer and TMB substrate.

| Parameter | ABA (BC1188) | IAA (BC1193) | GA₃ (BC1197) |
|---|---|---|---|
| Assay type | Competitive ELISA | Competitive ELISA | Competitive ELISA |
| Detection limit | 1 ng/mL | 0.5 ng/mL | 1 ng/mL |
| Linear range | 2–100 ng/mL | 1–50 ng/mL | 2–50 ng/mL |
| Intra-assay CV | <8% | <9% | <9% |
| Inter-assay CV | <15% | <15% | <15% |
| Recovery (spiked tissue extract) | 85–115% | 80–120% | 85–115% |
| Cross-reactivity | ABA >95% | IAA >95% | GA₃ >90% |
| Sample type | Leaf (0.5 g), xylem sap (100 μL) | Leaf (0.5 g), root (0.5 g) | Leaf (0.3 g), seed (0.1 g) |
| Extraction | 80% MeOH + BHT | 80% MeOH | 80% MeOH |
| Incubation time | 2 h + 15 min TMB | 2 h + 15 min TMB | 2 h + 15 min TMB |

**Sample Extraction for Hormones**: Plant tissue (0.3–0.5 g) is extracted in 80% methanol containing 10 mg/L BHT (butylated hydroxytoluene) at 4°C for 12–16 h. The extract is centrifuged, dried under N₂, and reconstituted in assay buffer. Further purification by C18 SPE cartridge is recommended for tissues with high pigment or phenolic content.

## 3. Sample Preparation Guide

| Assay | Recommended Tissue Amount | Extraction Solvent | Special Notes |
|---|---|---|---|
| Chlorophyll | 0.1 g leaf | 95% ethanol, 24 h, 4°C, dark | Avoid major veins; process in dim light |
| Carotenoids | 0.1 g leaf | Same as chlorophyll (read at 470 nm) | Co-extracted with chlorophyll |
| Proline | 0.1 g leaf/root | 3% sulfosalicylic acid | Use fresh tissue; avoid drying |
| MDA | 0.1 g leaf | 10% TCA (plant-optimized) | Do not use PBS or sucrose-containing buffers |
| NR | 0.2 g leaf | In situ in assay buffer (no extraction) | Must perform in dark; process within 2 h |
| H₂O₂ | 0.1 g leaf | Cold acetone or 5% TCA | Extract quickly; H₂O₂ degrades rapidly |
| Soluble Sugar | 0.1 g leaf (DW) | 80% ethanol, 80°C | Use oven-dried (80°C, 48 h) or fresh tissue |
| Starch | Residue from sugar extraction | DMSO + heat | Use pellet from sugar extraction |
| Total Phenolics | 0.1 g DW | 70% methanol, sonicate | Protect from light; use dark glass vials |
| ABA | 0.5 g leaf | 80% MeOH, 4°C, 12 h | C18 SPE recommended for clean-up |

## 4. Troubleshooting Guide

| Problem | Likely Cause | Solution |
|---|---|---|
| Chlorophyll A₆₆₅ exceeds 2.0 | Tissue sample too large | Reduce sample to 0.05 g; dilute extract 1:2 |
| Proline blank is colored | Ninhydrin reagent degraded or overheated | Prepare fresh ninhydrin; reduce heating time |
| MDA absorbance decrease after extraction | TBA chromophore instability | Read within 30 min after extraction |
| NR activity zero | Tissue harvested in dark phase | Harvest 2–4 h into light cycle |
| H₂O₂ blank high | Titanium reagent hydrolyzed | Prepare fresh H₂SO₄/Ti solution weekly |
| Anthrone blank is green | Sulfuric acid concentration incorrect | Ensure H₂SO₄ is >95% and cooled before use |
| Hormone binding below B₀ | Extract contains organic solvents | Evaporate MeOH completely and reconstitute in buffer |

## 5. Stress Marker Panel Recommendations

| Stress Type | Primary Markers | Secondary Markers | Expected Change |
|---|---|---|---|
| Drought | Proline (⬆), MDA (⬆), Soluble Sugars (⬆) | Chlorophyll (⬇), NR (⬇), ABA (⬆) | Proline 3–10×; MDA 2–3×; Sugars 1.5–3× |
| Salinity | Proline (⬆), MDA (⬆), H₂O₂ (⬆) | Chlorophyll (⬇), Carotenoids (variable) | Proline 5–20×; H₂O₂ 2–5× |
| Cold | Proline (⬆), Soluble Sugars (⬆), MDA (⬆) | Chlorophyll (⬇), Phenolics (⬆) | Sugars 2–4×; Proline 2–5× |
| Heat | MDA (⬆), H₂O₂ (⬆), Proline (⬆) | Chlorophyll (⬇), NR (⬇) | MDA 2–4×; H₂O₂ 2–3× |
| Heavy metal (Cd) | MDA (⬆), H₂O₂ (⬆), GSH (⬆) | Chlorophyll (⬇), Proline (⬆) | MDA 2–5×; GSH 1.5–3× |
| UV-B | Phenolics (⬆), Flavonoids (⬆), MDA (⬆) | Chlorophyll (⬇), Carotenoids (⬆) | Phenolics 2–5×; UV-absorbing compounds |
| Pathogen defense | Phenolics (⬆), H₂O₂ (⬆), ABA (⬆) | Flavonoids (⬆), Salicylic acid | H₂O₂ burst 2–10×; phenolics 2–3× |

## 6. Related Products & Cross-References

- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Metabolism Assay Kits](metabolism.md)
- [▶ Enzyme Activity Assay Kits](enzyme-activity.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
