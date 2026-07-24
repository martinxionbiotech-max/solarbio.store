---
title: "Enzyme Activity Assay Protocol"
description: "Official Solarbio protocol for general enzyme activity measurement using biochemical assay kits. Includes sample preparation for tissue, cells, serum/plasma, reaction setup, calculation methods with extinction coefficients, troubleshooting table, and optimization guidelines for kinetic and endpoint assays."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "HowTo",
 "name": "How to perform an enzyme activity assay using Solarbio biochemical kits",
 "description": "Step-by-step protocol for enzyme activity measurement from biological samples using Solarbio assay kits — sample preparation, reaction setup, calculation, quality control, and troubleshooting.",
 "totalTime": "P1H",
 "supply": ["Solarbio enzyme activity assay kit", "Spectrophotometer or microplate reader", "Homogenizer", "Centrifuge", "Precision micropipettes", "Water bath or incubator", "Ice", "Quartz cuvette (for UV assays 340 nm)"]
}
</script>

# Enzyme Activity Assay Protocol

Generic protocol for Solarbio spectrophotometric enzyme activity assay kits. Optimized for microplate and cuvette-based measurements.

## 1. Equipment and Reagents Checklist

### Required Equipment

| Equipment | Specification | Purpose |
|---|---|---|
| Spectrophotometer or microplate reader | UV-capable (340 nm for NADH); visible range (405–660 nm) | Absorbance measurement |
| Quartz cuvette (UV assays) | 1 cm path length, 100–500 μL capacity | For 340 nm NAD(P)H measurements |
| Polystyrene cuvette (visible assays) | 1 cm path length | For 400–660 nm chromogen assays |
| 96-well microplate | Flat-bottom, clear | High-throughput (200–300 μL well volume) |
| Precision micropipettes | 2–20 μL, 20–200 μL, 100–1000 μL | Accurate reagent dispensing |
| Water bath or incubator | 37°C ± 0.5°C | Temperature-controlled incubation |
| Microcentrifuge | 10,000–15,000×g | Sample clarification |
| Homogenizer | Glass Teflon homogenizer or bead mill | Tissue/cell homogenization |
| Ice bucket | — | Keep samples and reagents cold |
| Timer | ±1 s accuracy | Timing kinetic reactions |
| Vortex mixer | — | Mixing reaction components |
| Aluminum foil | — | Protect light-sensitive reagents (NADH, DCFH-DA) |

### Consumables

| Item | Recommended Specification |
|---|---|
| Microcentrifuge tubes | 0.5 mL, 1.5 mL, 2.0 mL (polypropylene) |
| Pipette tips | Filter tips recommended for RNA/DNA work |
| Cuvettes | Quartz (UV) or polystyrene (visible) |
| 96-well plates | Clear flat-bottom, non-binding surface preferred |

## 2. Sample Preparation

### Tissue Homogenization

| Step | Action | Time | Notes |
|---|---|---|---|
| 1 | Harvest and weigh tissue (0.05–0.1 g wet weight) | 2 min | Blot dry on filter paper; use saline wash for blood-rich tissues |
| 2 | Place in pre-cooled homogenization tube | — | Pre-chill tube on ice |
| 3 | Add 10 volumes (w/v) of ice-cold kit extraction buffer | 1 min | Volume = 1 mL per 0.1 g tissue |
| 4 | Homogenize at 4°C (glass Teflon or bead mill) | 1–3 min | Keep tube in ice water; avoid foaming |
| 5 | Centrifuge 8,000–10,000×g at 4°C | 10 min | Use refrigerated centrifuge |
| 6 | Collect supernatant, transfer to fresh tube on ice | 1 min | Avoid pellet; keep supernatant on ice |
| 7 | Dilute if needed in kit-specific diluent | — | See individual kit instructions |
| 8 | Proceed to assay | — | Complete within 2 h (or aliquot and freeze at -80°C) |

### Cell Lysate Preparation

| Step | Action | Time | Notes |
|---|---|---|---|
| 1 | Harvest cells (1×10⁶ for most assays) | 5 min | Trypsinize or scrape adherent cells |
| 2 | Wash 2× with cold PBS (pH 7.4) | 5 min | Centrifuge 300×g, 5 min, 4°C |
| 3 | Resuspend pellet in 200–500 μL extraction buffer | 1 min | Use kit-specific buffer |
| 4 | Sonicate 3×10 s pulses on ice | 1 min | Avoid foaming; 20% amplitude |
| 5 | Centrifuge 10,000×g, 10 min, 4°C | 10 min | Remove debris |
| 6 | Collect supernatant | 1 min | For cytosolic enzyme assays |
| 7 | Assay same day or store at -80°C | — | Avoid repeated freeze-thaw |

