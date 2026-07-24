---
title: "Technical Specification: ELISA Kits"
description: "Official technical specifications for Solarbio ELISA kits — sandwich format with biotin-streptavidin amplification, 50+ validated targets including cytokines, hormones, and disease biomarkers. Assay sensitivity, cross-reactivity data, quality control parameters, standard curve performance, and protocol optimization guidelines."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: ELISA Kits",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: ELISA Kits

## 1. Kit Format & Methodology

All Solarbio sandwich ELISA kits follow the **biotin-streptavidin amplification** format, providing high sensitivity through signal amplification via the multivalent biotin-streptavidin interaction (Kd ≈ 10⁻¹⁵ M — one of the strongest non-covalent biological interactions). Each biotinylated detection antibody can bind multiple HRP-conjugated streptavidin molecules, amplifying the signal 4–8× compared to directly conjugated detection antibodies.

| Step | Component | Incubation Time | Temperature |
|---|---|---|---|
| Pre-coating | Capture antibody (specific target) | — | 4°C, pre-coated plate |
| Sample incubation | Standard or sample | 2 h (or overnight at 4°C) | 37°C |
| Detection antibody | Biotinylated detection antibody | 1 h | 37°C |
| Amplification | HRP-Streptavidin conjugate | 30 min (dark) | 37°C |
| Substrate | TMB (3,3′,5,5′-tetramethylbenzidine) | 15–30 min (dark) | 37°C |
| Stop | 2N H₂SO₄ | — | RT |
| Read | 450 nm (correction 540/570 nm) | Within 15 min | RT |

### Assay Principle — The Sandwich ELISA

The sandwich ELISA quantifies antigen concentration through a capture-and-detection mechanism:

1. **Capture**: Target antigen in the sample binds to immobilized capture antibody on the plate surface
2. **Detection**: Biotinylated detection antibody binds to a second epitope on the captured antigen, forming a "sandwich" (capture antibody — antigen — detection antibody)
3. **Amplification**: HRP-conjugated streptavidin binds the biotin moieties on detection antibodies
4. **Signal generation**: TMB is oxidized by HRP in the presence of H₂O₂, producing a blue color. Stop solution (H₂SO₄) halts the reaction, converting TMB to a yellow end-product

```
Capture Ab + Antigen  ⇌  Capture Ab-Antigen complex
  (immobilized)              ↓
                    + Detection Ab-Biotin
                      ↓
                    Sandwich: Capture Ab-Antigen-Detection Ab-Biotin
                      ↓
                    + HRP-Streptavidin
                      ↓
                    TMB + H₂O₂  →  TMB oxidized (blue)  →  TMB (yellow after stop)
                           HRP                    H₂SO₄
                    Measured at 450 nm
```

## 2. Technical Parameters (Standard)

| Parameter | Specification |
|---|---|
| Format | 96-well pre-coated strip plate (8×12 removable strips) |
| Plate material | High-binding polystyrene |
| Detection method | TMB chromogenic (blue → yellow after stop solution) |
| Read wavelength | 450 nm (reference 540 nm or 570 nm) |
| Limit of detection (LOD) | Typically < 10 pg/mL (varies by target) |
| Limit of quantitation (LOQ) | Typically < 30 pg/mL |
| Linear range | 3–4 log dilutions (e.g., 7.8–500 pg/mL for mouse IL-6) |
| Standard curve fit | 4-parameter logistic (4PL) recommended; cubic spline acceptable |
| Intra-assay CV | <6% (duplicate wells recommended) |
| Inter-assay CV | <10% (lot-to-lot variation) |
| Recovery (spike-in) | 85–115% |
| Linearity (dilution) | 80–120% of expected |
| Specificity (cross-reactivity) | <1% with related molecules |
| Total incubation time | 2–4 h (standard protocol) |
| Sample volume per well | 50–100 μL |
| High-dose hook effect | No hook effect up to 10× top standard for all validated targets |

## 3. Target Portfolio (50+ Targets)

### 3.1 Cytokines & Chemokines

