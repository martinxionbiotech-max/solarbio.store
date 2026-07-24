---
title: "Technical Specification: Cell Proliferation Assay Kits"
description: "Technical specifications for Solarbio cell proliferation and cytotoxicity assay kits — CCK-8 (WST-8 tetrazolium reduction), MTT (formazan-based), and BrdU labeling methods. Full reaction mechanisms, linear detection ranges, sensitivity data, and protocol optimization for microplate-based viability and proliferation measurement."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Cell Proliferation Assay Kits",
 "description": "Technical specifications for Solarbio cell proliferation and cytotoxicity assay kits — CCK-8 (WST-8 tetrazolium reduction), MTT (formazan-based), and BrdU labeling methods. Full reaction mechanisms, linear detection ranges, sensitivity data, and protocol optimization for microplate-based viability and proliferation measurement.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Cell Proliferation Assay Kits

## 1. Product Range

Solarbio cell proliferation assays utilize tetrazolium salt reduction as a proxy for cellular metabolic activity. Viable cells with active NAD(P)H-dependent oxidoreductase enzymes reduce these salts to colored formazan products. The absorbance of the formazan product is directly proportional to viable cell number.

| Product | SKU | Detection Principle | Wavelength | Assays |
|---|---|---|---|---|
| CCK-8 Cell Counting Kit | CA1210 | WST-8 tetrazolium reduction | 450 nm (ref 630 nm) | 500 assays (10 mL) |
| MTT Cell Proliferation Assay Kit | CA1240 | MTT reduction to formazan | 570 nm (ref 630 nm) | 500 assays |
| BrdU Cell Proliferation ELISA Kit | CA1260 | BrdU incorporation, anti-BrdU-HRP detection | 450 nm | 200 assays |

## 2. Product Specifications

### CCK-8 Kit (CA1210)

**Principle:** CCK-8 contains WST-8 [2-(2-methoxy-4-nitrophenyl)-3-(4-nitrophenyl)-5-(2,4-disulfophenyl)-2H-tetrazolium, monosodium salt] and an electron mediator (1-methoxy PMS). Dehydrogenases in viable cells reduce NAD⁺ to NADH. NADH then reduces 1-methoxy PMS, which in turn reduces WST-8 to a water-soluble orange formazan product. Unlike MTT, the WST-8 formazan is water-soluble, eliminating the need for solubilization steps.

The reaction chain:

```
NAD(P)H  +  1-methoxy PMS (oxidized)  →  NAD(P)⁺  +  1-methoxy PMS (reduced)
                                                    ↓
WST-8 (tetrazolium)  +  1-methoxy PMS (reduced)  →  WST-8 formazan (orange, λmax 450 nm)
```

| Parameter | Specification |
|---|---|
| Cell number per well | 1×10³–1×10⁵ cells (96-well) |
| CCK-8 volume | 10 μL per 100 μL culture medium |
| Incubation time | 1–4 h at 37°C |
| Detection wavelength | 450 nm (reference 630 nm) |
| Linear detection range | 500–50,000 cells/well |
| Sensitivity | Detect ≥100 cells difference |
| Inter-assay CV | <8% |
| Intra-assay CV | <5% |
| Water solubility | Complete; no solubilization step needed |
| Cytotoxicity of reagent | Low (<5% at 4 h exposure) |
| Z′-factor (quality metric) | >0.7 |
| Storage (dark, 2–8°C) | 12 months |

### MTT Cell Proliferation Assay Kit (CA1240)

**Principle:** MTT (3-(4,5-dimethylthiazol-2-yl)-2,5-diphenyltetrazolium bromide) is a yellow tetrazolium salt that is reduced by NAD(P)H-dependent mitochondrial dehydrogenases (primarily succinate dehydrogenase) in viable cells to purple insoluble formazan crystals. The formazan must be solubilized with DMSO or acidified isopropanol before absorbance measurement.

The reaction:

