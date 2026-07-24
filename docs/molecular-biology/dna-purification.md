---
title: "Technical Specification: DNA Purification & Gel Recovery Kits"
description: "Technical specifications for Solarbio Agarose Gel DNA Recovery Kit (D1200) and DNA Purification Kit (D1300) — recovery efficiency, binding capacity, downstream compatibility, protocol optimization, and troubleshooting."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: DNA Purification & Gel Recovery Kits",
 "about": {"@type": "DefinedTerm", "name": "DNA Purification"},
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: DNA Purification & Gel Recovery Kits

!!! note "Commercial Orders"
    This documentation is a technical reference. For product pricing and purchasing: **[Solarbio Store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Overview

| Product | SKU | Application | Elution Volume | Binding Capacity |
|---|---|---|---|---|
| Agarose Gel DNA Recovery Kit | D1200 | Purify DNA from TAE/TBE agarose gels | ≥30 μL | >15 μg per column |
| DNA Purification Kit | D1300 | Clean up PCR products, enzymatic reactions, restriction digests | ≥30 μL | >10 μg per column |

### 1.1 Key Advantages

| Advantage | D1200 (Gel Recovery) | D1300 (PCR Cleanup) |
|---|---|---|
| Gel dissolving time (1% TAE, 200 mg slice) | 5–10 min at 56°C | N/A (solution cleanup) |
| Volume handling | ≤ 400 μL dissolved gel | ≤ 100 μL sample input |
| Fragment retention | 100 bp – 10 kb | 100 bp – 10 kb |
| Downstream compatible | Ligation, restriction, sequencing, labeling | Ligation, restriction, sequencing, labeling |
| Protocol time | 15–20 min | 10–15 min |
| No phenol/chloroform | Yes | Yes |
| Residual agarose | < 0.1% in eluate | N/A |

## 2. Technical Parameters

### 2.1 Gel DNA Recovery Kit (D1200)

| Parameter | Specification |
|---|---|
| Technology | Silica membrane spin column |
| Fragment size range | 100 bp – 10 kb |
| Recovery efficiency (>80%) | 100 bp – 8 kb |
| Recovery efficiency (30–50%) | 8 kb – 10 kb |
| Gel buffer compatibility | TAE, TBE |
| Binding capacity | >15 μg per column |
| Elution volume | 30–50 μL (minimum 25 μL for maximum concentration) |
| Gel dissolving buffer pH | 5.0–6.0 (containing NaI or guanidine thiocyanate) |

### 2.2 DNA Purification Kit (D1300)

| Parameter | Specification |
|---|---|
| Technology | Silica membrane spin column |
| Fragment size range | 100 bp – 10 kb |
| Recovery efficiency | >80% (100 bp – 8 kb) |
| Input volume | ≤100 μL standard; up to 500 μL with multiple loading |
| Binding capacity | >10 μg per column |
| Elution volume | 30–50 μL |
| Compatible samples | PCR products, restriction digests, labeling reactions, kinase reactions, ligation reactions |
| Residual primer removal | >95% removal of primers < 40 nt |
| Residual dNTP removal | >99% removal |

### 2.3 Recovery Efficiency by Fragment Size

| Fragment Size | D1200 (Gel Recovery) | D1300 (PCR Cleanup) |
|---|---|---|
| 100–200 bp | 70–85% | 75–90% |
| 200–500 bp | 80–95% | 85–95% |
| 500 bp – 3 kb | 85–95% | 85–95% |
| 3–5 kb | 80–90% | 80–90% |
| 5–8 kb | 70–85% | 70–85% |
| 8–10 kb | 30–50% | 40–60% |
| > 10 kb | 10–30% | 15–35% |

### 2.4 Binding Principle

DNA fragments selectively adsorb to the silica membrane in the presence of high concentrations of chaotropic salts (NaI in gel dissolving buffer, guanidine HCl in binding buffer). The chaotropic salt concentration required for effective binding to silica is:

\[
[\text{Chaotrope}] \geq 3\text{ M for effective DNA binding}
\]

At pH ≤ 7.5, DNA phosphate groups are protonated and interact with silanol groups on the membrane surface via hydrogen bonding and hydrophobic interactions. For gel extraction, the agarose is dissolved at 56°C in NaI-containing buffer, which simultaneously melts the agarose (gelling temperature 36–39°C) and provides binding conditions.

Elution is performed with low-ionic-strength buffer (10 mM Tris-HCl, pH 8.5). The alkaline pH deprotonates the silanol groups, increasing electrostatic repulsion, while the low salt concentration disrupts the chaotrope-mediated adsorption:

\[
\text{DNA}_{\text{(bound)}} \xrightarrow{\text{pH 8.5, low salt}} \text{DNA}_{\text{(free)}}
\]

## 3. Quality Control

| Test | D1200 | D1300 |
|---|---|---|
| Endonuclease | Not detectable | Not detectable |
| Exonuclease | Not detectable | Not detectable |
| DNase/RNase | Not detectable | Not detectable |
| Residual ethanol | <0.1% in eluate | <0.1% in eluate |
| PCR inhibition | None at 5 μL eluate (50 μL PCR) | None at 5 μL eluate (50 μL PCR) |
| Ligation compatibility | >80% T4 ligation efficiency vs. column-free control | >80% T4 ligation efficiency vs. column-free control |
| Restriction digestion | Complete digestion of 1 μg eluted DNA | Complete digestion of 1 μg eluted DNA |

## 4. Protocol Optimization

### 4.1 Optimization for Different Fragment Sizes

| Fragment Range | Recommended Adjustments |
|---|---|
| 100–200 bp | Use 30 μL elution buffer; incubate 5 min at RT before final spin; avoid overdrying membrane |
| 200–500 bp | Standard protocol (50 μL elution) |
| 500 bp – 3 kb | Standard protocol |
| 3–8 kb | Use 30 μL pre-warmed elution buffer (56°C); avoid vortexing to prevent shearing |
| > 8 kb | Use wide-bore pipette tips; elute with 20 μL pre-warmed (56°C) EB; extend incubation to 5 min |

### 4.2 Effect of Agarose Percentage on Recovery

| Agarose % | Gel Slice Dissolving Time (min at 56°C) | Expected Recovery (500 bp) |
|---|---|---|
| 0.7% | 3–5 min | 90–95% |
| 1.0% | 5–7 min | 85–92% |
| 1.5% | 7–10 min | 80–88% |
| 2.0% | 10–15 min | 70–80% |
| 3.0% | 15–20 min (increase dissolving buffer to 4× gel volume) | 50–65% |

### 4.3 Ethanol Removal in Wash Step

| Dry Spin Time at 12,000×g | Residual Ethanol in Eluate |
|---|---|
| 1 min | 0.5–1.0% (may inhibit downstream ligation) |
| 2 min | < 0.1% (recommended) |
| 3 min | < 0.05% |
| 5 min | < 0.01% |

## 5. Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| Low recovery (< 50%) | DNA fragment too small (< 100 bp) | Add 1 volume isopropanol instead of ethanol; increase binding time to 5 min |
| | DNA fragment too large (> 10 kb) | Use pre-warmed elution buffer (56°C); avoid overdrying membrane; minimize pipetting shear |
| | Gel slice too large (> 400 mg) | Split into two columns or increase dissolving buffer to 4× gel volume |
| | Incomplete gel dissolution | Increase incubation time at 56°C to 15 min; vortex every 3 min |
| | Ethanol added incorrectly | Verify ethanol concentration (96–100%); do not use denatured ethanol with additives |
| No DNA recovered | Column over-dried | Do not exceed 2 min dry spin; overdrying reduces binding capacity |
| | Elution buffer wrong | Use EB provided (10 mM Tris-HCl, pH 8.5); do not use water (pH < 7) |
| | Ethanol precipitation caused DNA loss | Precipitated DNA may appear at tube bottom before column loading — ensure resuspension |
| DNA does not digest/ligate | Residual ethanol in eluate | Increase dry spin to 3 min; air-dry column 2 min at RT before elution |
| | Contaminating agarose/chaotropes | Reduce gel slice to ≤ 200 mg; increase wash steps to 3× |
| | Elution buffer incompatible | Dialyze or ethanol precipitate if using heat-sensitive downstream applications |
| A₂₆₀/A₂₈₀ < 1.7 | Protein contamination | Increase wash volumes; add additional wash step |
| A₂₆₀/A₂₃₀ < 1.5 | Chaotrope carryover | Increase wash; include a second wash with 80% ethanol added |

## 6. Kit Components

### D1200-100T

| Component | Volume | Storage |
|---|---|---|
| Gel Dissolving Buffer | 100 mL | RT |
| Wash Buffer (concentrate) | 15 mL × 2 | RT |
| Elution Buffer | 30 mL | RT |
| Spin Columns | 100 pcs | RT |
| Collection Tubes | 100 pcs | RT |

### D1300-100T

| Component | Volume | Storage |
|---|---|---|
| Binding Buffer | 60 mL | RT |
| Wash Buffer (concentrate) | 15 mL × 2 | RT |
| Elution Buffer | 30 mL | RT |
| Spin Columns | 100 pcs | RT |
| Collection Tubes | 100 pcs | RT |

[▶ Related Protocol: Gel Extraction Protocol](../protocols/gel-extraction-protocol.md)
[▶ See also: DNA Extraction Kits](dna-extraction.md)
[▶ See also: Electrophoresis Reagents](electrophoresis.md)

*For technical support: [solarbio.store](https://solarbio.store)*
