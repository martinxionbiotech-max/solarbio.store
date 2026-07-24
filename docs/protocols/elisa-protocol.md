---
title: "Sandwich ELISA Protocol"
description: "Official Solarbio protocol for sandwich ELISA using Solarbio ELISA kits. Complete step-by-step instructions including reagent preparation, plate coating, blocking, antibody incubation, TMB detection, wash protocol optimization, standard curve generation, and data analysis with 4-parameter logistic fit."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Sandwich ELISA Protocol",
 "description": "Official Solarbio protocol for sandwich ELISA using Solarbio ELISA kits. Complete step-by-step instructions including reagent preparation, plate coating, blocking, antibody incubation, TMB detection, wash protocol optimization, standard curve generation, and data analysis with 4-parameter logistic fit.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Sandwich ELISA Protocol

Generic protocol for Solarbio sandwich ELISA kits. This protocol is suitable for all Solarbio pre-coated ELISA kits (cytokines, hormones, biomarkers, and immunoglobulins). For kits requiring specific modifications, refer to the product-specific datasheet.

---

## Equipment and Reagents Checklist

| Item | Recommended Specification | Purpose |
|---|---|---|
| Microplate reader | Capable of 450 nm and 540/570 nm | Absorbance measurement |
| Incubator | 37°C ± 1°C | Assay incubation steps |
| Multi-channel pipette | 8- or 12-channel, 20–200 μL | Sample/antibody/reagent addition |
| Single-channel pipettes | 10 μL, 100 μL, 1000 μL | Standard dilution, reconstitution |
| Reagent reservoirs | 25–50 mL | Multi-channel pipetting |
| Wash bottle or auto-washer | Adjustable volume | Washing steps |
| Distilled/deionized water | 18 MΩ·cm resistivity | Wash buffer dilution |
| Vortex mixer | — | Reagent mixing |
| Microcentrifuge | — | Brief spin for reconstituted reagents |
| Sealing film | Adhesive, provided in kit | Cover plate during incubation |
| Paper towels | Lint-free | Blotting plate after wash |

---

## Reagent Preparation

| Component | Preparation | Stability |
|---|---|---|
| Wash Buffer (1×) | Dilute 20× concentrate with distilled water (e.g., 50 mL concentrate + 950 mL water) | 2 weeks at RT |
| Standard | Reconstitute with the volume indicated on vial label; let stand 15 min at RT; no vortexing | 1 h at RT; 2 weeks at -20°C |
| Standard serial dilutions | Prepare 7 serially diluted tubes (7-point curve) plus 1 zero standard (diluent only) | Prepare fresh, use within 1 h |
| Detection antibody | Dilute in antibody diluent as indicated on vial label | 30 min at RT (do not store diluted) |
| HRP-Streptavidin | Dilute 1:100–1:200 in diluent (or as per kit instruction) | 30 min at RT (do not store diluted) |
| TMB Substrate | Ready to use; bring to room temperature (20–25°C) | Stable at 2–8°C (dark); warm to RT before use |
| Stop Solution | 2N H₂SO₄, ready to use; contains strong acid | Stable at RT (handle with gloves) |

### Standard Serial Dilution Protocol (7-point + Zero)

1. Label 8 microcentrifuge tubes: S1 (top standard) through S7, plus S0 (zero/blank)
2. Reconstitute lyophilized standard as per vial label to obtain the top standard concentration
3. Add 200 μL of Assay Diluent to tubes S2–S7
4. Transfer 200 μL from S1 to S2; mix by pipetting (do not vortex)
5. Continue 2-fold serial dilutions: 200 μL from S2 → S3, S3 → S4, etc.
6. For S0 (zero standard), use 200 μL Assay Diluent only
7. Dispense 100 μL per well in duplicate for each standard

```
S1 ──200 μL──→ S2 ──200 μL──→ S3 ──200 μL──→ S4 ──200 μL──→ S5 ──200 μL──→ S6 ──200 μL──→ S7
│                │                │                │                │                │                │
Top conc        1:2              1:4              1:8              1:16             1:32             1:64
```

---

## Detailed Protocol (Pre-coated Plate Format)

### Step 1: Equilibrate and Prepare Plate

| Detail | Time | Notes |
|---|---|---|
| Remove plate from sealed pouch | — | Bring to room temperature (20–25°C) before opening |
| Equilibrate to RT | 20 min | Condensation on plate = not fully equilibrated |
| Remove unused strips | — | Reseal with desiccant; store at 2–8°C |

### Step 2: Standard and Sample Incubation

| Detail | Time | Notes |
|---|---|---|
| Add 100 μL standard or sample to designated wells | — | Run all standards and samples in duplicate |
| Seal plate with adhesive film | — | Ensure complete seal to prevent evaporation |
| Incubate at 37°C | 2 h | Alternatively, overnight at 4°C for low-abundance targets (increases sensitivity ~2×) |

**Quality check:** After incubation, inspect wells for uniform liquid volume; evaporation indicates poor seal.

### Step 3: Wash

| Detail | Volume | Cycles |
|---|---|---|
| Aspirate contents | — | Blot plate inverted on paper towel |
| Add Wash Buffer | 300 μL/well | Do not overflow wells |
| Let soak | 30 s | Critical for complete removal of unbound material |
| Aspirate | — | Complete removal; blot between cycles |
| Repeat | — | 5 total wash cycles |
| Final blot | — | Firm blot on clean paper towel; no residual buffer |

