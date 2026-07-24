---
title: "Troubleshooting Guide"
description: "Common issues and solutions for Solarbio products — PCR, qPCR, DNA extraction, RNA extraction, ELISA, western blot, cell culture, enzyme activity assays, and competent cell transformation."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Troubleshooting Guide",
 "description": "Common issues and solutions for Solarbio products — PCR, qPCR, DNA extraction, RNA extraction, ELISA, western blot, cell culture, enzyme activity assays, and competent cell transformation.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Troubleshooting Guide

This guide covers common issues encountered when using Solarbio products across all product categories. Each section provides symptom descriptions, likely causes, tested solutions, and preventive measures. Use the table of contents to navigate to the relevant product category.

---

## General Principles for Troubleshooting

| Principle | Recommendation |
|---|---|
| Control reactions | Always include positive and negative controls in every experiment. A failing positive control indicates reagent or setup failure; a failing negative control indicates contamination. |
| Lot traceability | Record the lot number of every kit component. If an issue is traced to a specific lot, Solarbio QC can investigate with the lot-specific manufacturing records. |
| Systematic isolation | Change one variable at a time when troubleshooting. Changing multiple variables simultaneously makes it impossible to identify the root cause. |
| Fresh reagents | Many failures are resolved by using fresh aliquots of labile components (enzymes, substrates, standards). |

---

## PCR Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| No PCR product | Inhibitor in template | Dilute template 1:5, 1:10, 1:50 in nuclease-free water | Purify template (column cleanup) if high inhibitor load expected |
| | Primer Tm mismatch | Verify calculated Tm using nearest-neighbor method | Design primers with Tm 55–65°C and GC content 40–60% |
| | Taq polymerase inactive | Run positive control (e.g., GAPDH with 50 ng human gDNA) | Store 2×Taq MasterMix (PC1150) at −20°C; avoid >20 freeze-thaw cycles |
| | Extension time insufficient | Increase extension to 1 min per kb of target amplicon | Calculate extension time from amplicon length, not arbitrary |
| Multiple bands | Annealing temperature too low | Increase by 2–5°C; run gradient PCR (Tm ± 5°C) | Calculate theoretical Tm; use gradient PCR for new primer pairs |
| | Too much template | Reduce gDNA to 10–50 ng per 25 μL reaction; reduce cDNA to 1–2 μL of 1:10 dilution | Titrate template concentration for each new sample type |
| | Non-specific primer binding | Redesign primers (check for self-complementarity and 3′ stability) | Use Primer-BLAST or similar design tools |
| Smear on gel | Template degraded | Check template integrity on a gel | Store DNA in TE buffer; avoid freeze-thaw cycles |
| | Too many PCR cycles | Reduce to 28–30 cycles for DNA targets; reduce to 35 cycles for dilute targets | Use the minimum cycle number that produces detectable product |
| | Taq incorrect for high-GC targets | Switch to 2×Taq Plus (PC1155) for GC-rich templates | Use high-GC formulation for templates with >60% GC content |
| Faint or weak band | Insufficient template | Increase gDNA to 100 ng or cDNA to 2 μL | Optimize template amount by 3-point titration |
| | Suboptimal Mg²⁺ concentration | Mg²⁺ in standard 2×Taq MasterMix is 1.5 mM (final); supplement if needed | Standard formulation covers most templates; switch to 2×Taq Plus (PC1155) for difficult targets |
| | Low primer concentration | Increase to 0.4 μM each primer final | Start at 0.2 μM and optimize up to 0.5 μM |

---