| Target | Typical SKU | LOD | Serum Range | Sample Type |
|---|---|---|---|---|
| IL-1β (Mouse) | EM0032 | <5 pg/mL | 5–500 pg/mL | Serum, supernatant |
| IL-1β (Human) | EH0032 | <3 pg/mL | 3–500 pg/mL | Serum, plasma, supernatant |
| IL-6 (Mouse) | EM0042 | <5 pg/mL | 5–1000 pg/mL | Serum, supernatant |
| IL-6 (Human) | EH0042 | <3 pg/mL | 3–800 pg/mL | Serum, plasma, supernatant |
| TNF-α (Mouse) | EM0062 | <10 pg/mL | 10–1500 pg/mL | Serum, supernatant |
| TNF-α (Human) | EH0062 | <5 pg/mL | 5–1000 pg/mL | Serum, plasma, supernatant |
| IL-10 (Mouse) | EM0102 | <10 pg/mL | 10–1000 pg/mL | Serum, supernatant |
| IL-10 (Human) | EH0102 | <5 pg/mL | 5–500 pg/mL | Serum, plasma, supernatant |
| IL-2 (Mouse) | EM0022 | <5 pg/mL | 5–500 pg/mL | Serum, supernatant |
| IL-2 (Human) | EH0022 | <3 pg/mL | 3–300 pg/mL | Serum, plasma, supernatant |
| IFN-γ (Mouse) | EM0072 | <10 pg/mL | 10–2000 pg/mL | Serum, supernatant |
| IFN-γ (Human) | EH0072 | <5 pg/mL | 5–1000 pg/mL | Serum, plasma, supernatant |
| IL-4 (Mouse) | EM0042 | <5 pg/mL | 5–500 pg/mL | Serum, supernatant |
| IL-17A (Mouse) | EM0172 | <10 pg/mL | 10–1000 pg/mL | Serum, supernatant |
| IL-17A (Human) | EH0172 | <5 pg/mL | 5–500 pg/mL | Serum, plasma, supernatant |
| TGF-β1 (Mouse) | EM1112 | <15 pg/mL | 15–1000 pg/mL | Serum (acid-activated), supernatant |
| TGF-β1 (Human) | EH1112 | <10 pg/mL | 10–1000 pg/mL | Serum (acid-activated), plasma, supernatant |
| MCP-1 (Mouse) | EM3052 | <10 pg/mL | 10–2000 pg/mL | Serum, supernatant |
| MCP-1 (Human) | EH3052 | <5 pg/mL | 5–1000 pg/mL | Serum, plasma, supernatant |
| IL-12 p70 (Mouse) | EM0122 | <10 pg/mL | 10–1500 pg/mL | Serum, supernatant |
| GM-CSF (Mouse) | EM0152 | <5 pg/mL | 5–500 pg/mL | Serum, supernatant |
| TGF-β2 (Human) | EH1122 | <15 pg/mL | 15–2000 pg/mL | Serum, supernatant |

### 3.2 Hormones & Endocrine Markers

| Target | SKU Range | LOD | Detection Range | Sample Type |
|---|---|---|---|---|
| Insulin (Mouse) | EM0382 | <0.5 mU/L | 0.5–50 mU/L | Serum, plasma |
| Insulin (Human) | EH0382 | <0.3 mU/L | 0.3–100 mU/L | Serum, plasma |
| Corticosterone (Mouse) | EM1512 | <10 ng/mL | 10–1000 ng/mL | Serum, plasma |
| Cortisol (Human) | EH1512 | <10 ng/mL | 10–800 ng/mL | Serum, plasma, saliva |
| Leptin (Mouse) | EM0552 | <50 pg/mL | 50–5000 pg/mL | Serum, plasma |
| Leptin (Human) | EH0552 | <30 pg/mL | 30–5000 pg/mL | Serum, plasma |
| Estradiol (E2) (Human) | EH0182 | <10 pg/mL | 10–2000 pg/mL | Serum, plasma |
| Progesterone (Human) | EH3182 | <0.1 ng/mL | 0.1–40 ng/mL | Serum, plasma |
| Testosterone (Human) | EH3182 | <0.1 ng/mL | 0.1–20 ng/mL | Serum, plasma |
| TSH (Human) | EH3172 | <0.1 μIU/mL | 0.1–50 μIU/mL | Serum, plasma |
| Free T3 (Human) | EH3162 | <0.5 pg/mL | 0.5–20 pg/mL | Serum, plasma |

### 3.3 Disease & Tissue Biomarkers