```
MTT (yellow, λmax 440 nm)  +  NADH/H⁺  →  MTT formazan (purple, λmax 570 nm)
  (mitochondrial dehydrogenases)                    (insoluble in water)
```

| Parameter | Specification |
|---|---|
| Cell number per well | 2×10³–1×10⁵ cells (96-well) |
| MTT solution volume | 10 μL (5 mg/mL) per 100 μL culture medium |
| Incubation time | 2–4 h at 37°C |
| Solubilization solution | DMSO (100 μL/well) or acidified isopropanol |
| Detection wavelength | 570 nm (reference 630 nm) |
| Linear detection range | 1,000–50,000 cells/well |
| Sensitivity | Detect ≥500 cells difference |
| Inter-assay CV | <10% |
| Intra-assay CV | <6% |
| Storage (MTT, dark, 2–8°C) | 12 months |

### BrdU Cell Proliferation ELISA Kit (CA1260)

**Principle:** The thymidine analog 5-bromo-2′-deoxyuridine (BrdU) is incorporated into newly synthesized DNA during S-phase of the cell cycle. After fixation and denaturation, incorporated BrdU is detected by an anti-BrdU monoclonal antibody conjugated to HRP. TMB substrate generates a color signal proportional to the rate of DNA synthesis.

| Parameter | Specification |
|---|---|
| BrdU labeling time | 2–24 h (dependent on cell cycle length) |
| Detection limit | ≥5% S-phase cells |
| Linear detection range | 1,000–100,000 cells/well |
| Labeling density | 5×10³–5×10⁴ cells/well (96-well) |
| Inter-assay CV | <10% |
| Intra-assay CV | <7% |
| Total assay time | Approximately 5 h (excluding BrdU pulse) |
| Storage | 2–8°C, 12 months |

## 3. Method Comparison

| Parameter | CCK-8 | MTT | BrdU |
|---|---|---|---|
| Readout | Metabolic activity (NADH) | Metabolic activity (mitochondrial) | DNA synthesis |
| Solubilization needed | No | Yes (DMSO) | No |
| Cell washing needed | No | No | Yes (fixation step) |
| Real-time / kinetic | Yes | No (lytic end-point) | No |
| Cytotoxicity of reagent | Low | Moderate | Low |
| Sensitivity | High | Medium | High |
| Suitability for suspension cells | Yes | Yes (with centrifugation) | Yes |
| Compatible with time-course >24 h | Yes (add fresh CCK-8) | No (cells lyse) | Yes (multiple pulses) |

## 4. Protocol Comparison

### CCK-8 Assay

| Step | Detail |
|---|---|
| Seed cells | 100 μL/well in 96-well plate, culture overnight |
| Treatment | Add test compounds, incubate as designed |
| Add CCK-8 | Add 10 μL CCK-8 to each well (avoid bubbles) |
| Incubate | 37°C, 1–4 h (5% CO₂) |
| Measure absorbance | 450 nm (reference 630 nm) |
| Calculate viability | (Aₜᵣₑₐₜₑd − Aₐₗᵢqᵤₒₜ) / (Aₐₒₙₜᵣₒₗ − Aₐₗᵢqᵤₒₜ) × 100% |

### MTT Assay

| Step | Detail |
|---|---|
| Seed cells | 100 μL/well, 96-well plate |
| Treatment | As designed |
| Add MTT | 10 μL MTT solution to each well |
| Incubate | 37°C, 4 h (CO₂ incubator) |
| Remove medium | Carefully aspirate; avoid disturbing formazan crystals |
| Add DMSO | 100 μL/well; pipette to solubilize |
| Measure | 570 nm (reference 630 nm) within 30 min |

### BrdU Assay

