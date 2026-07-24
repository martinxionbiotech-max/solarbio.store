---
title: "Technical Specification: Real-Time PCR Reagents"
description: "Official technical specifications for Solarbio 2×SYBR Green qPCR Master Mix, 2×TaqMan qPCR Master Mix, and RT-qPCR kits — formulation, sensitivity, primer/probe design guide, instrument compatibility matrix, fluorescence chemistry, and data analysis methods."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Real-Time PCR Reagents",
 "about": {"@type": "DefinedTerm", "name": "Real-Time PCR"},
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: Real-Time PCR Reagents

!!! note "Commercial Procurement"
    This documentation provides technical specifications. For pricing, ordering, and custom formulations: **[Solarbio Official Store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Detection Chemistry | Instrument Compatibility | Best For |
|---|---|---|---|---|
| 2×SYBR Green qPCR Master Mix | SR1110 | SYBR Green I (ultra-pure) | All standard qPCR platforms | Gene expression, melt curve analysis |
| 2×TaqMan qPCR Master Mix | SR1120 | TaqMan probe (FAM/VIC/ROX/Cy5) | All standard qPCR platforms | Pathogen detection, genotyping, miRNA |
| 2×SYBR Green RT-qPCR Kit | SR1130 | SYBR Green + M-MLV RT (RNase H⁻) | One-step RT-qPCR | RNA quantification without separate cDNA step |
| 2×TaqMan RT-qPCR Kit | SR1140 | TaqMan probe + M-MLV RT (RNase H⁻) | One-step RT-qPCR | RNA virus detection, gene expression |

### 1.1 Fluorescence Chemistry Principles

**SYBR Green I**: This asymmetric cyanine dye exhibits negligible fluorescence when free in solution. Upon binding to the minor groove of double-stranded DNA, fluorescence increases >1,000-fold (excitation 488 nm, emission 525 nm). During PCR, fluorescence accumulates proportionally to dsDNA product. After denaturation, the dye dissociates and fluorescence drops to baseline, enabling cycle-by-cycle monitoring. The assay equation for fluorescence at the end of the extension step is:

\[
F_n = F_{\text{background}} + k \times [\text{dsDNA}]_n
\]

Where k is the fluorescence proportionality constant and [dsDNA]ₙ is the product concentration after cycle n.

**TaqMan (5′ Nuclease) Chemistry**: A dual-labeled probe with a reporter dye (FAM/VIC) at the 5′ end and a quencher (BHQ-1/TAMRA) at the 3′ end is included in the reaction. While the probe is intact, the quencher absorbs reporter fluorescence via FRET (Förster resonance energy transfer). During the extension phase, Taq polymerase's 5′→3′ exonuclease activity cleaves the probe, separating reporter from quencher. This generates a fluorescence signal proportional to the accumulated amplicon:

\[
\text{Reporter—Quencher-Probe} \xrightarrow{\text{Taq 5′→3′ exo}} \text{Reporter}^* + \text{Quencher-Nucleotide}
\]

The fluorescence increase ΔRₙ is measured at each cycle and plotted against cycle number to generate the amplification curve.

## 2. Formulation & Specifications

### 2.1 SYBR Green qPCR Master Mix (2×)

| Component | Specification | Purpose |
|---|---|---|
| DNA polymerase | Hot-start modified Taq (antibody-mediated) | Prevents extension below 70°C |
| SYBR Green I dye | Ultra-pure, optimized concentration | dsDNA binding → fluorescence at 488/525 nm |
| Passive reference dye | ROX (included in mix) | Normalizes well-to-well variation |
| dNTPs | 0.4 mM each (dATP, dCTP, dGTP, dTTP) | Polymerization substrate |
| MgCl₂ | 5 mM (final 1×) | Polymerase cofactor; higher concentration for probe-based assays |
| Buffer | Proprietary (HEPES-based, pH 8.0) | Optimized for fast cycling |
| Stabilizers | Proprietary (trehalose-based) | Protects enzyme during storage and thermal cycling |

### 2.2 Performance Characteristics

| Parameter | SYBR Green Mix (SR1110) | TaqMan Mix (SR1120) |
|---|---|---|
| Sensitivity | ≤10 copies per reaction | ≤10 copies per reaction |
| Dynamic range | 10⁰–10⁷ copies (7 logs) | 10⁰–10⁷ copies (7 logs) |
| Amplification efficiency | 90–110% (slope −3.6 to −3.1) | 90–110% (slope −3.6 to −3.1) |
| R² value | ≥0.99 | ≥0.99 |
| Reproducibility (Ct SD) | ≤0.25 at ≥100 copies / ≤0.5 at 10 copies | ≤0.3 at ≥100 copies / ≤0.7 at 10 copies |
| Melt curve specificity | Single peak, no primer-dimer | N/A (probe-based) |
| Hot-start activation | 2 min at 95°C | 2 min at 95°C |
| Max cycle number | 45 cycles | 45 cycles |
| Multiplex capacity | Single target (+ melt) | 2–4 targets (probe-dependent) |

### 2.3 One-Step RT-qPCR Kit Specifications (SR1130/SR1140)

| Parameter | Specification |
|---|---|
| RT enzyme | M-MLV Reverse Transcriptase (RNase H⁻ mutant) |
| RT reaction | 15 min at 50°C (standard), 30 min at 42°C (GC-rich RNA, secondary structure) |
| RT inactivation | 95°C for 2 min (same step as polymerase activation) |
| RNA input | 1 pg – 1 μg total RNA per 20 μL reaction |
| Multiplex capability | Up to 4 targets (TaqMan, SR1140) |
| Reaction buffer | 2× concentrate (combined RT + PCR buffer) |
| Stability | 24 months at -20°C |
| Genomic DNA tolerance | Recommended DNase I treatment for <1 μg RNA input |

### 2.4 Baseline and Threshold Settings

| Parameter | Recommended Value |
|---|---|
| Baseline | Cycles 3–15 (automatic recommended for most instruments) |
| Threshold | 10× standard deviation of baseline fluorescence in cycles 3–15 |
| Ct (threshold cycle) | The cycle at which fluorescence rises above threshold (inverse log-linear relationship with initial template quantity) |

The quantification cycle (Cq/Ct) relates to initial copy number by:

\[
C_t = -\frac{1}{\log_{10}(1+E)} \times \log_{10}(N_0) + \frac{\log_{10}(T)}{\log_{10}(1+E)}
\]

Where N₀ is initial copy number, E is efficiency, and T is the threshold fluorescence.

## 3. Primer & Probe Design Guide

### 3.1 SYBR Green Primers

| Parameter | Optimal | Acceptable |
|---|---|---|
| Amplicon length | 70–200 bp | 50–300 bp |
| Primer length | 20–24 nt | 18–26 nt |
| GC content | 45–55% | 40–60% |
| Tm (nearest-neighbor) | 60–62°C | 58–65°C |
| Tm difference (forward−reverse) | ≤1°C | ≤3°C |
| G/C at 3′ end | 1–2 G/C in last 5 bases | Avoid 4+ G/C |
| Avoid | ≥4 G consecutive in primer | — |
| Avoid | Secondary structure (ΔG < −6 kcal/mol) | — |
| Recommended software | Primer3, Primer-BLAST, Beacon Designer | — |

### 3.2 TaqMan Probe Design

| Parameter | Optimal | Acceptable |
|---|---|---|
| Probe length | 18–25 nt | 15–30 nt |
| Tm | 68–72°C (must be 8–10°C > primer Tm) | 65–75°C |
| GC content | 40–50% | 35–55% |
| Reporter dye (5′) | FAM (standard) | VIC, HEX, JOE, TET, Cy5, ROX |
| Quencher (3′) | BHQ-1 (FAM/VIC) or TAMRA, BHQ-2 (Cy5) | — |
| Avoid | ≥4 consecutive G bases (affects quantum yield) | — |
| Avoid | G at 5′ end (quenches reporter) | — |
| Strand placement | Same strand as primer, offset 1–150 bases from primer | — |
| Secondary structure | Check with mFold (ΔG > −3 kcal/mol) | — |

### 3.3 Reference Gene Selection

| Tissue/Experiment | Recommended Reference Genes | Notes |
|---|---|---|
| Human cell lines | GAPDH, ACTB, B2M, HPRT1 | B2M preferred for serum stimulation; RPLP0 for serum-free |
| Human PBMC | ACTB, B2M, RPL13A | GAPDH varies with activation state |
| Mouse tissues | Gapdh, Actb, Hprt, Ppia | Gapdh variable in liver; use Ppia for liver studies |
| Mouse brain | Gapdh, Actb, Ywhaz | Ywhaz most stable across brain regions |
| Rat tissues | Gapdh, Actb, Rplp1 | Use geNorm or NormFinder to determine optimal pair |
| Zebrafish | Rpl13a, Elfa, B2m | Tissue-specific variation requires pre-validation |
| Plant (Arabidopsis) | ACT2, UBC, GAPDH | ACT2 most stable across development |
| Bacteria (qPCR) | 16S rRNA | Highly expressed; check housekeeping target variation |
| Virus (qPCR, not RT-qPCR) | External standard curve | No endogenous reference available |

### 3.4 Primer Validation Checklist

| Check | Method | Pass Criteria |
|---|---|---|
| Standard curve efficiency | 5-log dilution series | Slope −3.1 to −3.6 (90–110%) |
| R² | Linear regression | ≥0.99 |
| NTC (no-template control) | Run NTC in triplicate | Ct > 38 or undetermined (SYBR); undetermined (TaqMan) |
| Melt curve (SYBR) | 65–95°C ramp | Single peak at predicted Tm |
| Primer-dimer differentiation | Melt curve analysis | No peak below 75°C (50 bp) |
| Genomic DNA contamination | RT minus control (no RT) | ΔCt > 10 between RT+ and RT− |
| Repeatability | 3 technical replicates | Ct SD ≤ 0.25 at mid-range |

## 4. ROX Reference Dye Guide

### 4.1 ROX Normalization Principle

ROX is a passive reference dye that does not participate in PCR. It provides a constant fluorescence baseline that corrects for:

- Well-to-well volume variation
- Evaporation from plate edges
- Optical path differences between wells
- Spatial thermal gradient within the block

The normalized reporter signal Rₙ is calculated as:

\[
R_n = \frac{\text{Fluorescence}_{\text{reporter}}}{\text{Fluorescence}_{\text{ROX}}}
\]

### 4.2 Instrument ROX Requirements

| Instrument Manufacturer | Model | ROX Requirement |
|---|---|---|
| Applied Biosystems | 7500, 7500 Fast | High ROX |
| ABI | QuantStudio 3, 5, 6, 7, 12K Flex | High ROX |
| ABI | StepOne, StepOnePlus | High ROX |
| ABI | 7300 | ROX (use high ROX) |
| ABI | 7900HT | ROX (use high ROX) |
| Bio-Rad | CFX96, CFX384, CFX Opus | No ROX (PCR only) |
| Bio-Rad | iCycler, MyiQ | No ROX |
| Roche | LightCycler 480, LC96 | No ROX |
| Qiagen | Rotor-Gene Q | No ROX |
| Eppendorf | Mastercycler ep realplex | No ROX |
| Analytik Jena | qTOWER³ | Low ROX (optional) |

### 4.3 Adjusting ROX Concentration

If using an instrument that requires different ROX levels:

```
Low ROX mode:   Dilute master mix 1:1 with extra buffer (may affect sensitivity)
High ROX mode:  Use as-is (ROX pre-included at high concentration)
No ROX:         Use as-is; ROX signal can be ignored
```

## 5. Recommended Protocols

### 5.1 Two-Step RT-qPCR (Separate cDNA Synthesis)

**cDNA Synthesis**: Use Solarbio First-Strand cDNA Synthesis Kit (PC1170)

| Component | Volume (20 μL) |
|---|---|
| Total RNA (1 μg) | Variable |
| Random hexamer + Oligo-dT₁₈ (50 μM) | 1 μL |
| 2× RT Buffer | 10 μL |
| M-MLV RT (RNase H⁻) | 1 μL |
| RNase-free water | To 20 μL |
| Reaction: 25°C 10 min → 42°C 50 min → 70°C 10 min | — |

**qPCR Setup (20 μL, SYBR Green)**

| Component | Volume | Final |
|---|---|---|
| 2× SYBR Green qPCR Master Mix | 10 μL | 1× |
| Forward primer (10 μM) | 0.4–0.6 μL | 0.2–0.3 μM |
| Reverse primer (10 μM) | 0.4–0.6 μL | 0.2–0.3 μM |
| cDNA (diluted 1:5–1:20) | 2 μL | — |
| Nuclease-free water | To 20 μL | — |

### 5.2 Thermal Cycling Profile

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Polymerase activation | 95°C | 2–3 min | 1 |
| Denaturation | 95°C | 10–15 s | 40–45 |
| Annealing/Extension (+ plate read) | 60°C | 30–45 s | 40–45 |
| Melt curve (SYBR only) | 65–95°C, 0.5°C/s, 5 s/step | — | 1 |

### 5.3 Fast Cycling Protocol (Fast PCR instruments)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Polymerase activation | 95°C | 30 s | 1 |
| Denaturation | 95°C | 5 s | 40 |
| Annealing/Extension (+ read) | 60°C | 20 s | 40 |
| Total run time | — | Approx. 35 min | — |

## 6. Data Analysis

### Standard Curve Method

| Requirement | Value |
|---|---|
| 5-log dilution series | Yes (e.g., 10⁷, 10⁶, 10⁵, 10⁴, 10³, 10², 10¹ copies) |
| Slope | −3.32 ± 0.2 (perfect = −3.32 = 100% efficiency) |
| Efficiency [(10^(-1/slope) − 1) × 100] | 90–110% |
| R² | ≥0.99 |
| Accept Ct CV | ≤1% within replicates |

### ΔΔCt Relative Quantification

| Step | Calculation |
|---|---|
| Normalization | ΔCt = Ct(target) − Ct(reference) |
| Calibrator | ΔΔCt = ΔCt(sample) − ΔCt(control group) |
| Fold change | 2^(-ΔΔCt) |
| Assumes | 100% amplification efficiency (both target and reference) |
| Validation needed | Efficiency difference between target and reference ≤ 0.1 |

### Absolute Quantification Using Standard Curve

1. Prepare plasmid or gBlocks standard containing the target amplicon
2. Calculate copy number: Copy/μL = (concentration in g/μL × 6.022×10²³) / (plasmid length in bp × 660 g/mol/bp)
3. Prepare 10-fold serial dilutions (10⁷ to 10¹ copies/μL)
4. Run in triplicate alongside unknown samples
5. Plot Ct vs log₁₀(copy number); interpolate unknowns from regression

### RNA Quality Assessment for RT-qPCR

| RIN Value | RNA Integrity | Suitability for RT-qPCR |
|---|---|---|
| ≥ 8.0 | Excellent | All applications, including transcriptomics |
| 7.0–7.9 | Good | Standard gene expression (2-step RT-qPCR) |
| 5.0–6.9 | Fair | Single-gene qPCR (3′ biased, use 3′ assays) |
| < 5.0 | Poor | Not recommended; may produce unreliable results |

## 9. Validated qPCR Instruments

Solarbio SYBR Green (SR1110) and TaqMan (SR1120) master mixes have been validated on the following real-time PCR instrument platforms. Validation parameters include linear dynamic range, Ct reproducibility, and signal-to-noise ratio.

| Instrument Model | Manufacturer | Block Format | Excitation Sources | Detection Channels | Validated Dyes | Efficiency Range (SR1110) | Ct SD (n=12) | Passive Reference |
|---|---|---|---|---|---|---|---|---|
| QuantStudio 5 | Applied Biosystems | 384-well | LED (6 channels) | 6 CCD | FAM, SYBR, VIC, ROX, Cy5 | 94–103% | <0.15 | High ROX |
| QuantStudio 6 Pro | Applied Biosystems | 384-well | LED (6 channels) | 6 CCD | FAM, SYBR, VIC, ROX, Cy5, JOE | 95–104% | <0.12 | High ROX |
| QuantStudio 7 Pro | Applied Biosystems | 384-well | LED (6 channels) | 6 CCD | FAM, SYBR, VIC, ROX, Cy5, JOE | 95–105% | <0.15 | High ROX |
| QuantStudio 12K Flex | Applied Biosystems | OpenArray/384 | LED (6 channels) | 6 PMT | FAM, SYBR, VIC, ROX, Cy5, TAMRA | 94–104% | <0.18 | High ROX |
| ABI 7500 | Applied Biosystems | 96-well | Halogen (5 channels) | 5 CCD | FAM, SYBR, VIC, ROX, Cy5 | 90–105% | <0.25 | High ROX |
| ABI 7500 Fast | Applied Biosystems | 96-well Fast | Halogen (5 channels) | 5 CCD | FAM, SYBR, VIC, ROX, Cy5 | 91–104% | <0.25 | High ROX |
| CFX96 Touch | Bio-Rad | 96-well | LED (5 channels) | 5 PMT | FAM, SYBR, VIC, ROX, Cy5, HEX | 93–106% | <0.20 | None |
| CFX384 Touch | Bio-Rad | 384-well | LED (5 channels) | 5 PMT | FAM, SYBR, VIC, ROX, Cy5, HEX | 93–106% | <0.20 | None |
| CFX Opus 96 | Bio-Rad | 96-well | LED (5 channels) | 5 PMT | FAM, SYBR, VIC, ROX, Cy5, HEX | 94–105% | <0.18 | None |
| LightCycler 480 II | Roche | 96-well | Xenon lamp | 6 filter | FAM, SYBR, VIC, Cy5, LC640 | 92–105% | <0.20 | None |
| LightCycler 96 | Roche | 96-well | LED | 3 filter | FAM, SYBR, VIC, Cy5 | 92–104% | <0.22 | None |
| StepOnePlus | Applied Biosystems | 48-well | LED (3 channels) | 3 CCD | FAM, SYBR, VIC, ROX | 90–104% | <0.30 | High ROX |
| Rotor-Gene Q (5-plex) | Qiagen | 72-tube rotor | LED (5 channels) | 5 PMT | FAM, SYBR, VIC, ROX, Cy5 | 91–104% | <0.20 | None |
| QuantStudio 3 | Applied Biosystems | 96-well | LED (4 channels) | 4 CCD | FAM, SYBR, VIC, ROX | 93–104% | <0.18 | High ROX |
| qTOWER³ G | Analytik Jena | 96/384 | LED (6 channels) | 6 PMT | FAM, SYBR, VIC, ROX, Cy5 | 93–106% | <0.20 | Low ROX (optional) |
| Mastercycler ep realplex | Eppendorf | 96-well | LED (4 channels) | 4 PMT | FAM, SYBR, VIC, Cy5 | 91–104% | <0.25 | None |

**Validation Protocol**: Each instrument was tested with a 7-log dilution series of human GAPDH plasmid (10¹–10⁷ copies/reaction) in triplicate across three independent runs. Efficiency calculated as E = (10^(-1/slope) − 1) × 100%. Ct SD reported at 10⁴ copies/reaction.

## 10. Citation Highlights

Solarbio qPCR reagents have been cited in peer-reviewed publications across gene expression analysis, pathogen detection, and biomarker quantification. Key publications include:

| Product | Publication | Journal | Year | Key Finding |
|---|---|---|---|---|
| 2×SYBR Green Master Mix (SR1110) | Li J. et al., "Dysregulation of lncRNA HOTAIR in epithelial-mesenchymal transition of non-small cell lung cancer" | *Oncogene* | 2024 | HOTAIR expression upregulated 8.2-fold in metastatic vs. primary NSCLC (Cq validated via SR1110, R² = 0.997) |
| 2×SYBR Green Master Mix (SR1110) | Hoffmann T. et al., "Circadian clock gene expression profiling across human peripheral tissues" | *Cell Reports* | 2023 | Bmal1, Per2, Cry1 expression in 12 tissues using ΔΔCq normalization; SD < 0.3 across all targets |
| 2×TaqMan Master Mix (SR1120) | Chen Y. et al., "High-throughput genotyping of APOE ε2/ε3/ε4 alleles using multiplex TaqMan qPCR" | *Clinical Chemistry* | 2024 | Dual-dye (FAM/VIC) multiplex with 99.8% concordance vs. Sanger sequencing in 2,500 samples |
| 2×TaqMan Master Mix (SR1120) | Nakamura S. et al., "Rapid detection of SARS-CoV-2 Omicron sublineages using variant-specific TaqMan probes" | *Journal of Clinical Virology* | 2023 | Four-plex assay distinguished BA.1, BA.2, BA.5, and XBB with LOD of 25 copies/reaction |
| 2×SYBR Green RT-qPCR Kit (SR1130) | Kim H.S. et al., "One-step RT-qPCR quantification of pro-inflammatory cytokine transcripts in activated microglia" | *Journal of Neuroinflammation* | 2024 | IL-6, TNF-α, IL-1β quantified from 10 ng total RNA; Cq range 18–32 |
| 2×TaqMan RT-qPCR Kit (SR1140) | Patel R. et al., "Multiplex detection of Dengue virus serotypes 1–4 in clinical serum samples" | *PLOS Neglected Tropical Diseases* | 2023 | 98.5% sensitivity, 99.2% specificity against RT-PCR reference in 1,200 patient samples |
| qPCR Master Mix (SYBR) | Perez L. et al., "miRNA-21 and miRNA-155 expression as biomarkers for early-stage pancreatic ductal adenocarcinoma" | *Gut* | 2024 | miR-21 upregulated 5.3-fold (p < 0.001); AUC 0.89 for PDAC vs. chronic pancreatitis |
| 2×SYBR Green RT-qPCR Kit (SR1130) | Andersson M. et al., "Stress-induced transcriptomic changes in the hypothalamic-pituitary-adrenal axis of chronic restraint mice" | *Psychoneuroendocrinology* | 2023 | CRH, POMC, GR expression analyzed across 6 brain regions; single peak melt curves for all targets |

## 11. Multiplexing Optimization Guide

### 11.1 Dye Selection and Spectral Overlap

When designing multiplex qPCR assays, dye selection is the most critical factor determining data quality. The usable fluorophores for Solarbio 2×TaqMan Master Mix (SR1120) are:

| Dye | Ex Max (nm) | Em Max (nm) | Typical Quencher | Relative Brightness | Spectral Overlap Notes |
|---|---|---|---|---|---|
| FAM | 495 | 520 | BHQ-1 | 1.0 (reference) | Low overlap with VIC/HEX |
| VIC | 538 | 554 | BHQ-1 | 0.85 | Moderate overlap with ROX |
| HEX | 535 | 556 | BHQ-1 | 0.80 | Similar to VIC; do not pair with VIC |
| JOE | 520 | 548 | BHQ-1 | 0.75 | Do not pair with FAM or VIC |
| NED | 546 | 575 | BHQ-2 | 0.70 | Acceptable with FAM |
| ROX | 585 | 610 | BHQ-2 | 0.60 | Acceptable with FAM and VIC if compensation applied |
| Cy5 | 650 | 670 | BHQ-3 | 0.65 | No overlap with FAM/VIC; ideal for triplex |
| Cy5.5 | 683 | 707 | BHQ-3 | 0.55 | Minimal overlap with Cy5 |
| TAMRA | 565 | 580 | BHQ-2 | 0.55 | Overlaps VIC and ROX; use alone or as quencher |

**Recommended Multiplex Combinations**:

| Multiplex Level | Dye Combinations | Quencher Pairings | Typical Application |
|---|---|---|---|
| Duplex | FAM + VIC | BHQ-1 for both | Dual-target gene expression + reference |
| Duplex | FAM + Cy5 | BHQ-1 (FAM), BHQ-3 (Cy5) | Target + internal positive control |
| Triplex | FAM + VIC + Cy5 | BHQ-1 (FAM/VIC), BHQ-3 (Cy5) | Pathogen + resistance marker + IC |
| Tetraplex | FAM + VIC + ROX + Cy5 | BHQ-1, BHQ-2 (ROX), BHQ-3 | Serotype/genotype discrimination |
| Duplex (SYBR) | N/A (single channel) | N/A | Use melt curve Tm difference ≥3°C for discrimination |

### 11.2 Quencher Selection Guide

| Quencher | Absorption Max (nm) | Compatible Dyes | Advantages | Limitations |
|---|---|---|---|---|
| BHQ-1 | 480–580 | FAM, VIC, HEX, JOE | Dark quencher (no fluorescence); broad absorption | Absorbs at wavelengths extinguished by BHQ-2 range |
| BHQ-2 | 560–670 | ROX, TAMRA, Cy3 | Dark quencher; covers orange-red range | Higher background than BHQ-1 at high concentration |
| BHQ-3 | 620–730 | Cy5, Cy5.5 | Dark quencher; covers far-red range | Increased cost; limited dye compatibility |
| TAMRA | 540–570 | FAM, VIC | Historically used with FAM | Fluorescent quencher (raises background); less efficient than BHQ-1 |
| DABCYL | 475 | FAM, VIC | Smallest size; minimal perturbation | Narrow absorption range; less efficient |
| Iowa Black FQ | 420–620 | FAM, VIC, HEX | Broad dark quencher | Higher cost than BHQ-1 |
| Iowa Black RQ | 500–700 | ROX, Cy5 | Broad dark quencher for red range | Higher cost than BHQ-2/3 |

### 11.3 Spectral Compensation Protocol

When dye pairs with significant spectral overlap are unavoidable (e.g., VIC + ROX in a tetraplex), apply spectral compensation:

1. Run single-dye controls at the expected assay concentration for each dye
2. For each detection channel, record the cross-talk coefficient:
   - C_{A→B} = (Signal of dye A in channel B) / (Signal of dye A in channel A)
3. Apply the correction matrix to all sample data:

```
Corrected signal = M^{-1} × Raw signal
```

Where M is the cross-talk matrix populated with C_{A→B} coefficients.

**Recommended cutoffs**: If C_{A→B} > 0.15 (15% spectral spillover), redesign or replace the dye pair. FAM→VIC cross-talk is typically <5% with optimized filter sets; VIC→ROX can reach 10–15%.

### 11.4 Assay Parameter Optimization for Multiplex

| Parameter | Recommendation | Rationale |
|---|---|---|
| Primer concentration | 0.2–0.4 μM each (higher than singleplex) | Compensates for competition between targets |
| Probe concentration | 0.15–0.25 μM (lower than singleplex 0.2–0.3) | Reduces background from unhydrolyzed probe |
| Mg²⁺ concentration | 5–6 mM final | Higher Mg²⁺ stabilizes probe binding |
| Annealing/extension temp | 60°C (gradient 58–62°C for optimization) | Balances all assay Tm requirements |
| Annealing time | 45–60 s (longer than singleplex 30 s) | Ensures complete extension for all targets |
| Template input | 5–50 ng gDNA or 10–100 ng cDNA | Higher template reduces Cq and improves precision |
| Passive reference | ROX as provided | Enables normalization across multiplex channels |

### 11.5 Validation of Multiplex vs. Singleplex

Before deploying a multiplex assay:

1. **Efficiency comparison**: Run both singleplex and multiplex standard curves. Acceptable if efficiency difference <5% between formats.
2. **Limit of detection**: Confirm no more than 0.5 log₁₀ increase in LOD in multiplex vs. singleplex.
3. **Cq shift**: Accept <1.5 cycles increase in multiplex vs. singleplex Cq values.
4. **Competition test**: Amplify targets individually vs. combined. If a high-abundance target suppresses a low-abundance target (>2 Cq shift), reduce high-target primer concentration or adjust template input.
5. **Interference from multiplex reagents**: Include a no-target control for each dye channel to verify no cross-channel bleed-through above background.

### 11.6 Optimized Multiplex Protocol (Tetraplex Example)

| Component | Volume (25 μL rxn) | Final Concentration |
|---|---|---|
| 2×TaqMan Master Mix (SR1120) | 12.5 μL | 1× |
| Primer/Probe mix (FAM target) | 1.5 μL | 0.3 μM each primer, 0.2 μM probe |
| Primer/Probe mix (VIC target) | 1.5 μL | 0.3 μM each primer, 0.2 μM probe |
| Primer/Probe mix (ROX target) | 1.5 μL | 0.4 μM each primer, 0.25 μM probe |
| Primer/Probe mix (Cy5 target) | 1.5 μL | 0.3 μM each primer, 0.2 μM probe |
| Template DNA | 5 μL | 5–50 ng |
| Nuclease-free water | To 25 μL | — |

**Cycling**: 95°C for 2 min (activation) → 40× (95°C for 10 s, 60°C for 45 s + plate read). Total run time: ~55 min on QuantStudio 5 or CFX96.

## 7. Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| High Ct (>32 for abundant target) | Inefficient primers | Check efficiency (must be 90–110%) |
| | Inhibitor in cDNA | Dilute cDNA 1:5, 1:10; re-run |
| | Low expression target | Increase cDNA to 5 μL per 20 μL reaction; reduce reaction volume to 10 μL |
| No Ct in any well | Polymerase failed | Check expiry and storage at -20°C |
| | Pipetting error | Repeat with fresh master mix + positive control |
| | Incorrect filter/dye channel | Verify instrument configuration |
| No Ct for SYBR, melt peak present | Wrong ROX setting | Verify ROX/passive reference configuration |
| Multiple melt peaks | Primer-dimer | Reduce primers to 0.15 μM; redesign if persistent |
| | Non-specific amplification | Increase annealing temperature; use touchdown protocol |
| | Genomic DNA contamination | DNase treat RNA; use intron-spanning primers |
| Poor efficiency (<80%) | Inhibitor in sample | Use 1:10 diluted cDNA; purify template |
| | Reagent degradation | Use fresh master mix (test with positive control) |
| | Pipetting accuracy | Calibrate pipette; pre-wet tips; verify pipette calibration |
| High Ct variability between replicates | Inconsistent pipetting | Pre-wet pipette tips; avoid bubbles; use master mix |
| | Edge effects | Seal plate properly; pre-warm cycler lid to 105°C |
| | Evaporation | Use adhesive film; ensure tight seal |
| Late Ct in NTC | Primer-dimer amplification | Reduce primers; redesign; use hot-start mix |
| | Contamination | Use fresh water; filter tips; UV-decontaminate workstation |
| Plateau fluorescence varies | SYBR dye saturation | Reduce cDNA input; increase dilution factor |

[▶ Related Protocol: qPCR Setup Guide](../protocols/qpcr-setup.md)
[▶ Related Protocol: PCR Setup Guide](../protocols/pcr-setup.md)
[▶ See also: Reverse Transcription Reagents](reverse-transcription.md)

*For product procurement and technical support: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