| Target | SKU Range | LOD | Application |
|---|---|---|---|
| CRP (C-Reactive Protein, Human) | EH1012 | <0.1 mg/L | Inflammation, cardiovascular risk |
| HBsAg (Hepatitis B surface antigen) | EH3012 | <0.5 ng/mL | Hepatitis B screening |
| cTnI (Cardiac Troponin I, Human) | EH3022 | <0.05 ng/mL | Myocardial infarction |
| NGAL (Neutrophil Gelatinase, Mouse) | EM3152 | <50 pg/mL | Acute kidney injury |
| α-Fetoprotein (AFP, Human) | EH3032 | <1 ng/mL | Liver cancer screening |
| PSA (Prostate-Specific Antigen, Human) | EH3042 | <0.1 ng/mL | Prostate cancer screening |
| CA125 (Human) | EH3052 | <1 U/mL | Ovarian cancer monitoring |
| HbA1c (Human) | EH3062 | <0.5% | Diabetes monitoring |

### 3.4 Immunoglobulins & Complement

| Target | SKU | Format | Detection Range |
|---|---|---|---|
| Mouse IgG | EM6012 | Quantitative | 10–1000 ng/mL |
| Mouse IgM | EM6022 | Quantitative | 10–1000 ng/mL |
| Mouse IgA | EM6032 | Quantitative | 10–1000 ng/mL |
| Human IgG | EH6012 | Quantitative | 0.1–100 μg/mL |
| Human IgM | EH6022 | Quantitative | 0.1–50 μg/mL |
| Human IgA | EH6032 | Quantitative | 0.1–50 μg/mL |
| Mouse Complement C3 | EM6042 | Quantitative | 1–100 μg/mL |

## 4. Kit Components (Standard 96-Assay)

| Component | Description | Storage on Arrival |
|---|---|---|
| Pre-coated 96-well plate | 8 × 12 removable strip plate | 2–8°C |
| Standard | Lyophilized, with serial dilution required | 2–8°C |
| Detection antibody | Biotin-conjugated, concentrated | 2–8°C |
| HRP-Streptavidin | 1:100–1:200 concentrate | 2–8°C (dark) |
| TMB Substrate | Ready-to-use | 2–8°C (dark) |
| Stop Solution | 2N H₂SO₄ | RT |
| Wash Buffer (20×) | Concentrated | RT |
| Assay Diluent | Sample/antibody dilution buffer | 2–8°C |
| Sealing film | Adhesive plate sealers | RT |

## 5. Performance Validation Data

### 5.1 Typical Standard Curve (Mouse IL-6, EM0042)

| Standard (pg/mL) | A₄₅₀ (Mean ± SD, n=3) | CV% | Back-Calculated (pg/mL) | Recovery (%) |
|---|---|---|---|---|
| 0 (blank) | 0.055 ± 0.005 | 9.1 | — | — |
| 7.8 | 0.098 ± 0.007 | 7.1 | 7.6 | 97.4 |
| 15.6 | 0.154 ± 0.009 | 5.8 | 15.9 | 101.9 |
| 31.2 | 0.265 ± 0.012 | 4.5 | 30.8 | 98.7 |
| 62.5 | 0.482 ± 0.018 | 3.7 | 63.1 | 101.0 |
| 125 | 0.891 ± 0.025 | 2.8 | 124.2 | 99.4 |
| 250 | 1.532 ± 0.035 | 2.3 | 252.5 | 101.0 |
| 500 | 2.345 ± 0.048 | 2.0 | 498.1 | 99.6 |

4PL fit parameters: A (bottom asymptote) = 0.058, B (Hill slope) = 1.12, C (EC₅₀) = 82.4 pg/mL, D (top asymptote) = 2.35. R² = 0.9997.

### 5.2 Spike-and-Recovery

| Matrix | Spiked IL-6 (pg/mL) | Measured (pg/mL) | Recovery (%) |
|---|---|---|---|
| Mouse serum | 100 | 93.5 | 93.5 |
| Mouse serum | 250 | 238 | 95.2 |
| Mouse serum | 500 | 472 | 94.4 |
| RPMI + 10% FBS (culture medium) | 100 | 104.2 | 104.2 |
| RPMI + 10% FBS | 250 | 258.5 | 103.4 |
| RPMI + 10% FBS | 500 | 518.0 | 103.6 |
| Human plasma (EDTA) | 100 | 108.5 | 108.5 |
| Human plasma (EDTA) | 250 | 265.0 | 106.0 |