### Serum/Plasma

- **Serum**: Allow blood to clot 30 min at RT, centrifuge 1,000–2,000×g for 15 min at 4°C. Collect supernatant.
- **Plasma**: Use heparin or EDTA as anticoagulant. Centrifuge at 1,000–2,000×g for 10 min at 4°C.
- **Dilution**: Most serum assays require 1:2–1:10 dilution in PBS or kit diluent. For ALT/AST, use undiluted serum.

**Quality Check**: Hemolyzed samples yield invalid results for LDH, AST, and most RBC-rich enzyme assays. If hemolysis is visible (>0.1 g/L hemoglobin), reject the sample.

## 3. Reaction Setup

### Generic Protocol for Kinetic (NADH-Coupled) Assays

| Step | Component | Volume (cuvette) | Volume (96-well) |
|---|---|---|---|
| 1 | Distilled water / buffer | 700 μL | 120 μL |
| 2 | Substrate mix | 200 μL | 50 μL |
| 3 | Coenzyme (NADH/NADPH) | 50 μL | 50 μL |
| 4 | Sample | 50 μL | 30–50 μL |
| — | **Total** | **1000 μL** | **250–270 μL** |

| 5 | Mix gently by inversion or pipetting | — |
|---|---|---|
| 6 | Incubate at 37°C for 3 min (pre-read equilibration) | — |
| 7 | Read A₃₄₀ at t=0, then every 30 s for 3–5 min | — |
| 8 | Calculate ΔA/min | — |

### Generic Protocol for Endpoint (Chromogenic) Assays

| Step | Component | Volume (cuvette) | Volume (96-well) |
|---|---|---|---|
| 1 | Sample | 50–100 μL | 20–50 μL |
| 2 | Substrate/buffer mix | 900 μL | 200 μL |
| 3 | Mix, incubate at 37°C for specified time | — |
| 4 | Stop solution (if applicable) | 100 μL | 50 μL |
| 5 | Read absorbance at kit-specific wavelength | — |

### Control Well Setup

| Well Type | Contents | Purpose |
|---|---|---|
| Blank | Buffer + substrate (no sample) | Zero instrument and measure background rate |
| Sample blank | Sample + buffer (no substrate) | Correct for endogenous absorbance |
| Positive control | Known enzyme standard (e.g., 10 U/L) | Validate kit performance |
| Sample | Complete reaction with sample | Measure enzyme activity |
| Inhibitor control | Sample + substrate + inhibitor | Confirm enzyme specificity |

## 4. Quality Checks During Protocol

### Pre-Assay Quality Checks

| Check | Acceptable Range | Action if Out of Range |
|---|---|---|
| NAD(P)H initial A₃₄₀ | 0.8–1.5 AU | If <0.8: add fresh NADH; if >1.5: dilute |
| Sample clarity | Clear (no turbidity) | Centrifuge at 12,000×g for 5 min |
| Blank rate (ΔA/min) | <0.005/min | Remake reagents if >0.005 |
| pH of reaction mix | Within ±0.1 of kit specification | Adjust with 1 M HCl or NaOH |
| Incubation temperature | 37°C ± 0.5°C | Calibrate water bath |

### During-Assay Checks

| Check | Frequency | Action |
|---|---|---|
| Linearity of ΔA/min | Every 30 s for 5 min | If R² < 0.98, reduce sample volume or concentration |
| ΔA/min value | After first reading | If >0.2/min: dilute sample 2×; if <0.005/min: increase sample 2× |
| Temperature uniformity | At each read | Maintain 37°C; use heated plate reader |

### Post-Assay Checks

- **Duplicate CV**: If CV >10%, repeat the assay. Acceptable CV <5% for most kits.
- **Standard curve R²**: R² should be >0.99. Re-prepare standards if below.
- **Positive control activity**: Should be within 85–115% of expected value.
- **Blank value**: Should not differ from expected by >0.05 AU.

## 5. Calculation Methods

### 5.1 Kinetic Activity (NADH/NADPH) — Rate Measurement

```
Activity (U/L) = (ΔA/min) × V_total × 1000 / (ε × d × V_sample)
```

Where:
- ΔA/min = Average absorbance change per minute (linear portion)
- V_total = Total reaction volume (mL)
- ε = Molar extinction coefficient at 340 nm = 6.22 L·mmol⁻¹·cm⁻¹ for NADH
- d = Light path = 1 cm (cuvette) or 0.6 cm (200 μL/well in 96-well)
- V_sample = Sample volume (mL)
- 1000 = Conversion factor (mmol → μmol)

