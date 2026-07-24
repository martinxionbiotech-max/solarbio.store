---
title: "Technical Specification: Cell Staining Reagents"
description: "Technical specifications for Solarbio cell staining products — fluorescent dyes for nuclear staining (DAPI, Hoechst, PI), mitochondrial membrane potential probes (JC-1), and cytoskeletal probes. Working concentrations, spectral data, staining protocols, and multiplex compatibility tables."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Cell Staining Reagents",
 "description": "Technical specifications for Solarbio cell staining products — fluorescent dyes for nuclear staining (DAPI, Hoechst, PI), mitochondrial membrane potential probes (JC-1), and cytoskeletal probes. Working concentrations, spectral data, staining protocols, and multiplex compatibility tables.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Cell Staining Reagents

## 1. Product Range

Solarbio cell staining reagents cover essential fluorescent probes for nuclear counterstaining, DNA content analysis, viability discrimination, and mitochondrial health assessment. These probes are validated for use in fluorescence microscopy, confocal microscopy, flow cytometry, and high-content imaging platforms.

| Product | SKU | Ex/Em (nm) | Application | Format |
|---|---|---|---|---|
| DAPI (4′,6-diamidino-2-phenylindole) | D1060 | 358/461 | Nuclear counterstain, DNA content | 5 mg/mL in DMSO, 1 mL |
| Hoechst 33258 | H1398 | 352/461 | Live cell nuclear stain | 10 mg/mL in DMSO, 1 mL |
| Hoechst 33342 | H1399 | 350/461 | Live cell nuclear stain (membrane-permeant) | 10 mg/mL in DMSO, 1 mL |
| PI (Propidium Iodide) | P8080 | 535/615 | Dead cell stain, DNA content (cell cycle) | 1 mg/mL in PBS, 1 mL |
| JC-1 Mitochondrial Membrane Potential Assay | M8650 | 514/529 (monomer), 585/590 (aggregate) | Apoptosis, mitochondrial health | 200× in DMSO, 0.5 mL |
| Calcein-AM | CA1330 | 495/515 | Viable cell stain (esterase activity) | 1 mM in DMSO, 100 μL |
| FITC-Phalloidin | CA1610 | 495/520 | F-actin cytoskeleton labeling | 50 μg, lyophilized |

## 2. Spectral Properties and Working Concentrations

### 2.1 Nuclear Stains

| Stain | Stock Solution | Working Concentration | Excitation Source | Staining Pattern |
|---|---|---|---|---|
| DAPI | 5 mg/mL in DMSO (store -20°C, dark) | 0.5–1 μg/mL | 358 nm (UV, 405 nm laser) | Nucleus; AT-rich regions brighter |
| Hoechst 33342 | 10 mg/mL in DMSO (store -20°C, dark) | 1–10 μg/mL | 350 nm (UV, 355 nm laser) | Nucleus; live cell permeable (30 min labeling) |
| Hoechst 33258 | 10 mg/mL in DMSO | 1–10 μg/mL | 352 nm | Nucleus; less permeable than 33342 |
| PI (viability) | 1 mg/mL in PBS (store 2–8°C, dark) | 1–5 μg/mL | 535 nm (488 nm laser, >585 nm emission) | Nucleus; only permeabilized/dead cells |

### 2.2 Functional Probes

| Probe | Stock | Working Dilution | Incubation | Application Notes |
|---|---|---|---|---|
| JC-1 | 200× in DMSO (store -20°C, dark) | 1× in culture medium | 15–30 min at 37°C | Red/green ratio measures ΔΨm depolarization |
| Calcein-AM | 1 mM in DMSO (store -20°C, dark) | 0.5–5 μM | 15–30 min at 37°C | Non-fluorescent until cleaved by intracellular esterases |
| FITC-Phalloidin | Reconstitute in 1.5 mL methanol (store -20°C) | 1:40–1:200 | 20–40 min at RT (dark) | Requires fixation (4% PFA) and permeabilization |

## 3. Dye Mechanism Details

### DAPI

DAPI (C₁₆H₁₅N₅·2HCl, MW 350.25) binds non-fluorescently to the minor groove of dsDNA, with strong preference for AT-rich sequences (binding constant ~10⁶ M⁻¹). Upon binding, its fluorescence quantum yield increases approximately 20-fold.

```
DAPI (free, low fluorescence)  +  dsDNA  →  DAPI-DNA complex (20× brighter)
                                            λmax ex: 358 nm, λmax em: 461 nm
```

### JC-1

