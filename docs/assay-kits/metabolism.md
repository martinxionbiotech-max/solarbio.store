---
title: "Technical Specification: Metabolism Assay Kits"
description: "Technical specifications for Solarbio metabolism assay kits — ATP content, glucose (GOD-POD), triglyceride (GPO-PAP), total cholesterol (CHOD-PAP), lactic acid, pyruvate kinase, HK, PFK, PEPCK, G6Pase, β-hydroxybutyrate, and free fatty acid quantification kits with reaction equations, performance data, and sample preparation protocols."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Metabolism Assay Kits",
 "description": "Full specifications for Solarbio metabolism assay kits — ATP, glucose, triglycerides, cholesterol, lactic acid, pyruvate kinase, HK, PFK, PEPCK, G6Pase, β-hydroxybutyrate, and free fatty acids with validated performance parameters.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Metabolism Assay"}
}
</script>

# Technical Specification: Metabolism Assay Kits

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Product Range

| Assay | SKU | Detection Method | Wavelength | Detection Limit | Linear Range | Sample Types |
|---|---|---|---|---|---|---|
| ATP Content Assay Kit | BC0300–BC0305 | Hexokinase/G6PDH-coupled (phosphomolybdic acid) | 636 nm | 1 μmol/L | 1–100 μmol/L | Tissue, cells, bacteria, serum |
| Glucose Assay Kit (GOD-POD) | BC2500 | Glucose oxidase-peroxidase (Trinder) | 505 nm | 0.1 mmol/L | 0.5–30 mmol/L | Serum, plasma, culture media |
| Triglyceride Assay Kit | BC0620 | GPO-PAP enzymatic (lipoprotein lipase) | 546 nm | 0.05 mmol/L | 0.1–10 mmol/L | Serum, plasma, tissue |
| Total Cholesterol Assay Kit | BC0650 | CHOD-PAP enzymatic (cholesterol esterase) | 505 nm | 0.1 mmol/L | 0.2–15 mmol/L | Serum, plasma, tissue |
| Lactic Acid Assay Kit | BC2230 | Lactate oxidase-peroxidase colorimetric | 530 nm | 0.1 mmol/L | 0.2–20 mmol/L | Serum, plasma, tissue |
| Pyruvate Kinase Assay Kit | BC2800 | Kinetic NADH-linked (PEP → pyruvate) | 340 nm (↓A) | 1 U/L | 3–300 U/L | Tissue, cell lysate |
| Hexokinase (HK) Assay Kit | BC0740 | G6PDH-coupled (NADPH production) | 340 nm (↑A) | 0.2 U/L | 0.5–100 U/L | Tissue, cell lysate |
| Phosphofructokinase (PFK) Assay Kit | BC1270 | Fru-6-P → Fru-1,6-P₂ (NADH-linked) | 340 nm (↓A) | 0.5 U/L | 1–100 U/L | Tissue, cell lysate |
| PEPCK Assay Kit | BC2170 | P-enolpyruvate + GDP → GTP + OAA | 340 nm (↑A) | 1 U/L | 2–200 U/L | Liver tissue |
| G6Pase Assay Kit | BC0745 | Glucose-6-P → Glucose + Pi (colorimetric) | 660 nm | 0.5 U/L | 1–100 U/L | Liver, kidney |
| β-Hydroxybutyrate Assay Kit | BC0460 | β-HBDH kinetic (NADH production) | 340 nm (↑A) | 5 μmol/L | 10–500 μmol/L | Serum, plasma |
| Free Fatty Acid (NEFA) Assay Kit | BC0590 | ACS-ACOD-TOOS colorimetric | 546 nm | 0.02 mmol/L | 0.05–2 mmol/L | Serum, plasma, tissue |

## 2. Detailed Assay Principles

### 2.1 ATP Content — Hexokinase/G6PDH Coupled with Phosphomolybdic Acid Detection

ATP content is a direct indicator of cellular energy status. The assay couples ATP-dependent glucose phosphorylation by hexokinase.