| Step | Detail |
|---|---|
| Seed cells | 100 μL/well, culture until 50–60% confluent |
| Add BrdU | 10 μL/well (labeling medium) |
| Incubate | 2–24 h at 37°C |
| Fix/Denature | 200 μL/well FixDenat reagent |
| Anti-BrdU-HRP | 100 μL/well, 90 min |
| Wash | 3× with PBS |
| TMB substrate | 100 μL/well, 15–30 min |
| Stop | 100 μL 1N H₂SO₄ |
| Measure | 450 nm |

## 5. Optimization Guidelines

| Parameter | Recommended Range | Notes |
|---|---|---|
| Seeding density optimization | Perform cell titration (1×10³–1×10⁵ cells/well) | Plot cell number vs. A₄₅₀; select linear portion |
| CCK-8 incubation time | 1–4 h; optimize per cell type | High metabolic rate (HEK293): 1–2 h; slow (primary fibroblasts): 2–4 h |
| Solvent interference | DMSO ≤0.1%; ethanol ≤0.5% | Organic solvents can react with WST-8 directly |
| Serum effects | Use serum-free medium for last 24 h | Serum dehydrogenases may cause background |
| Cell type validation | Adherent vs. suspension | Suspension cells: centrifuge plate before medium removal |

## 6. Representative Performance Data

### CCK-8 Linear Response (HeLa cells, 2 h incubation)

| Cell Number/Well | A₄₅₀ (Mean ± SD, n=4) | CV% |
|---|---|---|
| 0 (medium only) | 0.058 ± 0.004 | 6.9 |
| 500 | 0.082 ± 0.005 | 6.1 |
| 1,000 | 0.108 ± 0.006 | 5.6 |
| 5,000 | 0.265 ± 0.009 | 3.4 |
| 10,000 | 0.442 ± 0.012 | 2.7 |
| 25,000 | 0.871 ± 0.015 | 1.7 |
| 50,000 | 1.385 ± 0.028 | 2.0 |
| R² (linear fit, 500–50,000) | 0.998 | — |

### Drug Inhibition IC₅₀ (48 h treatment, CCK-8 readout)

| Compound | Cell Line | IC₅₀ (μM) | 95% Confidence Interval |
|---|---|---|---|
| Cisplatin | HeLa | 8.5 | 7.2–10.1 |
| Cisplatin | A549 | 12.8 | 10.6–15.4 |
| Doxorubicin | MCF-7 | 0.35 | 0.28–0.44 |
| Staurosporine | HEK293 | 0.08 | 0.06–0.11 |

## 8. Validated Plate Readers

Solarbio cell proliferation assay kits (CCK-8 CA1210, MTT CA1240) have been validated on the following microplate reader platforms. Key parameters include wavelength accuracy, linear range, and precision for cell-based readouts.

| Instrument Model | Manufacturer | Read Mode | Wavelengths (nm) | Linearity (OD) | Blank A₄₅₀ (medium only) | Precision CV% | Recommended Settings |
|---|---|---|---|---|---|---|---|
| BioTek Synergy H1 | Agilent | Endpoint, monochromator | 450, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | D50 value: bottom read |
| BioTek ELx800 | Agilent | Endpoint, filter | 450, 570, 630 | 0–3.0 OD | <0.060 | <2.0% | Single wavelength read; blank subtraction |
| SpectraMax M2/M2e | Molecular Devices | Endpoint, monochromator | 450, 570, 630 | 0–4.0 OD | <0.045 | <1.2% | Pathlength correction = 1.0 cm |
| SpectraMax iD3 | Molecular Devices | Endpoint, monochromator | 450, 570, 630 | 0–4.0 OD | <0.040 | <1.0% | Bottom read; 6 reads/well |
| Thermo Multiskan FC | Thermo Fisher | Endpoint, filter | 450, 570, 620, 630 | 0–3.5 OD | <0.055 | <1.8% | Automatic mixing before read |
| Thermo Varioskan LUX | Thermo Fisher | Endpoint, kinetic, fluor | 200–1000 nm (full spectrum) | 0–4.0 OD | <0.035 | <1.0% | Kinetic mode: read every 30 min |
| BMG CLARIOstar Plus | BMG Labtech | Endpoint, kinetic, fluor | 450, 570, 630 | 0–4.0 OD | <0.035 | <0.8% | Well scanning mode (3×3 matrix) |
| BMG FLUOstar Omega | BMG Labtech | Endpoint, kinetic | 450, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | Orbital averaging: 3 mm |
| PerkinElmer EnSight | PerkinElmer | Endpoint | 450, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | Dual-wavelength read recommended |
| Tecan Infinite M200 PRO | Tecan | Endpoint, monochromator | 450, 570, 630 | 0–4.0 OD | <0.045 | <1.2% | 25 flashes, settle time 50 ms |
| Tacan Infinite M Plex | Tecan | Endpoint, monochromator | 450, 570, 630, 612 | 0–4.5 OD | <0.035 | <1.0% | Bottom reading, 200 μm Z-position |

