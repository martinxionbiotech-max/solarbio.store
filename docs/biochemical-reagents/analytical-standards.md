---
title: "Technical Specification: Analytical Standards"
description: "Technical specifications for Solarbio analytical reference standards — HPLC standards, pharmacopoeia-grade reference materials, and certified calibration standards."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Analytical Standards",
 "description": "Technical specifications for Solarbio analytical reference standards — HPLC standards, pharmacopoeia-grade reference materials, and certified calibration standards.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: Analytical Standards

## 1. Grade Classification

| Grade | Purity | Certification | Application | Documentation |
|---|---|---|---|---|
| Analytical Standard | ≥ 99.0% | HPLC, NMR, MS, Karl Fischer | Method validation, calibration curves | COA with full analytical data |
| Pharmacopoeia Grade | Meets USP/EP/CP specifications | Lot-specific COA with monograph references | Pharmaceutical QC, compendial testing | COA with pharmacopoeia method results |
| Research Grade | ≥ 95% | HPLC, ¹H NMR | Research use only, preliminary screening | COA (HPLC chromatogram, NMR peaks) |

## 2. Product Categories

| Category | Example Standards | Typical Application | SKU Examples |
|---|---|---|---|
| Pharmaceutical impurities | Related substance standards | Impurity identification, quantification | SP-series |
| Natural product standards | Baicalin, berberine, resveratrol, curcumin | Herbal extract standardization | SN-series |
| Pesticide residue standards | Organophosphates, pyrethroids | Food safety testing, environmental analysis | SP-series |
| Vitamin and nutrient standards | Vitamins A, C, D, E, B-complex | Nutritional analysis, supplement QC | SV-series |
| Fatty acid methyl esters (FAME) | C4–C24 methyl esters | Lipid profiling, food authentication | SF-series |
| Inorganic ion standards | Nitrate, phosphate, sulfate | Water quality testing, soil analysis | SA-series |
| Mycotoxin standards | Aflatoxin B1, ochratoxin A | Food safety, feed testing | SM-series |

## 3. Pharmacopoeia Monograph Reference Table

Each pharmacopoeia-grade standard includes lot-specific results per the relevant compendial monograph. Refer to the table below for method alignment.

| Standard Type | USP Monograph | EP Monograph | JP Monograph | ChP Monograph | Typical Analytical Method |
|---|---|---|---|---|---|
| Impurity standards (organic) | USP <621> Chromatography | Ph. Eur. 2.2.46 | JP <2.01> | ChP 0512 | HPLC-UV, RRT ±0.02 |
| Natural product (baicalin) | USP <561> Articles of botanical | — | — | ChP <0821> | HPLC-DAD, comparison to accredited CRS |
| Pesticide residues | USP <561> | Ph. Eur. 2.8.13 | JP <2.62> | ChP 2341 | GC-MS/MS, LC-MS/MS |
| Vitamin A | USP Vitamin A Assay | Ph. Eur. 01/2008:0216 | JP Vitamin A | ChP <0721> | UV-Vis after saponification, HPLC |
| Vitamin D | USP <581> Vitamin D | Ph. Eur. 01/2008:0217 | JP Vitamin D | ChP <0721> | HPLC (normal phase) |
| FAME mix | USP <401> Fats and Oils | Ph. Eur. 2.4.22 | JP FAME | ChP <0713> | GC-FID, normalization |
| Mycotoxin (aflatoxin B1) | USP <561> | Ph. Eur. 2.8.18 | JP <2.65> | ChP 2351 | HPLC-FLD with post-column derivatization |
| Inorganic ions (nitrate) | USP <221> | Ph. Eur. 2.4.13 | JP | ChP <0808> | Ion chromatography, UV detection |
| Heavy metals | USP <231> (former), USP <232>/<233> | Ph. Eur. 2.4.8 / 2.2.58 | JP <1.07> | ChP <0821> | ICP-OES or ICP-MS (USP <233>) |
| Residual solvents | USP <467> | Ph. Eur. 2.4.24 | JP <2.46> | ChP 0861 | GC-FID headspace (ICH Q3C) |

**Note**: Solarbio pharmacopoeia-grade standards are characterized against compendial reference standards (USP RS, EP CRS, JP RS, or ChP CRS) where available. Where no compendial standard exists, characterization is performed using fully characterized in-house primary standards traceable to NIST SRM or equivalent.