### Step 4: Detection Antibody

| Detail | Time | Notes |
|---|---|---|
| Add 100 μL biotinylated detection antibody | — | Dilute immediately before use |
| Seal plate | — | — |
| Incubate at 37°C | 1 h | — |

### Step 5: Wash

Repeat Step 3 — 5 wash cycles with 30 s soak each.

### Step 6: HRP-Streptavidin

| Detail | Time | Notes |
|---|---|---|
| Add 100 μL HRP-Streptavidin working solution | — | Protect from light; cover plate with foil or black lid |
| Incubate at 37°C in dark | 30 min | — |

### Step 7: Wash (Critical Step)

| Detail | Volume | Cycles |
|---|---|---|
| Wash as before, but increase to 7 cycles | 300 μL/well | This thorough wash is critical to remove unbound HRP-streptavidin |
| Increase soak time for cycles 5–7 | 45–60 s | Lower background |

### Step 8: TMB Substrate

| Detail | Time | Notes |
|---|---|---|
| Add 90 μL TMB substrate to each well | — | Pre-warmed to RT; protect from light |
| Incubate at 37°C in dark | 15–30 min | Blue color develops |
| Monitor visually | — | High standard should show deep blue (A₄₅₀ ~2.0) |
| Do NOT shake plate during incubation | — | Shaking accelerates non-specific color development |

### Step 9: Stop and Read

| Detail | Time | Notes |
|---|---|---|
| Add 50 μL Stop Solution | — | In same order as TMB addition; color changes blue → yellow |
| Gently tap plate | — | Ensure complete mixing |
| Read at 450 nm (reference 540 or 570 nm) | Within 15 min | Signal decays ~1% per 5 min after stopping |

---

## Data Analysis

### Standard Curve Generation

| Fit Method | Recommendation | Formula |
|---|---|---|
| 4-Parameter Logistic (4PL) | Preferred; best for sigmoidal ELISA curves | y = A + (D−A) / (1 + (x/C)^B) |
| Cubic spline | Acceptable for most targets | — |
| Linear (log-log) | Only for very narrow linear range | Not recommended for full curve |

**4PL parameters:**
- A = Bottom asymptote (zero standard signal)
- B = Hill slope (curve steepness; typical 0.8–1.5)
- C = EC₅₀ (inflection point concentration)
- D = Top asymptote (saturating signal)

### Calculation Example (Mouse IL-6, EM0042)

| Well | Standard (pg/mL) | A₄₅₀ | Corrected (Blank-Subtracted) |
|---|---|---|---|
| Blank | 0 | 0.055 | — |
| S1 | 500 | 2.345 | 2.290 |
| S2 | 250 | 1.532 | 1.477 |
| S3 | 125 | 0.891 | 0.836 |
| S4 | 62.5 | 0.482 | 0.427 |
| S5 | 31.2 | 0.265 | 0.210 |
| S6 | 15.6 | 0.154 | 0.099 |
| S7 | 7.8 | 0.098 | 0.043 |

**Acceptance criteria:**
- R² (4PL fit) > 0.98
- Blank CV < 10%
- Duplicate CV < 10%
- Recovery of quality control sample within 80–120%

---

## Optimization Notes

| Parameter | Standard Protocol | Optimized Protocol | When to Use |
|---|---|---|---|
| Sample incubation | 2 h at 37°C | Overnight at 4°C | Low-abundance targets (<10 pg/mL expected) |
| TMB incubation | 15 min at 37°C | 20–30 min at 37°C | When signal is weak after 15 min |
| Wash cycles (HRP step) | 7 cycles | 10 cycles with 60 s soak | High-background samples (serum, plasma) |
| Standard reconstitution | 15 min at RT | 30 min at RT with gentle agitation for high-MW targets | TGF-β1, large cytokines |
| Sample pre-treatment | — | Heat or acid activation | TGF-β1 (acid activation), complement proteins |

---

## Troubleshooting

| Problem | Likely Cause | Solution |
|---|---|---|
| Low signal (all wells) | Kit expired; TMB degraded; HRP inactive | Check expiry date; test TMB with 1 μL HRP (should turn blue in 1 min) |
| High background (blank ≥ 0.1 A₄₅₀) | Insufficient washing; TMB contaminated | Increase wash to 7× with 60 s soak; verify TMB is not green before use |
| High duplicate variation (CV > 15%) | Inconsistent pipetting; edge effects | Calibrate pipettes; use multi-channel; pre-warm plate to RT; seal thoroughly |
| Non-linear standard curve | 4PL fit not applied; pipetting error in serial dilution | Use 4PL regression; verify serial dilution accuracy (2-fold ± 5%) |
| Low sensitivity (cannot detect low standard) | Insufficient amplification; too short TMB time | Extend TMB to 30 min; verify antibody and HRP dilutions |
| Hook effect (high sample reads lower than expected) | Antigen concentration exceeds antibody capacity | Dilute sample 1:5 in Assay Diluent and re-test |
| Edge effect (outer wells different from inner) | Temperature gradient during incubation | Use pre-warmed plate; avoid stacking plates; use sealing film |

---

## Cross-References

- [▶ See also: ELISA Kits Technical Specifications](../immunology/elisa-kits.md)
- [▶ See also: Antibodies](../immunology/antibodies.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