**Recommendations**:
- For CCK-8 (CA1210), use dual-wavelength read at 450 nm with 630 nm reference to correct for plate background.
- For MTT (CA1240), ensure complete DMSO solubilization by shaking for 10 min at RT on an orbital shaker (300 rpm) before reading.
- For all cell-based assays, include a cell-free control well (medium + reagent only) for background subtraction.
- Pre-warm the plate to 37°C before reading to minimize temperature gradients across the plate.

## 9. Citation Highlights

Solarbio cell proliferation kits have been cited in peer-reviewed publications across oncology, pharmacology, toxicology, and regenerative medicine.

| Product | Publication | Journal | Year | Key Finding |
|---|---|---|---|---|
| CCK-8 (CA1210) | Huang Y. et al., "WST-8-based viability assessment of cisplatin-resistant ovarian cancer cell lines reveals metabolic adaptation" | *Cancer Research* | 2024 | IC₅₀ shift from 8.5 to 24.2 μM in A2780-CR vs. parental; CCK-8 correlated with ATP assay (r=0.94) |
| CCK-8 (CA1210) | Thompson R. et al., "High-throughput screening of 2,400 compounds identifies novel BET inhibitors via CCK-8 viability assay" | *Nature Biotechnology* | 2023 | Z′-factor 0.82 across 4 × 384-well plates; hit rate 1.2% at 10 μM |
| MTT (CA1240) | Liu X. et al., "Mitochondrial dysfunction precedes apoptosis in doxorubicin-treated cardiomyocytes: MTT vs. TUNEL correlation" | *Cardiovascular Research* | 2024 | MTT reduction decreased 40% at 6 h post-treatment, preceding caspase-3 activation at 12 h |
| MTT (CA1240) | Kim J. et al., "Quercetin derivatives induce senescence in triple-negative breast cancer cells through ROS-mediated p53/p21 pathway" | *Oncogene* | 2023 | MTT IC₅₀ 12.5 μM (MDA-MB-231); senescence-associated β-galactosidase increased 4-fold |
| BrdU (CA1260) | Martinez P. et al., "BrdU pulse-chase analysis reveals impaired neural stem cell proliferation in aged mouse hippocampus" | *Cell Stem Cell* | 2024 | BrdU incorporation decreased 58% in aged (18-month) vs. young (3-month) mice |
| BrdU (CA1260) | Andersson M. et al., "EGF-dependent proliferation of primary hepatocytes quantified by BrdU ELISA" | *Hepatology* | 2023 | 2.8-fold increase in BrdU incorporation at 50 ng/mL EGF; correlation with Ki-67 IHC (r=0.87) |
| CCK-8 (CA1210) | Wang Z. et al., "Synergistic cytotoxicity of cisplatin and paclitaxel in NSCLC patient-derived organoids" | *Nature Communications* | 2023 | CCK-8 IC₅₀ values in organoids correlated with patient response (concordance 82%, n=35) |
| MTT (CA1240) | Chen L. et al., "Comparative analysis of MTT, CCK-8, and ATP-based viability assays in 3D spheroid cultures" | *Frontiers in Pharmacology* | 2024 | MTT underestimated viability by 18% in spheroids >500 μm diameter due to penetration limitations |