## 4. Uncertainty Budget

Assigned purity values are reported with expanded uncertainty (U) at k=2 (95% confidence interval). The combined standard uncertainty (u_c) is calculated from the following sources.

| Uncertainty Source | Typical Contribution (u, relative %) | Contribution to u_c² | Notes |
|---|---|---|---|
| HPLC area% repeatability | 0.10–0.30% | (s / √n) from 6 injections | Type A evaluation |
| HPLC area% — injection-to-injection | 0.05–0.15% | Repeatability of autosampler | Type A |
| Moisture (Karl Fischer) | 0.05–0.20% | Determined on same lot | Type B — KF coulometric |
| Residual solvents (GC-HS) | 0.02–0.10% | ICH Q3C class 2/3, if applicable | Type B — GC-FID |
| Inorganic ash/residue on ignition | 0.01–0.05% | USP <281> | Type B — furnace weight loss |
| Non-volatile impurities (NMR) | 0.10–0.50% | ¹H NMR qNMR (internal standard method) | Type A (when used as primary method) |
| Balance calibration | 0.02–0.05% | Certificate of calibration | Type B — rectangular distribution |
| Purity of reference material (if area normalization) | 0.20–0.50% | Combined from above sources | Combined uncertainty |

**Calculation**: u_c = √(Σ u_i²). Expanded uncertainty: U = k × u_c (k = 2, 95% confidence).

**Example**: For a standard with HPLC purity 99.5%, KF moisture 0.2%, residual solvents 0.05%, the combined standard uncertainty u_c ≈ 0.22%, giving U = 0.44% (k=2). The certified purity is therefore reported as 99.50% ± 0.44%.

## 5. Stability Monitoring Program

Solarbio analytical standards are monitored under a formal stability program per ISO 17034 requirements.

| Storage Condition | Re-Certification Interval | Monitoring Parameters | Actions on Out-of-Specification |
|---|---|---|---|
| −20°C (freezer) | 12 months | Purity (HPLC area%), moisture (KF), appearance | Immediate retest; if OOS confirmed, update shelf life and notify active customers |
| 2–8°C (refrigerator) | 6 months | Purity (HPLC area%), moisture (KF), appearance | Same as above |
| 15–25°C (controlled RT) | 3 months (first 12 months), then 6 months | Purity (HPLC area%), moisture (KF), appearance, residual solvents | Same as above |
| −20°C under N₂ (sealed ampoule) | 24 months | Purity (HPLC), moisture (KF), headspace O₂ | Confirm seal integrity; O₂ >2% triggers investigation |
| Light-exposed (accelerated, 30°C/65% RH) | 1 month | Appearance (color change), HPLC purity | Used to predict photostability per ICH Q1B |

**Long-term trend analysis**: Each lot is tracked for purity trend over time. The monitoring data are used to establish real-time shelf-life extensions (ICH Q1E approach). For long-stable compounds (≥99.5% purity after 36 months), shelf life may be extended to 48 or 60 months following data review.

## 6. Expanded Handling Protocols

### 6.1 Hygroscopic Standards

Standards with documented moisture sensitivity (e.g., hygroscopic salts, hydrates, lyophilized peptides):

- **Pre-opening**: Allow vial to reach room temperature in a sealed desiccator (silica gel, blue-indicating) for ≥1 h.
- **Opening**: Work in a glove box or dry bag with N₂ purge (<10% RH). Alternatively, open rapidly in a low-humidity room (<30% RH) and cap immediately after sampling.
- **Sampling**: Use a single-use spatula. Never return excess material to the original vial.
- **Post-sampling**: Purge headspace with dry N₂ or Ar (5 s), immediately reseal with original cap and Parafilm. Return to desiccated storage.
- **Discard**: If clumping or caking is observed, discard the standard. Do not attempt to re-dry.

### 6.2 Light-Sensitive Standards

Standards documented as photolabile (e.g., resveratrol, retinol, riboflavin, aflatoxins, curcumin):

- **Storage**: Keep in original amber glass vial inside a secondary opaque container (foil-wrapped box).
- **Workspace**: Use a yellow safe-light or dim the room lights. Avoid direct sunlight and fluorescent lighting within 1 m of the bench.
- **Weighing**: Use amber microcentrifuge tubes or wrap clear tubes with aluminum foil.
- **Solution preparation**: Prepare in amber volumetric flasks. If amber glass is unavailable, wrap clear glass with two layers of aluminum foil.
- **HPLC analysis**: Use amber autosampler vials. Set autosampler temperature to 4°C for labile compounds.

