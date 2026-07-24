---
title: "Technical Specification: Cloning & Ligation Reagents"
description: "Technical specifications for Solarbio cloning reagents — T4 DNA ligase, T4 polynucleotide kinase, alkaline phosphatase (CIP), restriction enzymes, cloning vectors, and DNA/RNA modifying enzymes with reaction conditions and optimization guidance."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Cloning & Ligation Reagents",
 "description": "Technical specifications for Solarbio cloning reagents — T4 DNA ligase, T4 PNK, CIP, restriction enzymes, and DNA/RNA modifying enzymes with reaction conditions, unit definitions, and optimization guidance.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Cloning Reagents"}
}
</script>

# Technical Specification: Cloning & Ligation Reagents

!!! note "Official Source"
    Technical documentation published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and custom orders: **[solarbio.store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Unit Definition | Application |
|---|---|---|---|
| T4 DNA Ligase | L1010 | 1 U = 50% ligation of cohesive λ-HindIII fragments in 30 min at 16°C | DNA ligation (cohesive ends, blunt ends) |
| T4 Polynucleotide Kinase | L1020 | 1 U = 1 nmol ³²P incorporated in 30 min at 37°C | 5′ phosphorylation of DNA/RNA; kinase labeling |
| Alkaline Phosphatase (CIP) | L1030 | 1 U = 1 μmol pNPP hydrolyzed in 1 h at 37°C | Dephosphorylation of DNA 5′ ends |
| Taq DNA Polymerase (native) | PC1100 | 1 U = 10 nmol dNTP incorporation in 30 min at 74°C | PCR amplification |
| T4 DNA Polymerase | L1040 | 1 U = 10 nmol dNTP incorporation in 30 min at 37°C | Blunt-end generation, fill-in reactions |
| Klenow Fragment | L1050 | 1 U = 10 nmol dNTP incorporation in 30 min at 37°C | 5′ overhang fill-in, random priming labeling |

### 1.1 Key Advantages

| Advantage | Details |
|---|---|
| T4 DNA Ligase (L1010) | High specific activity (400 U/μL); double the unit concentration of standard ligases — enables 15-min cohesive-end ligation |
| ATP pre-supplemented buffer | 10× T4 DNA Ligase Buffer contains 10 mM ATP; no external ATP addition needed |
| Compatible with common restriction buffers | Solarbio T4 DNA Ligase is active in CutSmart/NEBuffer 2/3 at 50–75% relative activity |
| PEG 4000 included | Molecular crowding agent enhances ligation efficiency 3–5× vs. PEG-free reactions |

## 2. T4 DNA Ligase Specifications

### 2.1 Reaction Parameters

| Parameter | Cohesive Ends | Blunt Ends |
|---|---|---|
| Optimal temperature | 16°C | 22°C (RT) |
| Typical ligation time | 15–30 min | 2 h (RT) or 16 h (4°C) |
| ATP concentration (1× buffer) | 1 mM | 1 mM |
| PEG 4000 (in buffer) | 5% (w/v) | 5% (w/v) |
| Heat inactivation | 65°C for 10 min | 65°C for 10 min |
| Unit concentration | 400 U/μL (L1010-01) | 400 U/μL |
| Recommended enzyme per 20 μL | 1 μL (400 U) | 2 μL (800 U) |
| Endonuclease contamination | Not detectable | Not detectable |
| Exonuclease contamination | Not detectable | Not detectable |

### 2.2 Ligation Reaction Chemistry

T4 DNA Ligase catalyzes the formation of a phosphodiester bond between a 5′ phosphate and a 3′ hydroxyl group at a nick in double-stranded DNA. The reaction proceeds through three steps:

1. **Adenylation of the enzyme**: T4 DNA Ligase reacts with ATP, forming a covalent enzyme-AMP intermediate and releasing pyrophosphate (PPi):

\[
E + \text{ATP} \rightleftharpoons E\text{-AMP} + \text{PP}_i
\]

2. **AMP transfer to 5′ phosphate**: The AMP is transferred from the enzyme to the 5′ phosphate group of the DNA nick, activating it as a 5′-phosphoryl-AMP intermediate:

\[
E\text{-AMP} + \text{DNA}(5'\text{-PO}_4) \rightarrow E + \text{AMP-PO}_4\text{-DNA}(5')
\]

3. **Phosphodiester bond formation**: The 3′-OH of the adjacent DNA strand attacks the activated 5′ phosphate, forming a new phosphodiester bond and releasing AMP:

\[
\text{AMP-PO}_4\text{-DNA}(5') + \text{DNA}(3'\text{-OH}) \rightarrow \text{DNA}(3'\text{-PO}_4\text{-5'})\text{-DNA} + \text{AMP}
\]

**Ligation Efficiency Factors:**

| Factor | Effect | Optimization |
|---|---|---|
| Insert:vector molar ratio | 3:1 (cohesive ends), 5:1 (blunt ends) | Calculate as (insert ng = vector ng × (insert kb / vector kb) × molar ratio) |
| DNA end concentration | Higher conc. favors intramolecular ligation | Reactions ≥ 10 nM DNA ends for self-ligation; ≤ 1 nM for circularization |
| Temperature | 16°C balances enzyme activity with DNA end annealing | 22°C works well for short incubations; 4°C overnight maximizes total ligation |
| ATP concentration | 1 mM optimal; excess ATP (≥ 5 mM) inhibits ligation | Do not exceed 1 mM final ATP |

### 2.3 Molar Ratio Calculation

