---
title: "qPCR Setup Protocol"
description: "Official Solarbio protocol for real-time quantitative PCR — SYBR Green and TaqMan chemistries, primer/probe design guidelines, standard curve preparation, thermal cycling profiles, ROX calibration, and data analysis including ΔΔCt method."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "qPCR Setup Protocol",
 "description": "Official Solarbio protocol for real-time quantitative PCR — SYBR Green and TaqMan chemistries, primer and probe design, standard curve preparation, thermal cycling, and ΔΔCt data analysis.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# qPCR Setup Protocol

Using Solarbio 2×SYBR Green qPCR Master Mix (SR1110) or 2×TaqMan qPCR Master Mix (SR1120). This protocol covers both two-step RT-qPCR (cDNA template) and direct DNA qPCR.

## Equipment and Reagents Checklist

| Item | Recommended Product | Notes |
|---|---|---|
| 2×SYBR Green qPCR Master Mix | SR1110 (Solarbio) | Includes ROX; verify instrument ROX requirements |
| 2×TaqMan qPCR Master Mix | SR1120 (Solarbio) | Includes ROX; for probe-based assays |
| Nuclease-free water | R1600 (Solarbio) | DEPC-treated or ultra-pure |
| cDNA template | PC1170-generated (Solarbio) | Diluted 1:5–1:20 in nuclease-free water |
| qPCR tubes/plate | 0.1 or 0.2 mL thin-wall | White plates improve fluorescence detection |
| Optical seal | Transparent adhesive film | Ensure no bubbles over wells |
| Real-time PCR instrument | ABI 7500, Bio-Rad CFX96, Roche LC480, etc. | — |
| Pipettes (0.5–10 μL, 10–100 μL) | Calibrated ±2% accuracy | Pre-wet tips before aspirating master mix |

## Primer and Probe Design

### SYBR Green Primers

| Parameter | Recommendation | Verification Method |
|---|---|---|
| Amplicon length | 70–200 bp | Check by gel or melt curve |
| Primer length | 18–24 nt | In silico analysis |
| GC content | 40–60% | OligoAnalyzer / Primer3 |
| Tm | 58–62°C | Nearest-neighbor calculation |
| Tm difference (pair) | ≤2°C | Compare forward/reverse |
| 3′ stability | ≤3 G/C in last 5 bases | Manual check |
| Avoid | ≥4 consecutive G residues | In silico |
| Avoid | Primer-primer complementarity (3′ end) | Check with AutoDimer or Primer-BLAST |

### TaqMan Probe

| Parameter | Recommendation |
|---|---|
| Probe length | 18–25 nt |
| Primary Tm | 68–70°C (10°C above primers) |
| GC content | 40–50% |
| Reporter dye (5′) | FAM, VIC, or HEX |
| Quencher (3′) | BHQ-1 (FAM, VIC) or TAMRA |
| Avoid | ≥4 consecutive G bases (reduces fluorescence) |
| Avoid | 5′ end must not be G (quenches reporter) |
| Secondary structure | Check with mFold (ΔG > −3 kcal/mol) |
| Concentration (final) | 0.1–0.3 μM |

## Reaction Setup (20 μL)

### SYBR Green

| Component | Volume (20 μL) | Final Concentration | Notes |
|---|---|---|---|
| 2× SYBR Green qPCR Master Mix | 10 μL | 1× | Contains polymerase, dNTPs, SYBR, ROX |
| Forward primer (10 μM) | 0.4–0.6 μL | 0.2–0.3 μM | Start at 0.3 μM; optimize 0.1–0.5 μM |
| Reverse primer (10 μM) | 0.4–0.6 μL | 0.2–0.3 μM | Keep forward:reverse ratio 1:1 |
| Template cDNA | 1–2 μL | 1–100 ng | Dilute cDNA 1:5 to 1:20 |
| Nuclease-free water | To 20 μL | — | — |

**Important:** Prepare a master mix (all components except template) for reproducibility. Include ≥10% excess volume.

### TaqMan

| Component | Volume (20 μL) | Final Concentration |
|---|---|---|
| 2× TaqMan qPCR Master Mix | 10 μL | 1× |
| Forward primer (10 μM) | 0.4 μL | 0.2 μM |
| Reverse primer (10 μM) | 0.4 μL | 0.2 μM |
| Probe (10 μM) | 0.3 μL | 0.15 μM |
| Template cDNA | 2 μL | 1–100 ng |
| Nuclease-free water | To 20 μL | — |

### ROX Adjustment (if needed)

| Instrument Requirement | Action |
|---|---|
| High ROX (ABI 7500, QuantStudio) | Use SR1110/SR1120 as-is |
| No ROX (Bio-Rad CFX, Roche LC480) | Use as-is; ROX channel ignored |
| Passive reference not used | Disable ROX detection on instrument software |

## Experimental Controls

| Control Type | Composition | Expected Result | Purpose |
|---|---|---|---|
| NTC (no-template control) | Water instead of template | No Ct or Ct > 38 | Detects contamination |
| NRT (no-RT control) | RNA sample without RT enzyme | No Ct or Ct > 35 | Detects gDNA contamination |
| Positive control | Known template + validated primers | Ct consistent (±0.5) | Validates assay function |
| Inter-run calibrator | Aliquoted reference sample | Ct SD < 0.5 across runs | Normalizes between plates |