### 6.3 Oxygen-Sensitive Standards

Standards prone to oxidation (e.g., unsaturated fatty acid standards, catechol-containing polyphenols, thiols):

- **Opening**: Open in a glove box under N₂ or Ar atmosphere.
- **Solvent degassing**: Purge all solvents with N₂ or Ar for 10 min before dissolving the standard. Use septum-sealed vials for stock solutions.
- **Antioxidant**: For stock solutions containing thiols (e.g., glutathione, NAC), add 1 mM DTT or 0.5 mM TCEP if compatible with the intended application.
- **Storage**: Store solutions under inert gas in gas-tight vials with PTFE-lined septa. Use crimp-top vials rather than snap-cap tubes.
- **Monitoring**: Monitor purity weekly by HPLC. A decrease >1% in HPLC area% indicates oxidation; discard and prepare fresh.

## 7. Method-Specific Preparation Tables

### 7.1 Solvent Recommendations by Analytical Technique

| Technique | Recommended Solvents | Not Recommended | Concentration Range | Filter Requirement |
|---|---|---|---|---|
| HPLC-UV (reverse phase) | Methanol, ACN, mobile phase | DMSO (high UV cutoff, column damage) | 0.1–100 µg/mL | 0.45 µm PTFE filter |
| HPLC-UV (normal phase) | Hexane/IPA, heptane/ethanol | Water, methanol (>5%) | 0.1–50 µg/mL | 0.45 µm PTFE |
| LC-MS | Methanol, ACN, water (LC-MS grade) | Non-volatile buffers (phosphate, borate); DMSO preferred over DMF | 1–1000 ng/mL | 0.22 µm PVDF |
| UPLC/UHPLC | ACN or methanol (low volume, low viscosity) | High-viscosity solvents (DMSO, DMF >10%) | 0.05–50 µg/mL | 0.2 µm PTFE |
| GC-FID | Hexane, heptane, ethyl acetate | Water, DMSO, DMF (damage inlet) | 1–100 µg/mL | 0.45 µm PTFE (syringe filter) |
| GC-MS | Hexane, heptane, MTBE | Aqueous, high-boiling solvents | 0.1–10 µg/mL | 0.22 µm PTFE |
| UV-Vis spectrophotometry | Water, ethanol, methanol | Solvents absorbing in measurement range | 1–100 µg/mL | Not typically required |
| Fluorescence spectroscopy | Water, ethanol, DMSO | Solvents that quench fluorescence (halogenated) | 0.1–10 µg/mL (varies) | 0.22 µm if particulates present |
| IR (KBr pellet) | N/A (solid state) | Moisture present in sample | 0.5–2% in KBr | Dry KBr (120°C, 4 h) |
| Melting point | N/A (solid) | Impure samples | ~2–5 mg | Dry sample (vacuum desiccator, 2 h) |

### 7.2 Preparation of Calibration Standards

| Level | Concentration | Preparation from Stock (1 mg/mL) | Purpose |
|---|---|---|---|
| Stock | 1 mg/mL (1000 ppm) | Weigh 10.0 mg ± 0.1 mg, dissolve in 10.0 mL solvent | Primary stock, stable ≤1 month at −20°C |
| Stock (diluted) | 100 µg/mL | 1 mL stock + 9 mL solvent | Intermediate stock, prepare fresh |
| Calibrator 1 | 50 µg/mL | 0.5 mL stock + 9.5 mL solvent | Highest calibrator |
| Calibrator 2 | 25 µg/mL | 0.25 mL stock + 9.75 mL solvent | Mid-range |
| Calibrator 3 | 10 µg/mL | 100 µL stock + 9.9 mL solvent | Mid-range |
| Calibrator 4 | 5 µg/mL | 500 µL of 100 µg/mL + 9.5 mL solvent | Mid-range |
| Calibrator 5 | 1 µg/mL | 100 µL of 100 µg/mL + 9.9 mL solvent | Low limit |
| Calibrator 6 | 0.5 µg/mL | 50 µL of 100 µg/mL + 9.95 mL solvent | LLOQ |

**Note**: For LC-MS work, prepare calibrators in 10:90 water:methanol (v/v) to match injection solvent. Prepare dilution series fresh daily. Use certified Class A volumetric glassware.