## qPCR Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| High Ct (>35) | Low expression target | Increase cDNA input 2× (reduce dilution factor) | Use more concentrated cDNA; do not exceed 10% of reaction volume |
| | Poor primer efficiency | Redesign primers; efficiency should be 90–105% | Design amplicons 70–150 bp, Tm 58–62°C |
| | Inhibition | Dilute cDNA 1:5 or 1:10 | Purify RNA better; use on-column DNase |
| No Ct (amplification) | No template added | Check pipetting; verify cDNA preparation | Include positive control in every qPCR run |
| | Probe degraded (TaqMan) | Check probe storage and integrity | Store probes at −20°C in the dark; avoid light exposure |
| | Wrong passive reference dye | ROX concentration mismatch with instrument | Use the correct qPCR master mix for your instrument: SR1110 (ROX-free), SR1115 (low ROX), SR1118 (high ROX) |
| | Instrument settings incorrect | Verify dye channel and fluorophore selection | Set up instrument protocol before preparing reactions |
| Multiple melt peaks (SYBR Green) | Primer-dimer formation | Reduce primer concentration to 0.2 μM each | Design primers with non-overlapping 3′ ends; avoid 3′ G+C clamps |
| | Non-specific amplification | Increase annealing temperature by 2–3°C | Run melt curve analysis on every qPCR plate |
| | Contamination | Use fresh primers and master mix | Prepare master mix in a dedicated PCR hood |
| High Ct variability between replicates | Pipetting error | Use master mix; avoid pipetting <1 μL | Calibrate pipettes every 6 months |
| | Low template concentration | Concentrate cDNA or increase template volume | Ensure homogeneous solution |
| Efficiency outside 90–110% | Inhibitors in template | Dilute template further; purify RNA | Perform column cleanup after RNA extraction |
| | Primer secondary structure | Check for hairpins and dimers at annealing temperature | Use design tools with secondary structure prediction |
| Standard curve R² < 0.98 | Pipetting error in serial dilution | Prepare fresh standards; verify pipette calibration | Use a dedicated pipette for standard curve preparation |
| | Standard at low concentration unstable | Use fresh aliquots; keep on ice | Prepare single-use aliquots; store at −80°C |

---

## DNA Extraction Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| Low DNA yield | Incomplete lysis | Increase Proteinase K (P0100) incubation to 30 min at 56°C | Pre-digest tissue in lysis buffer + PK for 30 min |
| | Inefficient binding | Ensure ethanol is added to binding buffer | Check buffer labels — some require ethanol addition before first use |
| | Elution insufficient | Elute in 50 μL; repeat elution with second 50 μL and combine | Pre-warm Elution Buffer to 65°C |
| Low A₂₆₀/A₂₈₀ (<1.7) | Protein contamination | Increase Proteinase K digestion; incubate longer at 56°C | Add fresh Proteinase K at 20 mg/mL final |
| | Phenol carryover (tissue only) | Add an extra chloroform extraction step | Use pre-treatments to remove heme/heavy proteins |
| Low A₂₆₀/A₂₃₀ (<1.5) | Chaotropic salt carryover | Add extra wash step with ethanol-containing Wash Buffer | Ensure wash buffer is prepared correctly |
| DNA degraded | DNase contamination | Use fresh, DNase-free materials | Add EDTA (1 mM final) to lysis buffer if working with nucleases |
| | Freeze-thaw damage | Aliquot purified DNA; avoid repeated thawing | Store at 4°C for short-term (−20°C for long-term) |
| DNA does not digest/amplify | Ethanol carryover | Dry pellet or column by extended centrifugation | Air-dry column 2 min after final wash |
| | Co-purified inhibitors | Clean up using DNA Purification Kit (D1300) | Add extra wash steps for problematic samples |

---