**Example Calculation**:
- ΔA/min = 0.042
- V_total = 1.0 mL (cuvette)
- ε = 6.22
- d = 1 cm
- V_sample = 0.05 mL

```
Activity = 0.042 × 1.0 × 1000 / (6.22 × 1 × 0.05) = 135 U/L
```

### 5.2 Endpoint Activity

```
Activity (U/L) = (A_sample − A_blank) × C_standard × Dilution / (A_standard − A_blank) × t
```

Where:
- A_sample = Sample absorbance
- A_blank = Blank absorbance
- C_standard = Standard concentration (from included calibrator)
- Dilution = Sample dilution factor
- t = Reaction time (min, for per-min units)

### 5.3 Specific Activity (per mg protein)

```
Specific activity (U/mg protein) = Activity (U/L) / Protein concentration (mg/mL)
```

See [Protein Quantification Kits](../assay-kits/protein-quantification.md) for protein quantification methods.

## 6. Troubleshooting Table

| Issue | Cause | Solution | Prevention |
|---|---|---|---|
| No activity detected (ΔA ~ 0) | Sample not added; enzyme inactive or denatured | Check pipetting; use fresh sample; add protease inhibitors | Keep samples on ice; add protease inhibitors to extraction buffer |
| Activity too high (ΔA/min > 0.2) | Sample too concentrated | Dilute sample 2–10 fold; reduce sample volume | Pre-dilute based on expected activity |
| Activity decreases over time (curving) | Substrate depleted; product inhibition; NADH consumed | Reduce sample volume; shorten measurement time | Verify linear phase; use 2× substrate concentration |
| Negative rate (absorbance increases) | Wrong direction; interfering enzyme; NADPH production | Confirm wavelength; check kit direction | Read kit protocol carefully; include sample blank |
| Irregular reading (scatter, spikes) | Bubbles in solution; precipitate formation | Tap plate; centrifuge sample; filter reagent | Mix gently; avoid SDS precipitation in Bradford |
| High blank rate (ΔA > 0.01/min) | NADH auto-oxidation; contaminated reagents | Prepare fresh NADH solution; use fresh buffer | Prepare NADH immediately before use; protect from light |
| Equal test and control (no inhibition) | Inhibitor inactive; compound inefficient | Check inhibitor concentration; increase inhibitor | Verify inhibitor stock; test dose-response |
| Ran out of NADPH before kinetic read | Sample activity too high | Dilute sample; use more NADPH (0.3 mM final) | Check sample dilution in pilot experiment |
| Sample blank shows high A | Hemoglobin, pigments, or turbidity | Centrifuge at higher speed; dilute sample | Use matched sample blank for each sample |
| Standard curve nonlinear | Pipetting error; chromogen instability | Repeat with fresh standards; use fresh chromogen | Calibrate pipettes; prepare new standards each time |

## 7. Optimization Notes

### For Different Sample Types

| Sample Type | Modification | Reason |
|---|---|---|
| Adipose tissue | Use higher detergent (0.5% deoxycholate) | High lipid content causes turbidity |
| Muscle tissue | Dilute 1:5–1:20 (high enzyme content) | High metabolic enzyme activity |
| Plant tissues | Add 1–2% PVP (polyvinylpyrrolidone) | Remove phenolic interference |
| Bacterial lysates | Add lysozyme (1 mg/mL) + sonication | Complete cell lysis |
| Culture supernatant | Concentrate 10× (Amicon 10K MWCO) | Low enzyme concentration |
| Hemolyzed serum | Reject sample (use fresh collection) | RBC enzymes inflate activity |

### Scaling Instructions

| Format | Cuvette (1 mL) | 96-well (250 μL) | 384-well (100 μL) |
|---|---|---|---|
| Sample volume | 50–200 μL | 10–50 μL | 5–20 μL |
| Total volume | 1000 μL | 250 μL | 100 μL |
| Path length | 1.0 cm | ~0.6 cm | ~0.4 cm |
| Sensitivity | Reference | ~60% of cuvette | ~40% of cuvette |

For microplate assays, multiply calculated activity by factor (1.0 / actual path length in cm). Accurate path length depends on total volume; calibrate using water absorbance at 977 nm.

## 8. Related Products & Cross-References

- [▶ Enzyme Activity Assay Kits](../assay-kits/enzyme-activity.md)
- [▶ Oxidative Stress Assay Kits](../assay-kits/oxidative-stress.md)
- [▶ Protein Quantification Kits](../assay-kits/protein-quantification.md)
- [▶ ELISA Protocol](elisa-protocol.md)
- [▶ Related Troubleshooting Guide](troubleshooting.md)

*For full product range, pricing, and ordering: [solarbio.store](https://solarbio.store)*
