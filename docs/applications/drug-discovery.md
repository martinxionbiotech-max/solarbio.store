---
title: "Drug Discovery Applications"
description: "Solarbio products supporting drug discovery workflows — target identification, HTS assays, lead optimization, and preclinical testing."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Drug Discovery Applications",
 "description": "Solarbio products supporting drug discovery workflows — target identification, HTS assays, lead optimization, and preclinical testing.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Drug Discovery Applications

## Workflow Integration

| Phase | Solarbio Products | Key Assays | Example SKUs |
|---|---|---|---|
| Target identification | Enzyme activity kits, cell assay kits | Kinase profiling, receptor binding | BC-series kits |
| Hit validation | Dose-response assays, IC₅₀ determination | Cell viability (CCK-8, MTT), apoptosis | CA1210, M1020 |
| Lead optimization | ADME/Tox screening, cell viability | Cytotox assays, oxidative stress panels | BC-series, CA-series |
| Preclinical | Biomarker ELISA kits, oxidative stress panels | Cytokine panels, tissue biomarkers | SEKH-series, BC-series |
| Mechanism of action | Cell signaling kits, apoptosis detection | Western blot, Annexin V | KGA-series, CA1020 |

## Key Applications

### Cell Viability and Cytotoxicity

| Assay | Principle | Detection Method | Readout | Throughput |
|---|---|---|---|---|
| CCK-8 (CA1210) | WST-8 reduction by cellular dehydrogenases | Absorbance 450 nm | % viability compared to control | 96/384-well |
| MTT (M1020) | MTT reduction to formazan | Absorbance 570 nm | % viability | 96-well |
| LDH Release (BC0655) | Extracellular LDH from damaged cells | Colorimetric 490 nm | % cytotoxicity | 96-well |
| Trypan Blue | Dye exclusion by viable cells | Manual counting on hemocytometer | Count/mL, % viability | Any format |

### Apoptosis Detection

| Assay | SKU | Principle | Detection | Application |
|---|---|---|---|---|
| Annexin V-FITC/PI | CA1020 | Phosphatidylserine externalization | Flow cytometry (FITC/PI channels) | Early vs. late apoptosis |
| TUNEL | CA1050 | DNA fragmentation (3'-OH ends) | Fluorescence microscopy or flow | Late apoptosis |
| Caspase-3 Activity | BC3830 | DEVD-pNA cleavage | Absorbance 405 nm | Caspase activation |
| JC-1 (Mitochondrial membrane potential) | M8650 | J-aggregate formation | Fluorescence: 530/590 nm | Mitochondrial dysfunction |

### ADME/Tox Screening

| Assay | Product | Parameter | Sample Types |
|---|---|---|---|
| Oxidative stress panel | SOD (BC0175), CAT (BC0205), GSH (BC1175) | Antioxidant status | Cell lysate, tissue, serum |
| Hepatotoxicity | ALT (BC1555), AST (BC1565), LDH (BC0655) | Liver enzyme release | Culture medium, serum |
| Metabolic activity | ATP (BC0305), Glucose (BC2505), Lactate (BC4805) | Energy metabolism | Cell lysate, medium |
| CYP450 activity | Custom substrate-based | CYP isoform-specific activity | Microsomes, hepatocytes |

## Assay Optimization Guidance

| Factor | Recommendation | Rationale |
|---|---|---|
| Cell density optimization | 5,000–20,000 cells/well for 96-well; 1,000–5,000 for 384-well | Linear range for CCK-8/MTT; avoid confluence >80% |
| Compound DMSO tolerance | Keep DMSO final concentration ≤0.1% (v/v) | DMSO at >0.5% affects cell viability and enzyme activity |
| Incubation time | 1–4 h for CCK-8 (37°C, 5% CO₂); 2–4 h for MTT | Longer incubation increases sensitivity but may reduce linearity |
| Positive controls | Staurosporine (1 µM, 6 h) for apoptosis; Triton X-100 (0.5%, 1 h) for cytotoxicity | Standard inducers for assay validation |
| IC₅₀ determination | 8-point, 3-fold serial dilution in triplicate | Minimum 8 points for 4-parameter logistic fit; R² >0.98 required for publication |

## Equipment Recommendations

| Assay Format | Recommended Instrument | Specification |
|---|---|---|
| 96-well absorbance | BioTek Epoch, Thermo Multiskan GO | Dual wavelength reading capability |
| 384-well assay | Molecular Devices SpectraMax i3x | High-speed monochromator |
| Flow cytometry apoptosis | BD FACSCanto, CytoFLEX | 488 nm laser + FITC/PE channels |
| Fluorescence microscopy | Zeiss Axio Observer, Leica DMI6000 | DAPI/FITC/TRITC filter sets |
| Chemiluminescence | BioTek Synergy H1 | Luminometer mode |

## Representative Data: CCK-8 Assay on HepG2 Cells

| Cisplatin (µM) | Viability (%) | SD | n |
|---|---|---|---|
| 0 | 100.0 | 3.2 | 3 |
| 1 | 94.1 | 4.1 | 3 |
| 3 | 83.5 | 3.8 | 3 |
| 10 | 58.2 | 5.0 | 3 |
| 30 | 31.7 | 4.2 | 3 |
| 100 | 12.4 | 2.1 | 3 |
| IC₅₀ | 14.3 µM | — | — |

## Cross-References

- [▶ Cell Biology Products](../cell-biology/index.md)
- [▶ Assay Kits](../assay-kits/index.md)
- [▶ Applications Index](index.md)
- [▶ Clinical Research Applications](clinical-research.md)
- [▶ Troubleshooting Guide](../protocols/troubleshooting.md)

*[solarbio.store](https://solarbio.store)*