## Thermal Cycling

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Polymerase activation | 95°C | 2 min | 1 |
| Denaturation | 95°C | 10–15 s | 40 |
| Anneal/Extend (plate read) | 60°C | 30 s (45 s for TaqMan) | 40 |
| Melt curve (SYBR only) | 65–95°C, 0.5°C step | 5 s each step | 1 |

### Fast Cycling Protocol (compatible with SR1110/SR1120)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Polymerase activation | 95°C | 30 s | 1 |
| Denaturation | 95°C | 3–5 s | 40 |
| Anneal/Extend (read) | 60°C | 15–20 s | 40 |
| Total run time | — | ~35 min | — |

Note: Fast protocol requires a fast thermal cycler (ABI 7500 Fast, Bio-Rad CFX96).

## Standard Curve Preparation

### Protocol

1. Prepare a 10-fold dilution series of the standard (plasmid, gBlock, or validated cDNA) covering 5–7 logs
2. Typical dilution range: 10⁷ to 10¹ copies/μL (or 1:10 serial dilution of high-abundance cDNA)
3. Run each dilution in triplicate

### Standard Curve Layout Example

| Dilution | Expected Copies/Reaction | Expected Ct (100% efficiency) |
|---|---|---|
| 10⁷ | 2 × 10⁷ | ~15 |
| 10⁶ | 2 × 10⁶ | ~18.3 |
| 10⁵ | 2 × 10⁵ | ~21.7 |
| 10⁴ | 2 × 10⁴ | ~25 |
| 10³ | 2 × 10³ | ~28.3 |
| 10² | 2 × 10² | ~31.7 |
| 10¹ | 2 × 10¹ | ~35 |
| NTC | 0 | Undetermined |

## Data Analysis

### Standard Curve Method

| Parameter | Requirement |
|---|---|
| Efficiency | 90–110% (slope −3.6 to −3.1) |
| R² | ≥0.99 |
| Dynamic range | ≥5 logs |
| NTC (no-template control) | Ct > 38 or no amplification |
| Ct SD within replicates | ≤ 0.25 at > 100 copies |

### ΔΔCt Relative Quantification

| Formula | Description |
|---|---|
| ΔCt = Ct(target) − Ct(reference) | Normalization to housekeeping gene |
| ΔΔCt = ΔCt(sample) − ΔCt(calibrator) | Fold change relative to calibrator |
| Fold change = 2^(-ΔΔCt) | Assuming 100% amplification efficiency |

**Assumptions for ΔΔCt:**
- Both target and reference genes amplify with ≥ 95% efficiency
- Efficiency difference between target and reference ≤ 0.1
- Reference gene expression is stable across all experimental conditions

### Melting Curve Analysis (SYBR Green Only)

| Observation | Interpretation | Action |
|---|---|---|
| Single peak at predicted Tm | Specific amplification | OK |
| Double peak (Tm difference < 2°C) | Two close amplicons | Redesign primers; increase annealing Tm |
| Peak at 70–75°C | Primer-dimer | Reduce primers to 0.15 μM; redesign |
| Broad peak | Non-specific amplification | Run gel; increase annealing temperature |
| Peak at Tm > 85°C | Possible gDNA amplification | Use intron-spanning primers; DNase treat |

## Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| No amplification | Probe degraded | Re-order probe; check storage at -20°C dark |
| | No cDNA | Verify RT reaction success (run positive control) |
| | cDNA diluted too much | Reduce dilution; use neat cDNA |
| | Inhibitor present | Dilute cDNA 1:10 or 1:20 |
| High Ct (>35) | Low expression target | Increase cDNA to 100 ng per 20 μL reaction |
| | Inefficient primers | Check efficiency; redesign if < 90% |
| | Poor RNA quality | Check RIN; re-extract if RIN < 5 |
| | ROX/primer mismatch | Verify instrument ROX settings |
| Non-specific amplification | Primer dimer | Reduce primers to 0.1–0.2 μM; melt curve analysis |
| | gDNA contamination | DNase treat RNA; use intron-spanning primers |
| | Annealing temperature too low | Increase to 62°C; test gradient 58–65°C |
| Poor efficiency (< 80%) | Inhibitor in sample | Dilute cDNA 1:10; purify template |
| | ROX mismatch | Verify instrument ROX configuration |
| | Pipetting error | Calibrate pipettes; pre-wet tips; use master mix |
| High replicate variability | Inconsistent pipetting | Use larger volume (20 μL); pre-wet tips |
| | Evaporation at plate edges | Use adhesive seal; pre-warm lid to 105°C |
| | Uneven thermal block | Use center wells; avoid edge wells for critical samples |
| Late Ct in NTC | Contamination (amplicon or plasmid) | Replace water; UV work area; use fresh tips |
| | Primer-dimer amplified | Reduce primer concentration |
| Baseline drift | Background adjustment incorrect | Set baseline cycles 3–15 manually |

### 5.1 NTC Acceptance Criteria

| Chemistry | NTC Requirement | Action if Failed |
|---|---|---|
| SYBR Green | Ct > 38 or undetermined | Redesign primers; re-purify or replace reagents |
| TaqMan | Ct > 40 or undetermined | Check for probe degradation; check for target contamination |
| RT-qPCR | NRT Ct — ΔCt > 10 vs. RT+ | DNase treat RNA; redesign primers |

[▶ Related Protocol: PCR Setup Guide](../protocols/pcr-setup.md)
[▶ See also: Real-Time PCR Reagents Technical Spec](../molecular-biology/real-time-pcr.md)
[▶ See also: Reverse Transcription Reagents](../molecular-biology/reverse-transcription.md)

*[solarbio.store](https://solarbio.store)*