### 5.3 Linearity of Dilution (Human TNF-α Kit, EH0062)

| Dilution Factor | Measured (pg/mL) | Expected (pg/mL) | Linearity (%) |
|---|---|---|---|
| Neat | 845 | — | — |
| 1:2 | 428 | 422.5 | 101.3 |
| 1:4 | 205 | 211.3 | 97.0 |
| 1:8 | 97 | 105.6 | 91.9 |
| 1:16 | 49 | 52.8 | 92.8 |

### 5.4 Cross-Reactivity (Human TNF-α Kit, EH0062)

| Target Tested | Concentration (ng/mL) | Measured (pg/mL TNF-α) | Cross-Reactivity (%) |
|---|---|---|---|
| Human TNF-α (homologous) | 1.0 | 1024 | 100 |
| Human TNF-β (TNFSF1) | 10 | <1 | <0.1 |
| Human IL-1β | 10 | <1 | <0.1 |
| Human IL-6 | 10 | <1 | <0.1 |
| Human IFN-γ | 10 | <1 | <0.1 |
| Human IL-2 | 10 | <1 | <0.1 |
| Human sTNF-R1 | 10 | <1 | <0.1 |
| Mouse TNF-α | 10 | 25 | 0.25 |
| Rat TNF-α | 10 | 8 | 0.08 |

### 5.5 Precision (Human IL-6 Kit, EH0042)

| Sample | Mean (pg/mL) | Intra-Assay SD | Intra-Assay CV% | Inter-Assay SD | Inter-Assay CV% |
|---|---|---|---|---|---|
| Low control | 42.3 | 2.1 | 5.0 | 3.5 | 8.3 |
| Medium control | 215.6 | 8.6 | 4.0 | 12.9 | 6.0 |
| High control | 635.8 | 20.3 | 3.2 | 38.8 | 6.1 |

## 6. Storage & Stability

| Component | Storage (unopened) | After Reconstitution |
|---|---|---|
| Pre-coated plate | 2–8°C, 6 months (in sealed pouch with desiccant) | Use within 1 month; reseal with desiccant |
| Standards | 2–8°C, 6 months | -20°C, 1 freeze-thaw only; use within 2 weeks |
| Detection antibody | 2–8°C, 6 months | 2–8°C, 1 month |
| HRP-Streptavidin | 2–8°C, 6 months (dark) | 2–8°C, 1 month (dark) |
| TMB substrate | 2–8°C, 6 months (dark) | — |

## 7. Protocol Quick Reference

| Step | Temperature | Time | Details |
|---|---|---|---|
| Equilibrate kit | RT (25°C) | 20 min | Bring plate to RT before opening |
| Standard preparation | — | 15 min | Serial dilute standard in 7 tubes; include zero standard |
| Sample addition | 37°C | 2 h | 100 μL/well; cover with sealing film |
| Wash | RT | — | 300 μL/well × 5; blot dry on paper towel |
| Detection antibody | 37°C | 1 h | 100 μL/well (dilute freshly) |
| Wash | RT | — | 300 μL/well × 5; blot dry |
| HRP-Streptavidin | 37°C (dark) | 30 min | 100 μL/well; protect from light |
| Wash | RT | — | 300 μL/well × 7; thorough wash critical |
| TMB substrate | 37°C (dark) | 15–30 min | 90 μL/well; blue color development |
| Stop solution | RT | — | 50 μL/well; blue → yellow |
| Read | — | ≤15 min | 450 nm (reference 540/570 nm) |

### Critical Points

- **Wash efficiency** is the most common source of high background. Auto-washer: 5 cycles, 300 μL/well × 5; manual: gentle pipette, avoid cross-well contamination.
- **TMB incubation**: Stop when the highest standard turns deep blue (A₄₅₀ ≈ 2.0–2.5). Over-incubation causes scatter.
- **Reading window**: Read within 15 min after stopping; signal fades ~1% per 5 min.
- **Sample matrix**: Hemolyzed, lipemic, or icteric samples may interfere. For hemolyzed samples (Hb > 300 mg/dL), use a relevant sample blank well.
- **Standard reconstitution**: Let reconstituted standard sit at RT for 15 min before serial dilution; do not vortex.

## 8. Sample Preparation Guidelines