Use the following formula to calculate insert mass for a given molar ratio:

\[
\text{Insert mass (ng)} = \frac{\text{Vector mass (ng)} \times \text{Insert length (kb)} \times \text{Molar ratio}}{\text{Vector length (kb)}}
\]

Typical ligation ratios:

| End Type | Insert:Vector Ratio | Vector Mass | Insert Mass | Total DNA in 20 μL |
|---|---|---|---|---|
| Cohesive | 3:1 | 50 ng | Calculated | 50–200 ng |
| Blunt | 5:1 | 50 ng | Calculated | 50–200 ng |
| Single-base overhang (TA) | 3:1 | 50 ng | Calculated | 50–200 ng |

## 3. T4 Polynucleotide Kinase (PNK) — L1020

| Parameter | Specification |
|---|---|
| Unit definition | 1 U incorporates 1 nmol ³²P into acid-insoluble product in 30 min at 37°C |
| Forward reaction | Transfers γ-phosphate from ATP to 5′-OH of DNA/RNA |
| Exchange reaction | Catalyzes exchange of 5′ phosphate with γ-phosphate of ATP (in ADP presence) |
| 3′ phosphatase activity | Removes 3′ phosphate groups from DNA |
| Optimal buffer | 70 mM Tris-HCl (pH 7.6), 10 mM MgCl₂, 5 mM DTT |
| ATP requirement | 1 mM for forward reaction |
| Heat inactivation | 75°C for 10 min |

## 4. Alkaline Phosphatase (CIP) — L1030

| Parameter | Specification |
|---|---|
| Unit definition | 1 U hydrolyzes 1 μmol pNPP in 1 h at 37°C |
| Optimal buffer | 50 mM Tris-HCl (pH 8.5), 0.1 mM ZnCl₂, 1 mM MgCl₂ |
| Heat inactivation | 75°C for 10 min (with EDTA, pH 8.0) |
| Dephosphorylation time | 30 min at 37°C (linearized vector, 5′ overhang) |
| | 60 min at 37°C (blunt ends, 3′ overhang) |
| Application | Prevents vector re-ligation; reduces background in cloning |

## 5. Restriction Enzymes Recommendation

| Enzyme | Recognition Site | 5′ Overhang | Buffer | Incubation Temp | Heat Inactivation |
|---|---|---|---|---|---|
| EcoRI | G↓AATTC | AATT | CutSmart / Buffer E | 37°C | 65°C, 20 min |
| HindIII | A↓AGCTT | AGCT | CutSmart / Buffer E | 37°C | 80°C, 20 min |
| BamHI | G↓GATCC | GATC | CutSmart / Buffer E | 37°C | 65°C, 20 min |
| NotI | GC↓GGCCGC | GGCC | CutSmart / Buffer E | 37°C | 65°C, 20 min |
| XhoI | C↓TCGAG | TCGA | CutSmart / Buffer E | 37°C | 65°C, 20 min |
| SmaI | CCC↓GGG | Blunt | Buffer Tango | 30°C | 65°C, 15 min |
| SalI | G↓TCGAC | TCGA | CutSmart / Buffer 3 | 37°C | 65°C, 20 min |
| KpnI | GGTAC↓C | GTAC | CutSmart / Buffer 1 | 37°C | 65°C, 20 min |

### 5.1 Double Digestion Guidelines

| Enzyme Pair | Compatible Buffer | Digestion Time | Notes |
|---|---|---|---|
| EcoRI + HindIII | CutSmart | 1 h at 37°C | Standard cloning double digest |
| BamHI + XhoI | CutSmart | 1 h at 37°C | Both produce compatible 5′ overhangs |
| NotI + EcoRI | CutSmart | 1 h at 37°C | NotI is methylation-sensitive |
| SmaI (blunt) + EcoRI | Sequential: EcoRI first (37°C), then SmaI (30°C) | 1 h each | Blunt + sticky often requires sequential |

## 6. Troubleshooting

| Ligation Issue | Cause | Solution |
|---|---|---|
| Few transformants | Vector self-ligation | Increase CIP treatment; confirm dephosphorylation |
| | Poor-quality insert DNA | Purify insert via gel extraction; check A₂₆₀/A₂₈₀ |
| | Wrong insert:vector ratio | Re-calculate; use 3:1 (sticky) or 5:1 (blunt) |
| | ATP degraded in buffer | Use fresh 10× ligation buffer; store aliquoted at -20°C |
| High background (blue-white) | Incomplete dephosphorylation | Increase CIP incubation to 60 min; repeat CIP after gel extraction |
| | Vector re-ligation | Use CIP-treated vector; verify on gel (linear vs. circular) |
| Insert present but wrong size | Insert tandem ligation | Reduce insert concentration; reduce ligation time (≤ 30 min) |
| | Partial digestion of vector | Verify restriction digest on gel; gel purify double-digested vector |
| No colonies | Transformation failed | Check competent cell efficiency; use positive control (pUC19) |
| | Antibiotic wrong concentration | Verify plates have correct antibiotic (e.g., 100 μg/mL ampicillin) |
| Restriction digestion incomplete | Star activity (non-specific cleavage) | Check buffer composition; reduce glycerol < 5%; reduce incubation time to 30 min |
| | Methylation blocking | Use Dam⁻/Dcm⁻ cells for methylation-sensitive sites |

[▶ Related Protocol: Competent Cell Transformation Protocol](../protocols/competent-cell-transformation.md)
[▶ See also: Competent Cells](competent-cells.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