## RNA Extraction Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| Low A₂₆₀/A₂₃₀ (<1.8) | Phenol/guanidine contamination (Trizol) | Re-precipitate RNA; wash pellet twice with 75% ethanol | Leave 1–2 mm margin above interphase during aqueous phase transfer |
| | Wash buffer carryover (Column) | Add an extra wash step; dry column for 2 min air centrifuge | Dry column after final wash |
| Low RNA yield | Incomplete homogenization | Increase homogenization time; grind in liquid N₂ for tough tissues | Use fresh, RNase-free homogenizer probe |
| | Inadequate starting material | Use 50 mg tissue (not <20 mg) | For very small samples, add carrier RNA (R1100) |
| RNA degraded (smear, no 28S/18S bands) | RNase contamination | Always use RNase-free water (R1600); spray surfaces with 70% ethanol | Wear gloves at all times; change frequently |
| | Sample not fresh | Snap-freeze in liquid N₂ immediately after collection; store at −80°C | Use RNAlater if liquid N₂ is unavailable |
| | Repeated freeze-thaw | Snap-freeze only once; aliquot tissue | Store extracted RNA at −80°C in single-use aliquots |
| gDNA contamination | Interphase disturbed (Trizol) | Transfer less aqueous phase | Do not attempt to recover every drop of aqueous phase |
| | DNase step too short (Column) | Incubate DNase I for full 15 min at RT | Do not skip or shorten the DNase incubation |

---

## ELISA Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| High background (OD > 1.5 in blank) | Insufficient washing | Increase wash steps to 5–7; increase wash buffer volume to 300 μL/well | Use an automatic plate washer for consistent wash volume |
| | Blocking insufficient | Use fresh blocking buffer; block for 1 h at RT | Do not reuse blocking buffer |
| | TMB substrate contaminated | Substrate should be colorless; discard if blue | Store TMB at 2–8°C in the dark |
| | Secondary antibody concentration too high | Reduce HRP-secondary dilution 2–4× | Titrate secondary antibody for each new lot |
| Low signal (OD < 0.5 for high standard) | Standard degraded | Prepare fresh standards; do not reuse reconstituted standards | Reconstituted standards are stable for 1 h at RT or store at −20°C for 1 month |
| | Incubation time too short | Extend primary or secondary incubation to overnight at 4°C | Follow kit protocol precisely |
| | Substrate incubation too short | Extend TMB incubation to 15–30 min at RT (protect from light) | Positive control should reach OD 1.0–2.0 within the incubation window |
| | Stop solution old | Prepare fresh 0.2 M H₂SO₄ or 1 M HCl | Stop solution is stable at RT; discard if visibly contaminated |
| Poor standard curve (R² < 0.98) | Serial dilution error | Verify pipetting; prepare fresh standard curve | Use reverse pipetting technique for viscous standards |
| | Standard at upper end saturated | Check hook effect; increase dilution of high standard | Use the standard range provided in the datasheet |
| Well-to-well variation | Edge effect | Pre-warm the plate to RT before opening; seal plate during incubation | Use sealers; do not stack plates |
| | Bubbles in wells | Tap plate gently before reading; use thin-needle to burst bubbles | Avoid vigorous mixing; let settled for 1 min before reading |

---

## Western Blot Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| No signal | Insufficient protein | Load 50–80 μg total protein per lane for low-abundance targets | Quantify all lysates by BCA assay (BC3180) before loading |
| | Transfer failed | Verify membrane orientation; check for air bubbles in sandwich | Stain with Ponceau S immediately after transfer to confirm |
| | Antibody does not recognize target | Check species reactivity on antibody datasheet | Use positive control lysate for each new antibody |
| High background | Insufficient blocking | Block overnight at 4°C | Use 5% milk for most targets; 5% BSA for phospho-targets |
| | Antibody concentration too high | Reduce primary antibody 2×; reduce secondary 2× | Titrate each new antibody lot |
| | Wash steps insufficient | Wash 5 × 5 min in TBST with shaking | Use 10 mL TBST per mini-blot; change wash vessel |
| Multiple bands | Non-specific antibody binding | Reduce primary dilution; check for cross-reactivity | Use peptide-blocking control where available |
| | Protein degradation | Add fresh PIC to lysis buffer | Work on ice for all extraction steps |
| High background spots | Antibody aggregates | Centrifuge antibody at 12,000×g, 10 min before use | Filter through 0.22 μm spin filter |
| Weak or streaky bands | Transfer orientation issue | Verify gel-to-membrane orientation | Label membrane corner before assembly |
| | Insufficient reducing agent | Add fresh β-ME (5% v/v) or DTT (100 mM) to sample buffer | Add reducing agent immediately before use |