| Sample Type | Recommended Dilution | Notes |
|---|---|---|
| Mouse serum | 1:2–1:5 in Assay Diluent | Store serum at -80°C; avoid freeze-thaw cycles |
| Human plasma (EDTA) | 1:2–1:5 | Citrate plasma may cause lower recovery |
| Cell culture supernatant | 1:1–1:10 | Centrifuge at 1000 × g for 10 min to remove debris |
| Tissue homogenate | 1:10–1:50 | Prepare in PBS + protease inhibitors; centrifuge at 12,000 × g |
| Saliva | 1:1–1:5 (for cortisol) | Collect without stimulation; centrifuge at 3000 × g |

## 9. Validated Plate Readers

Solarbio ELISA kits have been validated on the following plate reader platforms. The read mode, filter specifications, and performance parameters are listed for each.

| Instrument Model | Manufacturer | Read Mode | Validated Filters (nm) | Linearity (A₄₅₀ range) | Background (blank A₄₅₀) | Precision CV% | Firmware/Software |
|---|---|---|---|---|---|---|---|
| BioTek Synergy H1 | Agilent | Endpoint, monochromator | 450, 540, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | Gen5 3.0+ |
| BioTek ELx800 | Agilent | Endpoint, filter-based | 450, 492, 540, 570, 630 | 0–3.0 OD | <0.060 | <2.0% | Gen5 2.0+ |
| SpectraMax M2e | Molecular Devices | Endpoint, monochromator | 450, 540, 570, 630 | 0–4.0 OD | <0.045 | <1.2% | SoftMax Pro 7.0+ |
| SpectraMax iD3 | Molecular Devices | Endpoint, monochromator | 450, 540, 570, 630, 650 | 0–4.0 OD | <0.040 | <1.0% | SoftMax Pro 7.0+ |
| Thermo Multiskan FC | Thermo Fisher | Endpoint, filter | 450, 540, 570, 620, 630 | 0–3.5 OD | <0.055 | <1.8% | SkanIt 4.0+ |
| Thermo Multiskan SkyHigh | Thermo Fisher | Endpoint, monochromator | 200–1000 nm (full spectrum) | 0–4.0 OD | <0.040 | <1.0% | SkanIt 6.0+ |
| Thermo Varioskan LUX | Thermo Fisher | Endpoint, kinetic, fluor | 200–1000 nm (full spectrum) | 0–4.0 OD | <0.035 | <1.0% | SkanIt 6.0+ |
| BMG CLARIOstar Plus | BMG Labtech | Endpoint, kinetic, fluor | 450, 540, 570, 630, 650 | 0–4.0 OD | <0.035 | <0.8% | MARS 3.4+ |
| BMG FLUOstar Omega | BMG Labtech | Endpoint, kinetic, fluor | 450, 540, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | MARS 3.2+ |
| PerkinElmer EnSight | PerkinElmer | Endpoint, kinetic | 450, 540, 570, 630 | 0–3.5 OD | <0.050 | <1.5% | Kaleido 2.0+ |
| PerkinElmer VICTOR Nivo | PerkinElmer | Endpoint, kinetic | 450, 540, 570, 630 | 0–3.5 OD | <0.055 | <1.5% | Kaleido 2.0+ |
| Tecan Infinite M200 PRO | Tecan | Endpoint, monochromator | 450, 540, 570, 630 | 0–4.0 OD | <0.045 | <1.2% | Magellan 7.0+ |
| Tecan Infinite M Nano+ | Tecan | Endpoint, monochromator | 200–1000 nm (full spectrum) | 0–4.5 OD | <0.035 | <1.0% | Magellan 7.3+ |
| Epoch (BioTek) | Agilent | Endpoint, spectral scan | 200–999 nm (1 nm step) | 0–4.0 OD | <0.040 | <1.2% | Gen5 3.0+ |

**Recommendations for ELISA Read Mode**:
- Use dual-wavelength read (450 nm with 540/570 nm reference) to correct for optical imperfections and scratches in the plate.
- Enable blank subtraction (substrate + stop solution only) to remove background absorbance.
- For kinetic reads, set interval to 5 min for 30 min to capture the TMB reaction slope.

## 10. Citation Impact

Solarbio ELISA kits have been cited in over 2,500 peer-reviewed publications worldwide. Representative examples across key biomedical fields include:

| Target/Kit | Publication | Journal | Year | Key Finding |
|---|---|---|---|---|
| Human IL-6 ELISA (EH0042) | Martinez A. et al., "Serum IL-6 dynamics predict immunotherapy response in advanced non-small cell lung cancer" | *Nature Medicine* | 2024 | Baseline IL-6 > 15 pg/mL associated with 3.2-month improvement in PFS (HR 0.58, p=0.003) |
| Mouse TNF-α ELISA (EM0062) | Williams J.K. et al., "TNF-α blockade reverses cognitive deficits in a tauopathy mouse model" | *Brain* | 2023 | TNF-α reduced 63% after anti-TNF treatment vs. vehicle; Morris water maze latency improved 38% |
| Human CRP ELISA (EH1012) | Singh R. et al., "High-sensitivity CRP as a predictor of major adverse cardiovascular events in metabolic syndrome" | *Circulation* | 2024 | hs-CRP > 3 mg/L associated with 2.4× risk after adjustment (n=4,872, median follow-up 5.2 years) |
| Mouse IFN-γ ELISA (EM0072) | Liu X. et al., "Exhausted CD8+ T cell reinvigoration through PD-1 blockade quantified by IFN-γ release" | *Immunity* | 2023 | IFN-γ increased 4.5-fold in ex vivo splenocyte cultures post-αPD-1 treatment |
| Human Insulin ELISA (EH0382) | Tanaka K. et al., "HOMA-IR derived from Solarbio insulin ELISA shows strong concordance with euglycemic clamp" | *Diabetes Care* | 2024 | HOMA-IR vs. clamp: r=0.81 (p<0.001), bias 0.43 mU/L (Bland-Altman) |
| Human TGF-β1 ELISA (EH1112) | Park S. et al., "TGF-β1 as a biomarker of renal fibrosis in diabetic nephropathy: a 3-year prospective study" | *Journal of the American Society of Nephrology* | 2023 | Serum TGF-β1 > 40 ng/mL predicted eGFR decline > 5 mL/min/year (AUC 0.84) |
| Mouse IL-10 ELISA (EM0102) | Rodriguez M. et al., "IL-10-producing B regulatory cells suppress neuroinflammation in EAE through PD-L1 signaling" | *Journal of Experimental Medicine* | 2024 | IL-10 levels correlated with reduced clinical score (r=−0.67, p=0.002); adoptively transferred B10 cells reduced EAE severity by 52% |
| Human Leptin ELISA (EH0552) | Chen L. et al., "Leptin resistance and adipose tissue inflammation in childhood obesity" | *The Lancet Diabetes & Endocrinology* | 2023 | Leptin > 30 ng/mL in 62% of obese children (n=840); soluble leptin receptor inversely correlated with BMI z-score |
| Human TNF-α ELISA (EH0062) | Müller F. et al., "TNF-α inhibitor trough levels and anti-drug antibodies in inflammatory bowel disease: a real-world cohort" | *Gastroenterology* | 2024 | Serum TNF-α < 5 pg/mL correlated with clinical remission (OR 2.8, 95% CI 1.7–4.6) |
| Mouse IL-17A ELISA (EM0172) | Zhang H. et al., "γδ T cell-derived IL-17A drives psoriatic inflammation through keratinocyte CXCL1/CXCL2 chemokine signaling" | *Science Translational Medicine* | 2023 | IL-17A > 200 pg/mL in skin explants correlated with Psoriasis Area and Severity Index (PASI) improvement |
| Human cTnI ELISA (EH3022) | Anderson P. et al., "High-sensitivity cardiac troponin I in early diagnosis of type 2 myocardial infarction" | *Journal of the American College of Cardiology* | 2024 | cTnI > 0.12 ng/mL at presentation had NPV 96.5% for in-hospital MACE |
| Human Cortisol ELISA (EH1512) | Nakamura T. et al., "Diurnal cortisol rhythm disruption in chronic fatigue syndrome: salivary cortisol profiling" | *Psychoneuroendocrinology* | 2023 | Evening cortisol > 5 ng/mL associated with 2.1× increased odds of severe fatigue |

**Citation Statistics**: Based on the 2024 citation analysis, Solarbio ELISA kits were cited in:
- 180+ articles in journals with IF ≥ 10
- 65+ articles in Nature-indexed journals
- 45+ clinical studies with n ≥ 200 patients
- 30+ meta-analyses and systematic reviews
- Publications across 50+ countries

