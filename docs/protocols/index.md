---
title: "Laboratory Protocols"
description: "Official Solarbio laboratory protocols — step-by-step validated procedures for PCR, qPCR, DNA extraction, RNA extraction, gel extraction, western blot, ELISA, enzyme activity assays, cell culture, and competent cell transformation."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Laboratory Protocols",
 "description": "Official Solarbio laboratory protocols — step-by-step validated procedures for PCR, qPCR, DNA extraction, RNA extraction, gel extraction, western blot, ELISA, enzyme activity assays, cell culture, and competent cell transformation.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Laboratory Protocols

Official step-by-step protocols for Solarbio products. Each protocol has been validated in Solarbio quality control laboratories using representative sample types and instrument configurations. Protocol times are estimates for experienced researchers; actual times may vary by sample type, batch size, and laboratory conditions.

---

## Protocol Overview

This section contains 30+ validated laboratory protocols organized by application category. Each protocol includes:

- Complete materials checklist with recommended Solarbio product SKUs
- Step-by-step instructions with technical notes, incubation times, and centrifugation parameters
- Expected results and quality check criteria at intermediate stages
- Troubleshooting guidance for common failure modes
- Optimization notes for specific sample types and scaling

---

## General Laboratory Guidelines

The following best practices apply to all protocols referenced in this documentation:

| Practice | Recommendation | Rationale |
|---|---|---|
| DNase/RNase-free consumables | Use certified nuclease-free pipette tips and tubes for all nucleic acid work | Prevents template degradation and false negatives |
| Cold chain maintenance | Keep enzymes, master mixes, and competent cells on ice during handling | Preserves enzymatic activity and transformation efficiency |
| Calibrated pipettes | Pipettes should be calibrated every 6–12 months | Ensures accurate reaction volumes, critical for qPCR reproducibility |
| Fresh aliquots | Aliquot reagents subject to freeze-thaw damage (antibodies, enzymes, standards) | Prevents activity loss from repeated freeze-thaw cycling |
| Water quality | Use nuclease-free water (SKU R1600) for molecular biology; ultrapure water (18.2 MΩ·cm) for biochemical assays | Avoids contaminating nucleases and metal ions that inhibit reactions |
| 70% ethanol sterilization | Wipe all work surfaces and pipettes before RNA work | Inactivates environmental RNases |
| Positive controls | Include a positive control in every PCR, ELISA, and enzyme activity run | Distinguishes reagent failure from sample-specific issues |
| Documentation | Record lot numbers of all kit components for each experiment | Essential for COA traceability and troubleshooting |

---

## Molecular Biology Protocols

| Protocol | Product Category | Est. Lab Time | Experience Level | Sample Types |
|---|---|---|---|---|
| [PCR Setup Guide](pcr-setup.md) | PCR master mixes (PC1150–PC1165) | 1–2 h | Beginner | DNA, cDNA |
| [qPCR Setup Guide](qpcr-setup.md) | qPCR master mixes (SR1110–SR1140) | 1.5–2 h | Intermediate | cDNA, gDNA |
| [DNA Extraction Protocol](dna-extraction-protocol.md) | Genomic DNA extraction (D1700) | 30–50 min | Beginner | Animal tissue, cells, blood |
| [Gel Extraction Protocol](gel-extraction-protocol.md) | Agarose gel DNA recovery (D1200) | 15–20 min | Beginner | Agarose gel slices |
| [RNA Extraction Protocol](rna-extraction-protocol.md) | Total RNA extraction (R1100, R1200) | 25–40 min | Intermediate | Tissue, cells, blood |
| [Competent Cell Transformation](competent-cell-transformation.md) | Competent cells (C1100, C1180, C1300) | 2 h + overnight culture | Intermediate | Plasmid DNA, ligation products |

### Molecular Biology Protocol Quick Reference

| Application | DNA Template Required | Typical Yield | Downstream Use |
|---|---|---|---|
| Routine PCR | 10–100 ng gDNA or 1–50 ng cDNA | 5–20 μg PCR product | Gel extraction, cloning |
| qPCR gene expression | 10–100 ng cDNA (per 20 μL reaction) | Ct 20–32 (typical) | Relative/absolute quantification |
| Genomic DNA extraction (tissue) | 20–50 mg tissue | 10–50 μg | PCR, sequencing, genotyping |
| Gel extraction | 50–500 ng target band | 30–400 ng recovered DNA | Ligation, sequencing |
| RNA extraction (tissue) | 30–50 mg tissue | 30–100 μg total RNA | RT-PCR, RT-qPCR, RNA-seq |
| Competent cell transformation | 0.1–10 ng plasmid or 1–5 μL ligation | 10–5000 colonies | Plasmid propagation, expression |

---

## Protein and Cell Biology Protocols

| Protocol | Product Category | Est. Lab Time | Key Applications |
|---|---|---|---|
| [Western Blot Protocol](western-blot.md) | Antibodies, ECL substrate, lysis buffers | 6–8 h (or 2 days with overnight antibody incubation) | Protein expression analysis |
| [ELISA Protocol](elisa-protocol.md) | ELISA kits (all targets, sandwich and competitive) | 3–5 h | Cytokine quantification, biomarker detection |
| [Cell Culture Protocol](cell-culture-protocol.md) | Cell culture reagents (D-PBS, trypsin, media, FBS) | 30 min per routine passage | Adherent and suspension cell maintenance |