---

## Cell Culture Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| Cells not attaching | Trypsin over-treatment | Reduce incubation time; verify cells before they float | Check under microscope every 60 seconds |
| | Mycoplasma contamination | Test and treat with mycoplasma removal agent | Quarantine all new cell lines for 2 weeks |
| | Vessel needs coating | Use poly-L-lysine or collagen coating | Check cell line requirements before seeding |
| Slow growth | Mycoplasma infection | PCR test culture supernatant; discard if positive | Routine monthly mycoplasma testing |
| | Medium pH incorrect | Replace with fresh complete medium | Monitor phenol red color daily |
| | CO₂ levels unstable | Calibrate CO₂ sensor | Check CO₂ level weekly |
| Cell death after thaw | DMSO toxicity | Centrifuge cells immediately after thaw to remove DMSO | Do not leave cells in freezing medium at RT for >5 min |
| | Freezing medium without FBS | Always use FBS-containing freezing medium (70% medium, 20% FBS, 10% DMSO) | Prepare freezing medium fresh and keep on ice |
| Bacterial contamination | Poor aseptic technique | Discard all open media bottles; clean incubator | Review aseptic technique with all lab members |

---

## Competent Cell Transformation Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| No colonies | Cells not competent | Test with pUC19 control DNA; efficiency should be ≥1 × 10⁸ CFU/μg | Store cells at −80°C; thaw only once |
| | Heat shock temperature wrong | Calibrate 42°C water bath with a thermometer | Check water bath calibration monthly |
| | Heat shock timing wrong | Time exactly 45 s with a timer | Use a timer; do not approximate |
| | Antibiotic concentration too high | Reduce antibiotic to recommended concentration | Check antibiotic stock; store at 4°C (dark) |
| Satellite colonies | Antibiotic degraded (ampicillin) | Use fresh ampicillin plates (≤4 weeks old) | Prepare amplicillin plates fresh; store at 4°C |
| | Incubation >18 h | Harvest colonies at 14–16 h | Set plate incubation timer |
| Lawn of colonies (no selection) | No antibiotic in plate | Verify plate preparation | Always include a no-DNA negative control |
| Blue-white screening fails | IPTG or X-Gal not added | Add IPTG (0.1 mM) and X-Gal (40 μg/mL) to plates before use | Prepare induction plates fresh; store X-Gal at −20°C |

---

## Enzyme Activity Assay Troubleshooting

| Symptom | Cause | Solution | Prevention |
|---|---|---|---|
| Absorbance outside linear range | Sample too concentrated | Dilute homogenate 1:5, 1:10, 1:20 with assay buffer and re-assay | Run a pre-test with 3 dilutions for new sample types |
| | Tray or cuvette dirty | Clean cuvettes with 70% ethanol; use fresh microplates | Handle plates by edges only |
| Standard curve non-linear | Substrate or standard degraded | Prepare fresh working solutions | Store substrate and standards as recommended; aliquot |
| | Pipetting errors | Use calibrated pipettes; reverse pipetting for viscous solutions | Verify pipette calibration every 6 months |
| No reaction (zero absorbance) | Missing essential reagent (substrate, enzyme, cofactor) | Review protocol and confirm all components added | Prepare a checklist for each assay |
| | Incubation time too short | Extend to maximum protocol time | Use kinetic (rate) assays at multiple time points for problematic samples |
| High variability (CV > 15%) | Incomplete lysis/homogenization | Homogenize more thoroughly; centrifuge at higher g-force | Ensure all visible tissue fragments are homogenized |
| | Uneven temperature across plate | Pre-warm plate in incubator before adding substrate; seal if possible | Run color development at constant temperature |
| Interference from sample matrix | Hemoglobin, bilirubin, or lipid interference | Run sample blank for each sample; subtract from sample reading | Prepare appropriate sample blanks for colored or turbid samples |

---

*For further technical support: [solarbio.store](https://solarbio.store)*