```
ATP + Glucose ──[HK]──→ Glucose-6-phosphate + ADP
G-6-P + NADP⁺ ──[G6PDH]──→ 6-Phosphogluconate + NADPH + H⁺
NADPH + PMS ──[Reduction]──→ Reduced PMS + NADP⁺
Reduced PMS + Phosphomolybdic acid → Molybdenum blue (636 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 636 nm |
| Limit of detection | 1 μmol/L ATP |
| Lower limit of quantification | 2 μmol/L |
| Linear range | 1–100 μmol/L ATP |
| Intra-assay CV | <5% (n=20, 20 μmol/L) |
| Inter-assay CV | <10% (n=8 lots) |
| Recovery rate | 90–110% |
| Reaction time | 30 min at 37°C |
| Sample volume | 100 μL |
| Standard | 100 μmol/L ATP (included) |


**Sample Preparation**:

| Sample Type | Procedure | Expected ATP (nmol/mg prot) |
|---|---|---|
| Liver tissue | 0.1 g + 1 mL 0.6 M PCA, homogenize, centrifuge, neutralize | 5–15 |
| Muscle tissue | 0.1 g + 1 mL 0.6 M PCA, bead mill homogenization | 20–40 |
| Cultured cells | 1×10⁶ cells, lyse in 200 μL PCA, centrifuge, neutralize | 5–20 |
| Bacteria | 1×10⁸ cells, boil in TE buffer 5 min, centrifuge | 0.5–5 |

**Critical Note**: Perchloric acid (PCA) extraction must be neutralized with K₂CO₃/KOH to pH 7.0–7.5 before assay. Residual PCA denatures the coupling enzymes.

### 2.2 Glucose — GOD-POD (Trinder) Method

Glucose oxidase specifically oxidizes β-D-glucose to gluconic acid and H₂O₂. Peroxidase then couples H₂O₂ with 4-aminoantipyrine (4-AAP) and phenol to form a pink quinoneimine dye.

```
β-D-Glucose + O₂ + H₂O ──[Glucose Oxidase, pH 7.0, 37°C]──→ Gluconic acid + H₂O₂
2 H₂O₂ + 4-AAP + Phenol ──[POD]──→ Quinoneimine (pink, 505 nm) + 4 H₂O
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 505 nm |
| Limit of detection | 0.1 mmol/L |
| Linear range | 0.5–30 mmol/L |
| Intra-assay CV | <3% (n=20, 5 mmol/L) |
| Inter-assay CV | <6% (n=8 lots) |
| Recovery | 95–105% |
| Reaction time | 15 min at 37°C |
| Sample volume | 10 μL |
| Capacity | 500 assays |

**Reference Values**:

| Sample | Normal Fasting (mmol/L) | Postprandial (mmol/L) |
|---|---|---|
| Human serum | 3.9–6.1 | <11.1 (2 h) |
| Mouse serum | 4–10 | — |
| Rat serum | 4–8 | — |
| Cell culture media | 5 (DMEM) to 25 (high-glucose DMEM) | — |

**Interference**: Ascorbic acid (>0.5 mmol/L) and bilirubin (>200 μmol/L) lower apparent glucose concentration. For culture media, dilute 1:2–1:10 with saline to stay within linear range.

### 2.3 Triglyceride — GPO-PAP Method

Lipoprotein lipase (LPL) hydrolyzes triglycerides to glycerol and free fatty acids. Glycerol is then sequentially converted through coupled enzymatic reactions.