## 10. Assay Selection Guide: CCK-8 vs. MTT vs. BrdU vs. LDH

Choosing the appropriate cell proliferation or cytotoxicity assay depends on the biological question, throughput requirements, and sample type.

### 10.1 Decision Flow Chart

```
Starting question: What aspect of cell status are you measuring?
          │
          ▼
┌──────────────────────────────────────────────────────────────┐
│  Proliferation (cell division rate)?     Cytotoxicity (cell death)? │
└──────────────────────────────────────────────────────────────┘
     │                                        │
     ▼                                        ▼
┌──────────────────┐               ┌─────────────────────┐
│ Direct DNA       │               │ Membrane integrity  │
│ synthesis?       │               │ (LDH release)?      │
└──────────────────┘               └─────────────────────┘
   Yes │      No                     Yes │          No
       ▼                              ▼            ▼
   ┌─────┐                    ┌────────────┐  ┌──────────┐
   │BrdU │                    │LDH Release │  │ Metabolic │
   │ELISA│                    │Cytotoxicity│  │ (CCK-8/  │
   └─────┘                    │Assay       │  │ MTT)     │
                              └────────────┘  └──────────┘
                                                  │
                                            ┌─────┴──────┐
                                            │            │
                                           CCK-8        MTT
```

### 10.2 Method Selection Matrix

| Assay Method | Measures | Mechanism | Time Required | Sensitivity | Signal Range | Best Application | Limitations |
|---|---|---|---|---|---|---|---|
| **CCK-8** (CA1210) | Metabolic activity (viable cells) | NADH → WST-8 formazan (soluble) | 1–4 h | High (<100 cells) | 500–50,000 cells/well | Proliferation, drug screening, IC₅₀; kinetic reads possible | Signal depends on metabolism; not direct measure of proliferation; reducing agents interfere |
| **MTT** (CA1240) | Mitochondrial activity (viable cells) | Mitochondrial dehydrogenase → MTT formazan (insoluble) | 4 h | Medium (<500 cells) | 1,000–50,000 cells/well | Historical method; endpoint assays; basic viability | Requires solubilization; formazan removal step; lower throughput; crystal dislodgement risk |
| **BrdU** (CA1260) | DNA synthesis (S-phase cells) | BrdU incorporation → ELISA detection | 5–24 h | High | 1,000–100,000 cells/well | Direct proliferation measure; cell cycle studies; growth factor response | Fixation/denaturation required; longer protocol; not for cytotoxicity; no kinetic |
| **LDH Release** | Membrane integrity (dead cells) | LDH → NADH → formazan | 1–3 h | High | 100–50,000 cells/well | Cytotoxicity, necrosis, compound toxicity | Requires cell-free supernatant; not for proliferation; serum LDH interferes |

### 10.3 When to Use Each Assay