JC-1 (5,5′,6,6′-tetrachloro-1,1′,3,3′-tetraethylbenzimidazolylcarbocyanine iodide) is a cationic carbocyanine dye that accumulates in the mitochondrial matrix in proportion to the mitochondrial membrane potential (ΔΨm). At low concentrations (depolarized mitochondria), JC-1 exists as green-fluorescing monomers (Ex/Em 514/529 nm). At high concentrations (polarized mitochondria, ΔΨm > -140 mV), JC-1 forms J-aggregates with red fluorescence (Ex/Em 585/590 nm). The ratio of red to green fluorescence provides a sensitive, ratiometric measure of ΔΨm.

```
JC-1 (monomer, green)  ←→  JC-1 (J-aggregate, red)
  (depolarized ΔΨm)            (polarized ΔΨm > -140 mV)
  
Ratio: A₅₉₀ / A₅₂₉ — decrease indicates mitochondrial depolarization
```

## 4. Multiplex Compatibility

| Primary Probe | Compatible Counterstain | Notes |
|---|---|---|
| FITC-phalloidin (green) | DAPI (blue) | Minimal spectral overlap |
| Calcein-AM (green) | PI (red) | Standard live/dead assay |
| JC-1 (green/red) | None needed | Ratiometric; avoid co-staining with overlapping spectra |
| FITC-labeled antibodies | DAPI | IF + nuclear counterstain |
| GFP-expressing cells | PI or DAPI | Cell cycle + reporter analysis |
| Alexa Fluor 555/594 | DAPI | Fixed cell imaging |

## 5. Recommended Protocols

### Nuclear Staining (Fixed Cells)

| Step | Detail |
|---|---|
| Fixation | 4% paraformaldehyde, 15 min at RT |
| Permeabilization | 0.1–0.5% Triton X-100 in PBS, 10 min at RT |
| Wash | 3× PBS, 5 min each |
| DAPI staining | Add 300 nM DAPI (0.5 μg/mL) in PBS, 5 min at RT |
| Wash | 1× PBS, 5 min |
| Mount | Anti-fade mounting medium; seal coverslip |
| Image | DAPI filterset (Ex 340–380 nm, Em 435–485 nm) |

### JC-1 Mitochondrial Membrane Potential Assay

| Step | Detail |
|---|---|
| Seed cells | 1×10⁵ cells/mL, 200 μL culture medium (96-well or chamber slide) |
| Treatment | Add experimental agents (e.g., FCCP 10 μM as positive control, 30 min) |
| Prepare JC-1 | Dilute 200× stock to 1× in pre-warmed culture medium (37°C) |
| Load cells | Replace medium with 100 μL 1× JC-1; incubate 15–30 min at 37°C, 5% CO₂ |
| Wash | 2× with warm PBS or culture medium |
| Read | Fluorescence plate reader: Ex 485 nm, Em 535 nm (monomer); Ex 560 nm, Em 595 nm (aggregates) |
| Calculate | Ratio = F₅₉₀ / F₅₂₉ |

### Live/Dead Cell Viability Assay

| Step | Detail |
|---|---|
| Prepare staining solution | Calcein-AM (1:1000 = 1 μM final) + PI (1:1000 = 1 μg/mL) in PBS |
| Stain cells | Add solution to cells; incubate 15–30 min at RT, dark |
| Wash | 1× with PBS |
| Image | Calcein-AM (Ex 495 nm, FITC filter); PI (Ex 535 nm, TRITC filter) |
| Interpretation | Live cells: green fluorescence only; dead cells: red fluorescence only |

## 6. Troubleshooting

| Issue | Likely Cause | Solution |
|---|---|---|
| High background, all nuclei stain weakly | Stain concentration too high | Reduce probe concentration 2–5× |
| Patchy nuclear staining | Fixation or wash incomplete | Increase permeabilization time; ensure thorough washing |
| JC-1 does not show red aggregates | Mitochondria depolarized; wrong culture conditions | Use FCCP positive control; verify cells are healthy; warm all solutions to 37°C |
| Calcein-AM leaks out of cells | Over-staining or prolonged incubation | Reduce loading time; wash thoroughly and image immediately |
| PI stains all cells including control | Cells damaged during harvesting | Gentle dissociation; include live cell gate in flow cytometry |

## 7. Cross-References

- [▶ See also: Apoptosis Detection Kits](apoptosis-detection.md)
- [▶ See also: Flow Cytometry Reagents](../immunology/flow-cytometry.md)
- [▶ Related Protocol: Cell Culture Protocol](../protocols/cell-culture-protocol.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