```
Triglyceride ──[LPL, 37°C]──→ Glycerol + 3 × Free fatty acids
Glycerol + ATP ──[GK]──→ Glycerol-3-phosphate + ADP
G-3-P + O₂ ──[GPO]──→ Dihydroxyacetone phosphate + H₂O₂
H₂O₂ + 4-AAP + 3,5-DHBS ──[POD]──→ Quinoneimine (red, 546 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 546 nm |
| Limit of detection | 0.05 mmol/L |
| Linear range | 0.1–10 mmol/L |
| Intra-assay CV | <4% |
| Inter-assay CV | <8% |
| Recovery | 92–108% |
| Sample volume | 10 μL |
| Reaction time | 10 min at 37°C |
| Free glycerol blank | Included (subtract free glycerol for accurate TG) |

**Reference Values**:

| Species | Normal (mmol/L) | High (>mmol/L) |
|---|---|---|
| Human | 0.45–1.69 | >2.26 |
| Mouse (C57BL/6) | 0.5–1.2 | >1.5 (high-fat diet) |
| Rat | 0.4–1.0 | — |

**Critical Note**: For tissue homogenates, free glycerol blank subtraction is essential. The kit includes a separate blank reagent without LPL.

### 2.4 Total Cholesterol — CHOD-PAP Method

Cholesterol esters are hydrolyzed by cholesterol esterase (CE), and free cholesterol is oxidized by cholesterol oxidase (CO).

```
Cholesterol ester + H₂O ──[CE, 37°C]──→ Free cholesterol + Fatty acid
Free cholesterol + O₂ ──[CO]──→ Cholest-4-en-3-one + H₂O₂
2 H₂O₂ + 4-AAP + Phenol ──[POD]──→ Quinoneimine (505 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint colorimetric |
| Wavelength | 505 nm |
| Limit of detection | 0.1 mmol/L |
| Linear range | 0.2–15 mmol/L |
| Intra-assay CV | <3% |
| Inter-assay CV | <6% |
| Sample volume | 10 μL |
| Reaction time | 10 min at 37°C |

**Reference Values**:

| Species | Normal (mmol/L) | HDL-C (mmol/L) | LDL-C (mmol/L) |
|---|---|---|---|
| Human | 3.1–5.7 | 0.9–1.6 | <3.4 |
| Mouse (C57BL/6) | 1.5–3.0 | 1.2–2.5 | 0.2–0.5 |
| Rat | 1.5–2.5 | 0.8–1.5 | 0.3–0.6 |

### 2.5 Lactic Acid — Lactate Oxidase Method

Lactic acid (lactate) is a product of anaerobic glycolysis. The assay uses L-lactate oxidase to produce H₂O₂, detected colorimetrically.

```
L-Lactate + O₂ ──[Lactate Oxidase, pH 7.0]──→ Pyruvate + H₂O₂
2 H₂O₂ + 4-AAP + TOOS ──[POD]──→ Quinoneimine (purple, 530 nm)
```

| Parameter | Specification |
|---|---|
| Detection limit | 0.1 mmol/L |
| Linear range | 0.2–20 mmol/L |
| Intra-assay CV | <4% |
| Sample types | Serum, plasma, tissue homogenate, cell culture media |
| Reaction time | 10 min at 37°C |

**Reference Values**:

| Sample | Normal (mmol/L) | Pathological |
|---|---|---|
| Human serum/plasma | 0.5–2.2 | >4 (lactic acidosis) |
| Mouse serum | 1–4 | Increases with exercise, ischemia |
| Cell culture supernatant | 1–5 (confluent) | 10–20 (hypoxia) |
| Tissue (muscle) | 5–20 nmol/mg prot | — |

### 2.6 Pyruvate Kinase (PK)

Pyruvate kinase catalyzes the final step of glycolysis: phosphoenolpyruvate to pyruvate with ATP generation.

```
PEP + ADP ──[PK, 37°C]──→ Pyruvate + ATP
Pyruvate + NADH + H⁺ ──[LDH]──→ L-Lactate + NAD⁺
(↓A₃₄₀, rate proportional to PK activity)
```

| Parameter | Specification |
|---|---|
| Assay type | Kinetic (NADH consumption) |
| Wavelength | 340 nm |
| Limit of detection | 1 U/L |
| Linear range | 3–300 U/L |
| Intra-assay CV | <6% |
| Unit definition | 1 U = 1 μmol PEP converted per min |

### 2.7 Hexokinase (HK)

Hexokinase catalyzes the first committed step of glycolysis: glucose phosphorylation.

```
Glucose + ATP ──[HK, 37°C]──→ Glucose-6-phosphate + ADP
G-6-P + NADP⁺ ──[G6PDH]──→ 6-Phosphogluconate + NADPH + H⁺
(↑A₃₄₀, rate proportional to HK activity)
```

| Parameter | Specification |
|---|---|
| Assay type | Kinetic |
| Wavelength | 340 nm |
| Detection limit | 0.2 U/L |
| Linear range | 0.5–100 U/L |
| Intra-assay CV | <5% |

### 2.8 Phosphofructokinase (PFK)

PFK catalyzes the rate-limiting step of glycolysis: fructose-6-phosphate to fructose-1,6-bisphosphate.

```
Fru-6-P + ATP ──[PFK, 37°C]──→ Fru-1,6-P₂ + ADP
Fru-1,6-P₂ ──[Aldolase]──→ G-3-P + DHAP
G-3-P ──[TPI]──→ DHAP (converted)
2 DHAP + 2 NADH ──[GDH]──→ 2 Glycerol-3-P + 2 NAD⁺
(↓A₃₄₀, 2 NADH consumed per Fru-1,6-P₂ formed)
```

| Parameter | Specification |
|---|---|
| Assay type | Kinetic (2-step coupled) |
| Wavelength | 340 nm |
| Detection limit | 0.5 U/L |
| Linear range | 1–100 U/L |

### 2.9 PEPCK (Phosphoenolpyruvate Carboxykinase)

PEPCK is a key gluconeogenic enzyme that converts oxaloacetate to phosphoenolpyruvate.

```
OAA + GTP ──[PEPCK, 37°C]──→ PEP + GDP
PEP + ADP ──[PK]──→ Pyruvate + ATP
Pyruvate + NADH ──[LDH]──→ Lactate + NAD⁺
(↓A₃₄₀, rate proportional to PEPCK activity)
```

| Parameter | Specification |
|---|---|
| Detection limit | 1 U/L |
| Linear range | 2–200 U/L |
| Intra-assay CV | <7% |
| Tissue | Liver (highest), kidney, adipose |

### 2.10 Glucose-6-Phosphatase (G6Pase)

G6Pase catalyzes the terminal step of gluconeogenesis and glycogenolysis. The generated phosphate is detected via molybdenum blue.

```
Glucose-6-P + H₂O ──[G6Pase, pH 6.5, 37°C]──→ Glucose + Pi
Pi + (NH₄)₆Mo₇O₂₄ + Reducing agent → Molybdenum blue (660 nm)
```

| Parameter | Specification |
|---|---|
| Assay type | Endpoint (inorganic phosphate detection) |
| Wavelength | 660 nm |
| Detection limit | 0.5 U/L |
| Linear range | 1–100 U/L |

**Critical Note**: Microsomes must be intact for G6Pase activity. Freeze-thaw or detergents permeabilize microsomal membranes and may increase apparent activity (latency release).

### 2.11 β-Hydroxybutyrate (β-HB)

β-Hydroxybutyrate is the most abundant ketone body, elevated in ketosis, fasting, and diabetic ketoacidosis.

```
β-Hydroxybutyrate + NAD⁺ ──[β-HBDH, pH 9.5]──→ Acetoacetate + NADH + H⁺
(↑A₃₄₀, proportional to β-HB concentration)
```

| Parameter | Specification |
|---|---|
| Limit of detection | 5 μmol/L |
| Linear range | 10–500 μmol/L |
| Intra-assay CV | <6% |
| Reference (human, fed) | 10–300 μmol/L |
| Pathological | >800 μmol/L (ketosis) |

### 2.12 Free Fatty Acid (NEFA) — ACS-ACOD Method

Free fatty acids are activated by acyl-CoA synthetase (ACS), then oxidized by acyl-CoA oxidase (ACOD) producing H₂O₂.

```
FFA + ATP + CoA ──[ACS]──→ Acyl-CoA + AMP + PPi
Acyl-CoA + O₂ ──[ACOD]──→ 2,3-trans-Enoyl-CoA + H₂O₂
H₂O₂ + 4-AAP + TOOS ──[POD]──→ Quinoneimine (purple, 546 nm)
```

| Parameter | Specification |
|---|---|
| Limit of detection | 0.02 mmol/L |
| Linear range | 0.05–2 mmol/L |
| Intra-assay CV | <5% |
| Reference (human serum) | 0.1–0.9 mmol/L |

## 3. Sample Preparation Guide

| Assay | Tissue Protocol | Cell Protocol | Serum/Plasma |
|---|---|---|---|
| ATP | PCA extraction (0.6 M), neutralize to pH 7.0 | PCA extraction, 1×10⁶ cells | Direct assay possible (PCA needed for protein removal) |
| Glucose | — | — | Direct; dilute culture media |
| Triglyceride | Chloroform:MeOH (2:1) extraction | Same as tissue | Direct; free glycerol blank required |
| Cholesterol | Chloroform:methanol extraction | Same as tissue | Direct |
| Lactic Acid | 0.1 g in 0.5 mL saline, homogenize | Lyse 1×10⁶ cells in 200 μL | Direct; use fluoride/oxalate plasma |
| PK | 0.1 g in 1 mL extraction buffer | 1×10⁶ cells in 200 μL | — |
| HK | 0.1 g in 1 mL extraction buffer + 0.1% Triton | 1×10⁶ cells in 200 μL | — |

## 4. Interference Table

| Substance | Glucose (GOD-POD) | TG (GPO-PAP) | Cholesterol (CHOD-PAP) | Lactic Acid | β-HB | NEFA |
|---|---|---|---|---|---|---|
| Ascorbic acid (>0.5 mM) | Strong | Moderate | Strong | Moderate | None | Moderate |
| Bilirubin (>200 μmol/L) | Moderate | Moderate | Moderate | None | None | None |
| Hemoglobin (>1 g/L) | Moderate | Moderate | Moderate | Strong | None | Moderate |
| EDTA | None | None | None | None | None | None |
| Heparin | None | None | None | None | None | None |
| DTT (>1 mM) | Strong | Strong | Strong | Moderate | None | Strong |

## 5. Related Products & Cross-References

- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Hepatotoxicity Assay Kits](hepatotoxicity.md)
- [▶ Enzyme Activity Assay Kits](enzyme-activity.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