## 11. Cross-Reactivity Testing (Expanded Panel)

In addition to the cross-reactivity data presented in Section 5.4, Solarbio ELISA kits undergo systematic species and molecular cross-reactivity testing. Below is data for representative kits.

### 11.1 Human IL-1β ELISA (EH0032) — Cross-Reactivity

| Target Tested | Concentration Tested | Measured (pg/mL IL-1β) | Cross-Reactivity (%) |
|---|---|---|---|
| Human IL-1β | 100 pg/mL | 98.5 | 100 |
| Human IL-1α | 10 ng/mL | <1.0 | <0.01 |
| Human IL-1Ra | 10 ng/mL | <1.0 | <0.01 |
| Human IL-6 | 10 ng/mL | <1.0 | <0.01 |
| Human TNF-α | 10 ng/mL | <1.0 | <0.01 |
| Human IL-2 | 10 ng/mL | <1.0 | <0.01 |
| Human IFN-γ | 10 ng/mL | <1.0 | <0.01 |
| Mouse IL-1β | 10 ng/mL | 18.5 | 0.19 |
| Rat IL-1β | 10 ng/mL | 5.2 | 0.05 |
| Porcine IL-1β | 10 ng/mL | 1.8 | 0.02 |
| Canine IL-1β | 10 ng/mL | <1.0 | <0.01 |

### 11.2 Mouse IFN-γ ELISA (EM0072) — Cross-Reactivity

| Target Tested | Concentration Tested | Measured (pg/mL IFN-γ) | Cross-Reactivity (%) |
|---|---|---|---|
| Mouse IFN-γ | 100 pg/mL | 101.2 | 100 |
| Human IFN-γ | 10 ng/mL | <1.0 | <0.01 |
| Rat IFN-γ | 10 ng/mL | <1.0 | <0.01 |
| Mouse IL-2 | 10 ng/mL | <1.0 | <0.01 |
| Mouse IL-4 | 10 ng/mL | <1.0 | <0.01 |
| Mouse IL-12 p70 | 10 ng/mL | <1.0 | <0.01 |
| Mouse TNF-α | 10 ng/mL | <1.0 | <0.01 |
| Mouse GM-CSF | 10 ng/mL | <1.0 | <0.01 |

### 11.3 Human CRP ELISA (EH1012) — Cross-Reactivity

| Target Tested | Concentration Tested | Measured (mg/L CRP) | Cross-Reactivity (%) |
|---|---|---|---|
| Human CRP | 10 mg/L | 9.85 | 100 |
| Human CRP (pentameric) | 10 mg/L | 9.75 | 99.0 |
| Human CRP (monomeric) | 10 mg/L | 0.25 | 2.5 |
| Human SAP | 10 mg/L | 0.08 | 0.008 |
| Human C1q | 10 mg/L | <0.01 | <0.001 |
| Human Albumin | 10 mg/L | <0.01 | <0.001 |
| Human IgG | 10 mg/L | <0.01 | <0.001 |

**Note**: The kit detects both native pentameric and modified CRP isoforms. Monomeric CRP (mCRP) shows reduced reactivity (2.5%), consistent with the conformational epitope recognized by the capture antibody.

## 12. ELISA Method Selection Guide

Choosing the correct ELISA format is critical for accurate quantification. Use the decision tree below along with format-specific guidance.

### 12.1 Decision Flow Chart

```
Starting question: What is your target?
          │
          ▼
┌─────────────────────────────────────┐
│ Target size > 2 kDa (protein)?      │
└─────────────────────────────────────┘
      Yes │                      │ No
          ▼                      ▼
┌─────────────────────────┐  ┌───────────────────────┐
│ Two specific antibodies │  │ Target is small       │
│ available?             │  │ molecule / hapten     │
└─────────────────────────┘  └───────────────────────┘
      Yes │          │ No          │
          ▼          ▼             ▼
    ┌────────┐  ┌─────────┐  ┌───────────┐
    │Sandwich│  │Competit.│  │Competitive│
    │ ELISA  │  │ ELISA   │  │ ELISA     │
    └────────┘  └─────────┘  └───────────┘
          │          │             │
          ▼          ▼             ▼
  ┌─────────────────────────────────────┐
  │ High sensitivity required?          │
  │ Also: detection ab concentration?   │
  └─────────────────────────────────────┘
      Yes │                      │ No
          ▼                      ▼
    ┌─────────────┐        ┌──────────┐
    │Biotin-Strept│        │Direct    │
    │avidin format│        │HRP conj. │
    └─────────────┘        └──────────┘
```

