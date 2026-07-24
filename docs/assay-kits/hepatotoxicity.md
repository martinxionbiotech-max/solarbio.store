---
title: "Technical Specification: Hepatotoxicity & Clinical Chemistry Assay Kits"
description: "Technical specifications for Solarbio liver function and clinical chemistry assay kits — ALT, AST, ALP, GGT, LDH, 5′-NT, creatinine, BUN, total protein, and bilirubin with validated protocols, reaction equations, interference data, and reference ranges."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Hepatotoxicity & Clinical Chemistry Assay Kits",
 "description": "Full specifications for Solarbio liver function and clinical chemistry assay kits covering ALT, AST, ALP, GGT, LDH, 5′-NT, creatinine, BUN, total protein, and bilirubin with reaction mechanisms and performance data.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Hepatotoxicity Assay"}
}
</script>

# Technical Specification: Hepatotoxicity & Clinical Chemistry Assay Kits

!!! note "Official Source Verification"
    This documentation is published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial inquiries, visit the **[Solarbio Store](https://solarbio.store)**.

## 1. Product Range

| Assay | SKU | Principle | Wavelength | Detection Limit | Linear Range | Sample Types |
|---|---|---|---|---|---|---|
| ALT (GPT) | BC1550 | Reitman-Frankel (2,4-DNPH) | 505 nm | 1 U/L | 2–150 U/L | Serum, plasma |
| AST (GOT) | BC1560 | Reitman-Frankel (2,4-DNPH) | 505 nm | 2 U/L | 5–200 U/L | Serum, plasma |
| ALP | BC2140 | pNPP hydrolysis (kinetic) | 405 nm | 1 U/L | 3–500 U/L | Serum, plasma |
| γ-GT (GGT) | BC1225 | L-γ-glutamyl-p-nitroanilide | 405 nm | 0.5 U/L | 2–300 U/L | Serum, plasma |
| LDH | BC0680 | NADH → NAD⁺ (kinetic, UV) | 340 nm (↓A) | 2 U/L | 5–600 U/L | Serum, cell lysate, tissue |
| 5′-Nucleotidase (5′-NT) | BC1230 | Adenosine → NH₃ detection | 640 nm | 0.5 U/L | 1–100 U/L | Serum, plasma |
| Creatinine | BC4780 | Jaffe reaction (picric acid, alkaline) | 510 nm | 5 μmol/L | 10–500 μmol/L | Serum, plasma, urine |
| BUN (Urea) | BC1520 | Urease-indophenol (Berthelot) | 630 nm | 0.5 mmol/L | 1–25 mmol/L | Serum, plasma |
| Total Protein | BC3740 | Biuret method | 540 nm | 0.1 g/L | 0.5–100 g/L | Serum, plasma |
| Total Bilirubin | BC1800 | Diazotized sulfanilic acid (Jendrassik-Grof) | 540 nm | 1 μmol/L | 2–200 μmol/L | Serum, plasma |

## 2. Detailed Assay Principles and Reaction Equations

### 2.1 ALT (Alanine Aminotransferase / GPT) — Reitman-Frankel Method

ALT catalyzes the transfer of an amino group from L-alanine to α-ketoglutarate, producing pyruvate and L-glutamate. Pyruvate reacts with 2,4-dinitrophenylhydrazine (DNPH) to form a hydrazone chromophore in alkaline solution.

```
L-Alanine + α-Ketoglutarate ──[ALT (pH 7.4, 37°C)]──→ Pyruvate + L-Glutamate

Pyruvate + DNPH (2,4-dinitrophenylhydrazine)
    ──[Alkaline]──→ Pyruvate-2,4-dinitrophenylhydrazone (brown, 505 nm)
```

| Parameter | Specification |
|---|---|
| Substrate | L-Alanine (200 mM) + α-KG (2 mM) in PBS, pH 7.4 |
| Incubation | 30 min at 37°C |
| DNPH incubation | 2,4-DNPH (0.1% in 1 M HCl), 20 min at 37°C |
| Alkaline development | 0.4 M NaOH, 10 min at RT |
| Wavelength | 505 nm |
| Detection limit | 1 U/L |
| Linear range | 2–150 U/L |
| Intra-assay CV | <5% (n=20, 50 U/L) |
| Inter-assay CV | <10% (n=10 lots) |
| Sample volume | 50 μL |
| Calibrator | 50 U/L pyruvate calibrator (included) |
| Unit definition | 1 U = 1 μmol pyruvate formed per min at 37°C |

### 2.2 AST (Aspartate Aminotransferase / GOT) — Reitman-Frankel Method

AST transfers an amino group from L-aspartate to α-ketoglutarate, producing oxaloacetate (OAA) and L-glutamate. OAA is unstable and spontaneously decarboxylates to pyruvate, which is detected with DNPH.

```
L-Aspartate + α-Ketoglutarate ──[AST (pH 7.4, 37°C)]──→ Oxaloacetate + L-Glutamate

Oxaloacetate (spontaneous) → Pyruvate + CO₂

Pyruvate + DNPH → Pyruvate-2,4-dinitrophenylhydrazone (505 nm)
```

| Parameter | Specification |
|---|---|
| Substrate | L-Aspartate (200 mM) + α-KG (2 mM) |
| Incubation | 30 min at 37°C |
| Detection limit | 2 U/L |
| Linear range | 5–200 U/L |
| Intra-assay CV | <5% |
| Calibrator | Included (50 U/L) |

**ALT and AST Clinical Interpretation**:

| AST/ALT Ratio | Condition |
|---|---|
| <1 (ALT > AST) | Acute viral hepatitis, NAFLD |
| >1.5 (AST > ALT) | Alcoholic hepatitis, cirrhosis |
| >2 (AST 2–20× ALT) | Alcoholic liver disease |
| ALT > 300 U/L | Consider drug-induced liver injury (DILI) |
| Both > 1000 U/L | Massive hepatic necrosis, acetaminophen overdose |

### 2.3 ALP (Alkaline Phosphatase) — pNPP Method

ALP hydrolyzes p-nitrophenyl phosphate (pNPP) to p-nitrophenol and inorganic phosphate. The reaction is performed at pH 10.3 (2-amino-2-methyl-1-propanol buffer) and stopped with NaOH.

```
pNPP (colorless) + H₂O ──[ALP, pH 10.3, 37°C]──→ p-Nitrophenol (yellow, 405 nm) + Pi
```

| Parameter | Specification |
|---|---|
| Substrate | pNPP (10 mM in AMP buffer, pH 10.3) |
| Incubation | 30 min at 37°C |
| Stop | 0.1 M NaOH |
| Wavelength | 405 nm |
| Detection limit | 1 U/L |
| Linear range | 3–500 U/L |
| Intra-assay CV | <4% |
| Unit definition | 1 U = 1 μmol pNPP hydrolyzed per min |

**Isoform Note**: ALP exists as tissue-specific isoforms (liver/bone/kidney, intestinal, placental). Elevated liver ALP indicates cholestasis. For bone-specific ALP, heat inactivation at 56°C for 15 min selectively inactivates bone ALP by ~50%.

### 2.4 γ-GT (Gamma-Glutamyl Transferase / GGT)

GGT transfers the γ-glutamyl group from L-γ-glutamyl-p-nitroanilide to glycylglycine, releasing p-nitroaniline (yellow).

```
L-γ-Glutamyl-p-nitroanilide + Glycylglycine
    ──[GGT pH 8.6, 37°C]──→ L-γ-Glutamyl-Glycylglycine + p-Nitroaniline (yellow, 405 nm)
```

| Parameter | Specification |
|---|---|
| Substrate | L-γ-Glutamyl-p-nitroanilide (4 mM) |
| Acceptor | Glycylglycine (50 mM) |
| Buffer | Tris-HCl, pH 8.6 |
| Wavelength | 405 nm |
| Detection limit | 0.5 U/L |
| Linear range | 2–300 U/L |
| Intra-assay CV | <4% |
| Unit definition | 1 U = 1 μmol p-nitroaniline formed per min |

**Clinical Note**: GGT is the most sensitive marker for alcohol-induced hepatotoxicity. Elevated GGT with normal ALP suggests chronic alcohol consumption; elevation of both GGT and ALP indicates cholestasis.

### 2.5 LDH (Lactate Dehydrogenase) — Kinetic UV Method

LDH catalyzes reversible conversion of lactate to pyruvate with NAD⁺/NADH as cofactor. The kit measures the forward reaction (lactate → pyruvate), detected as NADH production (↑A₃₄₀).

```
L-Lactate + NAD⁺ ──[LDH, pH 9.0, 37°C]──→ Pyruvate + NADH + H⁺
(NADH production monitored at 340 nm, ↑A)
```

| Parameter | Specification |
|---|---|
| Assay type | Kinetic (endpoint reading or rate) |
| Wavelength | 340 nm |
| Detection limit | 2 U/L |
| Linear range | 5–600 U/L |
| Intra-assay CV | <5% |
| Sample volume | 20–50 μL |
| Unit definition | 1 U = 1 μmol NADH formed per min at 37°C |
| ε (NADH) | 6.22 × 10³ L·mol⁻¹·cm⁻¹ |

**LDH Isoenzyme Distribution**:

| Isoenzyme | Tissue Origin | Clinical Significance |
|---|---|---|
| LDH-1 (H₄) | Heart, RBC | Elevated in MI, hemolysis |
| LDH-2 (H₃M) | Heart, RBC | Dominant in serum normally |
| LDH-3 (H₂M₂) | Lung, spleen | Elevation in pulmonary disease |
| LDH-4 (HM₃) | Liver, skeletal muscle | Hepatocellular injury |
| LDH-5 (M₄) | Skeletal muscle, liver | Liver disease, muscle damage |

LDH-1/LDH-2 ratio >1 is a classic pattern for acute myocardial infarction (the "flipped" ratio).

### 2.6 5′-Nucleotidase (5′-NT)

5′-NT hydrolyses adenosine monophosphate (AMP) to adenosine and inorganic phosphate. The phosphate is detected via the molybdenum blue method.

```
Adenosine-5′-monophosphate + H₂O ──[5′-NT, pH 7.5, 37°C]──→ Adenosine + Pi

Pi + (NH₄)₂MoO₄ + Reducing agent → Molybdenum blue (640 nm)
```

| Parameter | Specification |
|---|---|
| Detection limit | 0.5 U/L |
| Linear range | 1–100 U/L |
| Intra-assay CV | <6% |

**Clinical Note**: 5′-NT is specific for hepatobiliary diseases. Unlike ALP, it is not elevated in bone disease, making it useful for distinguishing hepatic versus bone-origin ALP elevations.

### 2.7 Creatinine — Jaffe Reaction

Creatinine reacts with picric acid in alkaline solution to form an orange-red complex.

```
Creatinine + Picric acid ──[NaOH, pH ~12]──→ Creatinine-picrate complex (orange-red, 510 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 510 nm |
| Detection limit | 5 μmol/L |
| Linear range | 10–500 μmol/L |
| Intra-assay CV | <5% (n=20, 100 μmol/L) |
| Inter-assay CV | <10% |
| Deproteinization | Required (tungstic acid precipitation included) |
| Reaction time | 15 min at RT |
| Interference | Ketone bodies, glucose (>20 mmol/L), cephalosporins — auto-blank correction included |

**Critical Notes**:
- Serum creatinine reference: 44–106 μmol/L (human). Rodents: 15–40 μmol/L (mouse), 20–60 μmol/L (rat).
- Urine creatinine: used to normalize analyte excretion (e.g., urinary albumin/creatinine ratio).

### 2.8 BUN (Blood Urea Nitrogen) — Urease-Indophenol Method

Urease hydrolyzes urea to ammonia and CO₂. Ammonia reacts with hypochlorite and salicylate to form a green indophenol dye (Berthelot reaction).

```
Urea + H₂O ──[Urease, 37°C, 15 min]──→ 2 NH₃ + CO₂

NH₃ + Salicylate + NaOCI ──[Nitroprusside catalyst]──→ Indophenol (green-blue, 630 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 630 nm |
| Detection limit | 0.5 mmol/L |
| Linear range | 1–25 mmol/L urea |
| Intra-assay CV | <4% |
| Inter-assay CV | <8% |
| Standard | 10 mmol/L urea (included) |

**Reference Ranges**:

| Species | BUN (mmol/L) | Creatinine (μmol/L) |
|---|---|---|
| Human | 2.5–7.5 | 44–106 |
| Mouse | 5–12 | 15–40 |
| Rat | 4–10 | 20–60 |
| Dog | 2.5–9.5 | 44–130 |

### 2.9 Total Protein — Biuret Method

Peptide bonds in proteins form a violet complex with Cu²⁺ in alkaline solution (biuret reaction).

```
Protein (peptide bonds) + Cu²⁺ ──[NaOH, pH ~12]──→ Cu²⁺-peptide complex (violet, 540 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 540 nm |
| Detection limit | 0.1 g/L |
| Linear range | 0.5–100 g/L |
| Intra-assay CV | <3% |

### 2.10 Total Bilirubin — Jendrassik-Grof Method

Bilirubin reacts with diazotized sulfanilic acid (diazo reagent) to form azobilirubin (red-purple). Caffeine-sodium benzoate accelerates the reaction by disrupting bilirubin-albumin binding.

```
Bilirubin + Diazotized sulfanilic acid ──[Caffeine, 30 min]──→ Azobilirubin (540 nm)
```

| Parameter | Specification |
|---|---|
| Wavelength | 540 nm |
| Detection limit | 1 μmol/L |
| Linear range | 2–200 μmol/L |
| Intra-assay CV | <5% |

## 3. Optimized Reaction Parameters

### 3.1 ALT/AST Modified Protocol (High Sensitivity)

| Step | Standard | High Sensitivity (Low Activity) |
|---|---|---|
| Sample volume | 50 μL | 100 μL (reduce calibrator volume) |
| Substrate volume | 100 μL | 50 μL (concentrated) |
| Incubation | 30 min | 60 min |
| DNPH incubation | 20 min | 30 min |
| NaOH development | 0.4 M, 10 min | 0.4 M, 15 min |

**Note**: The high-sensitivity modification achieves a detection limit of 0.5 U/L. Validate linearity when modifying incubation times.

### 3.2 ALP Optimization by Sample Type

| Sample | Incubation Time | Expected Activity | Dilution Factor |
|---|---|---|---|
| Human serum (normal) | 30 min | 40–150 U/L | None |
| Serum (cholestasis) | 15 min | 200–800 U/L | 1:2 with saline |
| Bone tissue extract | 30 min | 50–300 U/L | None |
| Intestinal mucosa | 30 min | 100–500 U/L | 1:2 |
| Cell lysate | 30–60 min | 10–200 U/L | Variable |

## 4. Sample Preparation Guide

| Assay | Sample Prep | Storage | Notes |
|---|---|---|---|
| ALT/AST | Serum, no hemolysis | 2–8°C, 48 h; -20°C, 1 month | Hemolyzed samples give invalid results (RBC contains AST) |
| ALP | Serum, fresh preferred | 2–8°C, 5 days | ALP activity decreases on freezing; avoid freeze-thaw |
| GGT | Serum, no special prep | 2–8°C, 7 days; -20°C, 1 month | Stable; pregnancy can falsely elevate |
| LDH | Serum (separate from cells promptly) | 2–8°C, 3 days | RBC LDH is ~100× serum; even minimal hemolysis invalidates results |
| Creatinine | Serum or urine | 2–8°C, 7 days; -20°C, 3 months | Deproteinize before measurement |
| BUN | Serum or plasma | 2–8°C, 1 week; -20°C, 1 month | Ammonium heparin anticoagulant invalidates assay |
| Bilirubin | Serum, protect from light | 2–8°C, 2 days (dark) | Protect from light — bilirubin is photolabile |

## 5. Interference Table

| Substance | ALT (DNPH) | AST (DNPH) | ALP (pNPP) | LDH (NADH) | Creatinine (Jaffe) | BUN (Indophenol) |
|---|---|---|---|---|---|---|
| Hemoglobin (>0.5 g/L) | Strong | Strong | None | Strong | Moderate | None |
| Triglycerides (>5 mM) | Moderate | Moderate | None | None | None | None |
| Bilirubin (>200 μmol/L) | Moderate | Moderate | None | None | None | None |
| Pyruvate (>1 mM) | Strong | Strong | None | None | None | None |
| Ascorbic acid (>1 mM) | None | None | None | None | None | Strong |
| EDTA | None | None | Inhibits (chelates) | None | None | None |
| Ammonium heparin | None | None | None | None | None | Strong |
| Glucose (>20 mM) | None | None | None | None | Moderate | None |

## 6. Reference Ranges (Rodent)

| Assay | Mouse Serum | Rat Serum | Human Serum |
|---|---|---|---|
| ALT (U/L) | 25–80 | 20–60 | 7–40 |
| AST (U/L) | 50–150 | 40–120 | 10–35 |
| ALP (U/L) | 40–120 | 60–200 | 40–120 |
| GGT (U/L) | 0–5 | 0–5 | 5–40 |
| LDH (U/L) | 200–600 | 150–500 | 100–250 |
| Creatinine (μmol/L) | 15–40 | 20–60 | 44–106 |
| BUN (mmol/L) | 5–12 | 4–10 | 2.5–7.5 |

**Note**: Reference ranges are provided for the C57BL/6 mouse (8–12 weeks, male) and Sprague-Dawley rat. Significant strain, age, and sex differences exist. Always run age- and sex-matched controls.

## 7. Drug-Induced Liver Injury Markers — Suggested Panel

| Injury Pattern | Key Markers | Typical Findings |
|---|---|---|
| Hepatocellular | ALT ⬆, AST ⬆, ALT > AST | APAP, CCl₄, CCl₃-induced injury |
| Cholestatic | ALP ⬆, GGT ⬆, Bilirubin ⬆ | ANIT, α-naphthylisothiocyanate |
| Mixed | ALT ⬆, ALP ⬆, GGT ⬆ | Various drugs |
| Mitochondrial | AST > ALT, LDH ⬆ | Fialuridine, valproic acid |

## 8. Related Products & Cross-References

- [▶ Oxidative Stress Assay Kits](oxidative-stress.md)
- [▶ Inflammation & Injury Assay Kits](inflammation.md)
- [▶ Related Protocol: Enzyme Activity Assay Protocol](../protocols/enzyme-assay-protocol.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