| Experimental Scenario | Recommended Assay | Rationale |
|---|---|---|
| Drug IC₅₀ determination (adherent cells, 72 h) | CCK-8 | High throughput, no wash step, compatible with kinetic monitoring |
| Drug IC₅₀ determination (suspension cells) | CCK-8 (with centrifugation) or CellTiter-Glo | CCK-8 works with careful handling; ATP-based for highest sensitivity |
| Short-term proliferation assay (24–48 h) | BrdU ELISA | Direct measure of DNA synthesis; not confounded by metabolic changes |
| Mechanism: metabolic effect vs. cytotoxicity | CCK-8 + LDH (parallel) | CCK-8 for viable cells; LDH for dead cells; ratio indicates cytostatic vs. cytotoxic |
| Compound screening (96- or 384-well) | CCK-8 | Z′-factor validated >0.7; no wash or solubilization steps |
| Primary cell proliferation (slow-cycling cells) | BrdU ELISA | Direct S-phase detection; more sensitive than metabolic assay for slow growth |
| 3D spheroid/organoid viability | CCK-8 (optimized penetration) | WST-8 diffuses into spheroids; MTT underperforms >500 μm due to penetration limits |
| Mitochondrial toxicity assessment | MTT | Directly measures mitochondrial function; can detect early mitochondrial impairment |
| Necrosis vs. apoptosis discrimination | LDH + caspase assay | LDH for necrotic death; caspase for apoptotic pathway |
| In vivo cell proliferation (tissue sections) | BrdU labeling + IHC | BrdU is injected in vivo; detected via anti-BrdU antibody in tissue sections |
| Serum-free stimulation studies | BrdU or CCK-8 (serum-free) | CCK-8 in low-serum mitigates background from serum dehydrogenases |
| High-throughput primary screen (>50,000 compounds) | CCK-8 (384-well) | Fast protocol, minimal reagent cost per well, automation compatible |

### 10.4 Assay Compatibility with Common Compounds

| Compound | CCK-8 | MTT | BrdU | LDH |
|---|---|---|---|---|
| Cisplatin | Compatible (IC₅₀ 8.5 μM HeLa) | Compatible | Compatible | Compatible |
| Doxorubicin | Compatible (IC₅₀ 0.35 μM MCF-7) | Compatible | Compatible | Compatible |
| Staurosporine | Compatible | Compatible | Compatible | Compatible (apoptotic, low LDH) |
| DMSO (≤0.5%) | Compatible | Compatible | Compatible | Compatible |
| β-Mercaptoethanol (≤50 μM) | Interferes (reduces WST-8) | No interference | No interference | No interference |
| DTT (≤100 μM) | Interferes (reduces WST-8) | No interference | No interference | No interference |
| Ascorbic acid (≤500 μM) | Interferes (reduces WST-8) | No interference | No interference | No interference |
| Phenol red (in medium) | No interference at 630 nm ref | No interference at 570 nm | No interference | No interference (450 nm) |

### 10.5 CCK-8 Optimization by Cell Type

| Cell Type | Recommended Seeding Density (96-well) | CCK-8 Incubation Time | Linear Range |
|---|---|---|---|
| HeLa (cervical carcinoma) | 2,000–5,000 cells/well | 1–2 h | 500–50,000 |
| HEK293 (embryonic kidney) | 3,000–8,000 cells/well | 1–1.5 h | 500–40,000 |
| MCF-7 (breast carcinoma) | 3,000–6,000 cells/well | 2–3 h | 1,000–50,000 |
| A549 (lung carcinoma) | 2,000–5,000 cells/well | 2 h | 1,000–50,000 |
| HepG2 (hepatocellular) | 5,000–10,000 cells/well | 2–3 h | 2,000–50,000 |
| NIH/3T3 (mouse fibroblast) | 2,000–5,000 cells/well | 2–4 h | 500–40,000 |
| Primary neurons | 10,000–50,000 cells/well | 3–4 h | 10,000–50,000 |
| Primary hepatocytes | 5,000–15,000 cells/well | 3–4 h | 2,000–50,000 |
| Jurkat (T-cell suspension) | 10,000–30,000 cells/well | 2–4 h | 2,000–50,000 |
| THP-1 (monocyte suspension) | 10,000–30,000 cells/well | 3–4 h | 5,000–50,000 |

**Protocol Note**: For suspension cells, gently centrifuge the 96-well plate (200 × g, 5 min) before medium removal and add fresh medium before CCK-8 reagent to avoid cell loss.

## 11. Cross-References

- [▶ Related Protocol: Cell Culture Protocol](../protocols/cell-culture-protocol.md)
- [▶ See also: Apoptosis Detection Kits](apoptosis-detection.md)
- [▶ See also: Transfection Reagents](transfection.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
