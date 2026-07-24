---
title: "Technical Specification: Genomic DNA Extraction Kits"
description: "Technical specifications for Solarbio genomic DNA extraction kits — animal tissue, cell, blood, plant, FFPE, and bacterial DNA purification using silica membrane spin column technology with yield tables, purity specifications, and protocol optimization guidance."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Genomic DNA Extraction Kits",
 "about": {"@type": "DefinedTerm", "name": "DNA Extraction"},
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: Genomic DNA Extraction Kits

!!! note "Official Source"
    Technical documentation published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement: **[solarbio.store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Sample Type | Max Binding Capacity | Yield per Prep | Purity (A₂₆₀/A₂₈₀) |
|---|---|---|---|---|---|
| Animal Tissue/Cell Genomic DNA Extraction Kit | D1700 | Tissue, cells | 40 μg | 15–35 μg (20 mg tissue) | 1.8–2.0 |
| Blood Genomic DNA Extraction Kit | D1750 | Whole blood, buffy coat | 30 μg | 5–15 μg (200 μL whole blood) | 1.8–2.0 |
| Plant Genomic DNA Extraction Kit | D1800 | Plant leaf, seed, root | 40 μg | 10–30 μg (100 mg leaf) | 1.8–2.0 |
| FFPE DNA Extraction Kit | D1850 | FFPE tissue sections | 15 μg | 2–10 μg (10 μm × 5 sections) | 1.8–2.0 |
| Bacterial Genomic DNA Extraction Kit | D1900 | Gram-positive/negative bacteria | 50 μg | 15–40 μg (10⁹ cells) | 1.8–2.0 |
| Saliva DNA Collection & Purification Kit | D1950 | Saliva (0.5–2 mL) | 20 μg | 2–10 μg | 1.8–2.0 |

### 1.1 Key Advantages Summary

| Advantage | Description |
|---|---|
| No organic solvents | Silica membrane technology eliminates phenol/chloroform exposure |
| Fast protocol | 20 min hands-on time; 30–50 min total |
| High molecular weight | DNA > 30 kb from fresh tissue (intact nucleosomes) |
| RNase-safe | Optional on-column or post-eluion RNase treatment |
| Buffer color indicator | Binding Buffer BB contains pH indicator to confirm correct ethanol addition |
| Multiple formats | 50-preps, 100-preps, and 200-preps bulk configurations |
| DNase/RNase-free | All components validated for nuclease absence |
| PCR-ready | Eluted DNA amplifies directly without additional purification |

## 2. Kit Technology

All Solarbio DNA extraction kits use **silica membrane spin column technology** with protocol optimizations per sample type. The binding mechanism relies on chaotropic salts which disrupt hydrogen bonding between water molecules and DNA, allowing the negatively charged phosphate backbone to adsorb to the hydrophilic silica surface.

### 2.1 The Silica Adsorption Principle

Silica binds DNA in the presence of high concentrations of chaotropic salts (guanidine HCl, guanidine thiocyanate, NaI) at pH 6–8. The mechanism involves:

1. Chaotropic salts dehydrate DNA and silica surfaces
2. DNA phosphate groups form hydrogen bonds with silanol (Si–OH) groups on the silica surface
3. At low pH (< 7.5), silanol groups are protonated, reducing electrostatic repulsion between negatively charged DNA and silica
4. Under high-salt conditions (> 1 M monovalent salt), shielding of charge repulsion further enhances binding
5. Elution in low-ionic-strength buffer (10 mM Tris, pH 8.5) reverses adsorption: water molecules rehydrate DNA, disrupting silanol-phosphate interactions

**Reaction equation for silica-DNA interaction:**

\[
\text{DNA}_{\text{(aq)}} + \text{Si-OH}_{\text{(solid)}} \xrightarrow{[\text{GuHCl}] > 4M} \text{DNA}\cdots\text{Si-OH}_{\text{(adsorbed)}} \xrightarrow{\text{Low salt}} \text{DNA}_{\text{(aq)}} + \text{Si-OH}_{\text{(solid)}}
\]

### 2.2 Technology Comparison

| Parameter | Silica Column (All Kits) | Traditional Phenol-Chloroform |
|---|---|---|
| Purity | A₂₆₀/A₂₈₀ 1.8–2.0 | 1.8–2.0 |
| DNA fragmentation | Minimal (shear force < 10,000×g) | Minimal |
| RNA removal | RNase step optional | RNase step optional |
| Organic solvent exposure | None | Phenol, chloroform |
| Hands-on time | 20 min | 60–90 min |
| Total protocol time | 30–50 min | 2–3 h |
| Hazardous waste | Ethanol only | Phenol, chloroform (hazardous) |
| Reproducibility (well-to-well) | CV < 10% | CV 15–30% |
| Column format | Spin column (Eppendorf-compatible) | N/A |

### 2.3 Workflow

```
Sample → Lysis (Proteinase K, 56°C, 15–30 min)
    → Binding Buffer + Ethanol → Load column (12,000×g, 1 min)
        → Wash 1 (500 μL WB, 12,000×g, 1 min)
            → Wash 2 (500 μL WB, 12,000×g, 1 min)
                → Dry spin (12,000×g, 2 min)
                    → Elute (50–100 μL EB, RT 2 min, 12,000×g, 1 min)
                        → Purified DNA
```

### 2.4 Proteinase K Reaction

Proteinase K is a serine protease with broad substrate specificity. It cleaves peptide bonds adjacent to the carboxylic group of aliphatic and aromatic amino acids. The lysis reaction is:

\[
\text{Protein}_{(n)} \xrightarrow{\text{Proteinase K, 56°C}} \text{Peptides} + \text{Amino acids}
\]

At 56°C, Proteinase K activity is maximum (specific activity ≈ 30 U/mg). Adding SDS or guanidine HCl in the lysis buffer denatures proteins, exposing more cleavage sites and accelerating digestion.

## 3. Performance Specifications

### 3.1 DNA Yield by Sample Type (D1700)

| Sample | Input Amount | Typical DNA Yield | A₂₆₀/A₂₈₀ | Integrity |
|---|---|---|---|---|
| Mouse liver | 20 mg | 25–35 μg | 1.85–1.95 | >30 kb |
| Mouse tail (biopsy) | 1 cm (≈20 mg) | 10–20 μg | 1.80–1.90 | 15–30 kb |
| HeLa cells | 1 × 10⁶ cells | 5–10 μg | 1.85–1.95 | >30 kb |
| E. coli pellet | 1 × 10⁹ cells | 20–40 μg | 1.80–1.90 | >30 kb |
| Rat kidney | 20 mg | 20–30 μg | 1.85–1.95 | >30 kb |
| Rat brain | 20 mg | 12–20 μg | 1.80–1.90 | >20 kb |
| Human whole blood (D1750) | 200 μL | 5–15 μg | 1.80–1.90 | >20 kb |
| Buffy coat (D1750) | 100 μL | 10–20 μg | 1.85–1.95 | >30 kb |
| Cultured yeast | 1 × 10⁸ cells | 5–15 μg | 1.80–1.90 | 15–30 kb |

### 3.2 Plant Tissue Yield Guide (D1800)

| Plant Species | Tissue (100 mg) | Yield | A₂₆₀/A₂₈₀ | A₂₆₀/A₂₃₀ | Notes |
|---|---|---|---|---|---|
| Arabidopsis | Leaf | 8–15 μg | 1.8–2.0 | ≥1.8 | Low polysaccharides |
| Rice | Leaf | 10–20 μg | 1.8–2.0 | ≥1.7 | Moderate polysaccharides |
| Tobacco | Leaf | 20–30 μg | 1.8–2.0 | ≥1.8 | High protein content |
| Pine | Needle | 5–10 μg | 1.7–1.9 | ≥1.5 | High resin content; reduce input to 50 mg |
| Corn | Seed (50 mg) | 10–15 μg | 1.8–1.9 | ≥1.6 | Starch interference in endosperm |
| Soybean | Leaf | 15–25 μg | 1.8–1.9 | ≥1.7 | Moderate secondary metabolites |
| Arabidopsis | Seed (20 mg) | 2–5 μg | 1.7–1.9 | ≥1.5 | High lipid content; use additional chloroform extraction step |

### 3.3 FFPE DNA Yield (D1850)

| Sample Type | Age of Block | Section Yield (10 μm, 5 sections) | Usable for PCR/SEQ |
|---|---|---|---|
| Formalin-fixed breast tissue | <1 year | 5–10 μg | Yes (PCR, qPCR, NGS) |
| Formalin-fixed colon tissue | 1–3 years | 3–7 μg | Yes (PCR, qPCR) |
| Formalin-fixed lung tissue | 3–5 years | 2–5 μg | Limited to <200 bp amplicons |
| Decalcified bone | <1 year | 1–3 μg | Possible with dedicated protocol |
| Lymph node | <2 years | 4–8 μg | Yes (PCR, NGS) |

### 3.4 FFPE DNA Quality Assessment

| Parameter | Acceptable Range | Method |
|---|---|---|
| DNA concentration | ≥ 2 ng/μL | Qubit / Nanodrop |
| A₂₆₀/A₂₈₀ | 1.7–2.0 | UV spectrophotometry |
| A₂₆₀/A₂₃₀ | ≥ 1.5 | UV spectrophotometry |
| Fragment size (mean) | ≥ 150 bp | TapeStation / Bioanalyzer |
| Functional PCR (100 bp target) | Amplification in ≤ 38 cycles | qPCR |

### 3.5 Quality Control Specifications

| Parameter | Specification | Test Method |
|---|---|---|
| DNA integrity | High molecular weight (>20 kb for fresh tissue) | Agarose gel electrophoresis |
| RNA contamination | Not detectable (optional RNase step) | RNase treatment + gel |
| Protein contamination | A₂₆₀/A₂₈₀ 1.75–2.0 | UV spectrophotometry |
| Organic/polysaccharide residue | A₂₆₀/A₂₃₀ ≥ 1.8 | UV spectrophotometry |
| PCR inhibition | No inhibition at 100 ng/reaction | Gapdh PCR, 35 cycles |
| Endotoxin (D1700) | <10 EU/mL | LAL chromogenic assay |
| DNase/RNase activity | Not detectable | Incubation assays |
| Storage stability | 24 months at RT (kit), 6 months at −20°C (eluted DNA) | Accelerated aging |
| PCR amplification | Single band, correct size | 500 bp amplicon from 50 ng template |

## 4. Kit Components

### D1700-50T (Animal Tissue/Cell)

| Component | Volume | Storage | Notes |
|---|---|---|---|
| Proteinase K | 1.2 mL | -20°C | Stable at -20°C; short-term 2–8°C ≤ 1 week |
| Lysis Buffer LB | 30 mL | RT (15–30°C) | Contains guanidine HCl; precipitate at <15°C — warm to 37°C before use |
| Binding Buffer BB | 30 mL | RT | Contains chaotropic salt |
| Wash Buffer WB (concentrate) | 25 mL | RT | Add 100 mL 96% ethanol before first use |
| Elution Buffer EB | 15 mL | RT | 10 mM Tris-HCl, pH 8.5 |
| Spin Columns + Collection Tubes | 50 pcs | RT | 2 mL collection tube; binding capacity > 40 μg |

### D1750-50T (Blood) — Additional Components

| Component | Volume | Notes |
|---|---|---|
| Red Blood Cell Lysis Buffer | 50 mL | NH₄Cl-based; removes erythrocytes before WBC lysis |
| Proteinase K | 1.2 mL | — |
| Lysis Buffer BL | 30 mL | Optimized for blood (higher buffering capacity) |

### D1800-50T (Plant) — Additional Components

| Component | Volume | Notes |
|---|---|---|
| Lysis Buffer PL | 30 mL | Contains CTAB + PVP (for polyphenol removal) |
| RNase A (10 mg/mL) | 100 μL | Optional on-column or post-eluion treatment |
| β-Mercaptoethanol (user-supplied) | — | Add 1% to lysis buffer before use |

## 5. Step-by-Step Protocol Varies by Sample

**See detailed protocol for each kit type:**

- [Animal Tissue/Cell Protocol](../protocols/dna-extraction-protocol.md)
- Blood Protocol — refer to kit manual
- Plant Protocol — refer to kit manual

### 5.1 Protocol Optimization Factors

| Factor | Effect on DNA Yield and Purity | Recommended Adjustment |
|---|---|---|
| Lysis time (tissue) | Longer incubation (up to 60 min) increases yield | 30 min (standard); 60 min for connective tissue |
| Temperature of Binding Buffer BB | Cold buffer reduces binding efficiency | Warm to RT before use (20–25°C) |
| Ethanol concentration | < 70% ethanol reduces binding | Use 96–100% ethanol; never use denatured ethanol |
| Wash completeness | Residual ethanol inhibits downstream PCR | Dry spin 2 min at 12,000×g after final wash |
| Elution buffer volume | Lower volume increases concentration but reduces recovery | Minimum 30 μL for standard columns; 20 μL for low-DNA samples |
| Incubation at elution | 2 min RT is minimum; 5 min at 56°C increases recovery by 20% | Heat to 56°C for 5 min before final spin |

### 5.2 Sample-Specific Modifications

**High-fat tissue (brain, adipose):** After lysis step, centrifuge at 12,000×g for 5 min at 4°C. Remove the fatty lipid layer (top) before adding Binding Buffer BB.

**Hard tissue (bone, cartilage):** Increase Proteinase K to 40 μL and extend lysis to 60 min or overnight (56°C). Use a mortar and pestle or bead mill for initial pulverization in liquid nitrogen.

**Polysaccharide-rich samples (plant tubers, seeds):** After binding, perform an additional wash with 500 μL WB + 5% ethanol before the standard washes.

## 6. Storage of Purified DNA

| Condition | Duration | Recommended |
|---|---|---|
| 2–8°C (short-term) | ≤1 month | PCR template, restriction digestion |
| -20°C (long-term) | ≥5 years | Sequencing, library construction |
| -80°C (archival) | ≥10 years | Biobanking, rare samples |
| Elution buffer | TE (pH 8.0) preferred | Prevents DNase degradation |
| Avoid | Repeated freeze-thaw > 5× | Aliquot (50 μL) for repeated use |
| Container | Low-bind polypropylene | Reduces nonspecific adsorption to tube walls |

[▶ Related Protocol: DNA Extraction Protocol](../protocols/dna-extraction-protocol.md)
[▶ See also: DNA Purification & Gel Recovery](dna-purification.md)

*For pricing, custom packaging, and orders: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