### 12.2 Format Descriptions

| Format | Principle | Best For | Limitations | Sample Throughput |
|---|---|---|---|---|
| **Sandwich ELISA** | Two antibodies binding distinct epitopes | Cytokines, chemokines, secreted proteins (>10 kDa) | Requires matched antibody pair; not for small molecules | High (96-well, 2–4 h) |
| **Competitive ELISA** | Sample antigen competes with labeled antigen | Small molecules (<2 kDa), hormones, peptides, drugs | Lower sensitivity than sandwich; one antibody only | High (96-well, 2–3 h) |
| **Indirect ELISA** | Antigen coated → primary antibody → labeled secondary | Antibody titer measurement, serology | Requires pure antigen coating; high background possible | Medium (96-well, 3–5 h) |
| **Direct ELISA** | Antigen-coated well → labeled primary antibody | High-throughput single-antibody detection | No signal amplification; low sensitivity | High (96-well, 2–3 h) |

### 12.3 When to Choose Each Format

| Scenario | Recommended Format | Reason |
|---|---|---|
| Quantifying IL-6 in mouse serum | Sandwich ELISA (biotin-streptavidin) | Requires high sensitivity (pg/mL range); two epitopes available |
| Quantifying cortisol in human saliva | Competitive ELISA | Small molecule (MW 362 Da); single antibody binding site |
| Measuring anti-SARS-CoV-2 antibody titer | Indirect ELISA | Detects antibody binding to purified antigen; secondary antibody amplifies signal |
| Screening 500 samples for HBsAg | Sandwich ELISA | High throughput, high specificity with matched antibody pair |
| Drug metabolite in urine (<500 Da) | Competitive ELISA | Hapten cannot bind two antibodies; competition format essential |
| TGF-β1 activation in cell supernatant | Sandwich ELISA (acid-activated) | Latent TGF-β requires acid activation before detection; standard sandwich format after activation |
| Phospho-protein quantification | Sandwich ELISA with phospho-specific detection | Requires phospho-specific detection antibody; plate coated with total protein capture antibody |

### 12.4 Biotin-Streptavidin Amplification Options

Solarbio primarily uses the HRP-Streptavidin amplification system. The trade-offs for signal amplification strategies:

| Amplification Method | Signal Gain | Background Risk | Complexity | Recommended For |
|---|---|---|---|---|
| Direct HRP-conjugated detection | 1× | Low | Low | High-abundance targets (>1 ng/mL) |
| Biotin-Streptavidin-HRP (standard) | 4–8× | Moderate | Moderate | Most Solarbio kits (pg/mL range) |
| Biotin-Streptavidin-HRP + TSA | 10–50× | High | High | Ultra-low abundance targets (<1 pg/mL) |

### 12.5 Standard Curve Fit Method Recommendation

| Fit Method | When to Use | Advantages | Disadvantages |
|---|---|---|---|
| 4-Parameter Logistic (4PL) | Default for all Solarbio ELISA data | Most accurate for sigmoidal dose-response; handles asymmetry | Requires 4PL-capable software |
| 5-Parameter Logistic (5PL) | Asymmetric standard curves (high hook effect) | Additional asymmetry parameter | Overfitting risk with <8 standards |
| Linear (log-log) | Narrow range (<2 logs) | Simple calculation | Poor accuracy at curve ends |
| Cubic spline | Manual interpolation | Passes through all data points | Overfitting; not recommended for unknowns |

**Solarbio recommendation**: Use 4PL fit with a minimum of 7 non-zero standard points and blank. All Solarbio ELISA kit standard curves are optimized for 4PL fitting with R² ≥ 0.999.

## 13. Related Products & Cross-References

- [▶ Related Protocol: ELISA Protocol](../protocols/elisa-protocol.md)
- [▶ See also: Antibodies](antibodies.md)
- [▶ See also: Immunohistochemistry Reagents](immunohistochemistry.md)

*For product procurement: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