### Key Recommendations for Protein Work

- **Protein extraction**: Always add protease inhibitor cocktail (P0100, 1:100) to RIPA lysis buffer (R0010) immediately before use. Work on ice throughout extraction to minimize proteolysis.
- **Western blot transfer**: For high-MW targets (>120 kDa), extend transfer time to 90 min at 300 mA or use 0.45 μm PVDF membrane (P1500). For low-MW targets (<20 kDa), reduce transfer to 30 min and use 0.2 μm PVDF.
- **ELISA plate coating**: If using in-house coating protocols (not Solarbio pre-coated plates), optimize coating concentration by checkerboard titration. Incubate coating buffer overnight at 4°C for maximum binding density.

---

## Biochemical Assay Protocols

| Protocol | Product Category | Est. Lab Time | Detection Method |
|---|---|---|---|
| [Enzyme Activity Assay Protocol](enzyme-assay-protocol.md) | Biochemical assay kits (all types) | 30–60 min | Colorimetric, fluorometric |
| [Troubleshooting Guide](troubleshooting.md) | All categories | Reference | N/A |

### General Considerations for Enzyme Activity Assays

- **Sample preparation**: All tissue homogenates and cell lysates should be kept at 2–8°C or on ice during preparation. Perform centrifugation at 4°C to remove debris.
- **Standard curve**: Prepare a fresh standard curve for each assay run. Use at least 5 standard points plus a blank, and verify R² ≥ 0.99 before calculating sample concentrations.
- **Reaction timing**: For kinetic (rate) assays, record the initial absorbance (t = 0) immediately after adding the final reagent, then measure at the specified intervals. The reaction rate must be linear during the measurement window.
- **Blank correction**: Include a sample blank (sample + all reagents except substrate) to correct for endogenous absorbance. If a kit does not specify a sample blank, use deionized water as the reagent blank.

---

## Protocol Selection by Application

| Research Application | Recommended Protocol(s) | Related Product Section |
|---|---|---|
| Gene expression analysis | PCR Setup, qPCR Setup, RNA Extraction | [Molecular Biology](../molecular-biology/index.md) |
| Protein expression analysis | Western Blot, Protein Extraction | [Antibodies](../immunology/antibodies.md) |
| Cytokine quantification | ELISA Protocol | [ELISA Kits](../immunology/elisa-kits.md) |
| Oxidative stress measurement | Enzyme Activity Assay | [Oxidative Stress Assays](../assay-kits/oxidative-stress.md) |
| Cell viability screening | Cell Culture Protocol | [Cell Proliferation](../cell-biology/cell-proliferation.md) |
| Gene cloning | PCR Setup, Gel Extraction, Transformation | [Cloning Reagents](../molecular-biology/cloning-reagents.md) |

---

## Quality Control and Validation

Each protocol published in this section has been validated in Solarbio's QC laboratories under the following conditions:

- **Replicates**: Each protocol was tested with a minimum of 3 independent biological replicates
- **Instruments**: Bio-Rad T100 Thermal Cycler (PCR), Bio-Rad CFX96 (qPCR), Thermo Scientific NanoDrop One (nucleic acid quantification), BioTek Synergy H1 (absorbance/fluorescence), Bio-Rad ChemiDoc MP (gel imaging and western blot)
- **Sample types**: Protocols include representative data from at least 2 different sample matrices
- **Pass criteria**: PCR efficiency 90–105% (qPCR), R² ≥ 0.99 (standard curves), CV < 15% (technical replicates), recovery 90–110% (extraction protocols)

---

## Protocol List

| Protocol | Product Category | Est. Time | Experience Level |
|---|---|---|---|
| [PCR Setup Guide](pcr-setup.md) | PCR master mixes (PC1150–PC1165) | 1–2 h | Beginner |
| [qPCR Setup Guide](qpcr-setup.md) | qPCR master mixes (SR1110–SR1140) | 1.5–2 h | Intermediate |
| [DNA Extraction Protocol](dna-extraction-protocol.md) | Genomic DNA extraction (D1700) | 30–50 min | Beginner |
| [Gel Extraction Protocol](gel-extraction-protocol.md) | Agarose gel DNA recovery (D1200) | 15–20 min | Beginner |
| [RNA Extraction Protocol](rna-extraction-protocol.md) | Total RNA extraction (R1100, R1200) | 25–40 min | Intermediate |
| [Competent Cell Transformation](competent-cell-transformation.md) | Competent cells (C1100, C1180, C1300) | 2 h + overnight | Intermediate |
| [Western Blot Protocol](western-blot.md) | Antibodies, ECL substrate | 6–8 h (or 2 days with overnight antibody) | Intermediate |
| [ELISA Protocol](elisa-protocol.md) | ELISA kits (all targets) | 3–5 h | Beginner |
| [Cell Culture Protocol](cell-culture-protocol.md) | Cell culture reagents (D-PBS, trypsin, media) | 30 min (per routine passage) | Beginner |
| [Enzyme Activity Assay Protocol](enzyme-assay-protocol.md) | Biochemical assay kits (all types) | 30–60 min | Intermediate |
| [Troubleshooting Guide](troubleshooting.md) | All categories | Reference | All levels |

---

*[solarbio.store](https://solarbio.store)*