## 8. Reference Standard Storage Log Template

| Field | Entry |
|---|---|
| Standard name | Example: Baicalin |
| Lot number | B2024-001 |
| SKU | SN8010 |
| Purity (HPLC area%) | 99.3% |
| Quantity received | 100 mg |
| Date received | 2024-05-15 |
| Certificate of Analysis | BAICALIN-COA-240515.pdf |
| Storage location | Freezer A, shelf 3, amber vial box |
| Storage temperature | 2–8°C |
| Opening 1 | 2024-06-01, ~2 mg removed, N₂ blanket applied |
| Current remaining mass | ~98 mg |
| Re-certification due | 2025-05-15 (annual) |
| Next purity monitoring | 2025-01-15 (6-month check) |
| Disposition | Active — within valid retest period |
| Disposal date | — |
| Disposal reason | — |

Maintain this log for each standard to ensure traceability from receipt to disposal. Solarbio recommends a two-person verification system for initial log entries and for any re-certification results. Archived logs must be retained for at least 5 years after disposal.

## 9. Comparison: Solarbio vs Pharmacopoeial Reference Standards

| Criterion | Solarbio Analytical Standard | USP RS | EP CRS | ChP CRS |
|---|---|---|---|---|
| Purity | ≥99.0% (HPLC) | ≥99.5% (typically) | ≥99.5% (typically) | ≥99.0% |
| Uncertainty reported | Yes (k=2, 95% CI) | Yes (target uncertainty) | Yes (expanded uncertainty) | Sometimes |
| COA format | Full analytical dataset | Monograph compliance | Monograph compliance | Monograph compliance |
| Batch size | Small-to-medium (0.1–10 g) | Large (multi-gram) | Medium | Medium |
| Lead time | Ships within 1–3 business days | 2–6 weeks (backorder possible) | 4–8 weeks (import) | 2–4 weeks |
| Certificates | Digital PDF (free download) | Digital PDF | Paper + digital | Digital PDF |
| Price per vial (100 mg) | $25–$80 | $150–$600 | €150–€500 | ¥200–¥800 |
| Labeling | Detailed: purity, lot, MW, CAS, storage, barcode | USP logo, lot, CAS, MW | EP logo, lot, CAS | ChP logo, lot number |
| Primary use | Research, method development, routine QC | Pharmacopoeial compendial testing | Pharmacopoeial compendial testing | Chinese pharmacopoeia testing |
| Traceability | In-house primary standards, SRM cross-check | Certified against primary USP RS | Certified against primary EP CRS | Certified against primary ChP CRS |

**When to choose Solarbio**: For method development, routine calibration, and training. For compendial release testing submitted to a regulatory authority, the relevant pharmacopoeial standard (USP/EP/ChP) is required. Solarbio standards are fully suitable for in-process testing, stability studies, R&D, and QC where compendial conformance is not mandatory.

## 10. Quality Specifications

| Parameter | Analytical Grade | Pharmacopoeia Grade | Research Grade |
|---|---|---|---|
| Purity (HPLC area %) | ≥ 99.0% | Meets compendial requirement | ≥ 95.0% |
| Uncertainty of purity | ± 0.5% (k=2) | N/A (pass/fail) | N/A |
| Moisture (Karl Fischer) | < 0.5% | < 0.5% | < 1.0% |
| Residual solvents | ICH Q3C compliant | Monograph-specified | < 5000 ppm |
| Heavy metals (ICP-MS) | < 5 ppm | < 10 ppm | < 20 ppm |
| Identity confirmation | NMR (¹H, ¹³C), MS, IR, melting point | IR, melting point, specific rotation (if applicable) | HPLC retention match, ¹H NMR |
| Certificate type | Full COA with expiry | Monograph-compliant COA | HPLC + NMR summary |
| Shelf life | 36 months | 24–36 months | 24 months |
| Storage | 2–8°C or as labeled | 2–8°C or as labeled | −20°C |

## 11. Related Products

- [▶ Biochemical Assay Kits](../assay-kits/index.md)
- [▶ Food Safety Testing Applications](../applications/food-safety-testing.md)
- [▶ Quality & Compliance](../quality/index.md)
- [▶ Certificate of Analysis Guide](../quality/coa-guide.md)
- [▶ Small Molecule Compounds](small-molecules.md)

---

*[solarbio.store](https://solarbio.store)*
