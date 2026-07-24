---
title: "Technical Specification: RNA Extraction Kits"
description: "Official technical specifications for Solarbio total RNA extraction kits — trizol-based and spin column methods for animal tissue, cells, blood, and plant samples. Includes yield tables, purity specifications, DNase treatment protocols, and RNA integrity assessment."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: RNA Extraction Kits",
 "description": "Specifications for Solarbio total RNA extraction kits — trizol and silica column methods. Yield tables by tissue type, purity metrics (A260/A280, A260/A230), DNase protocols, RNA integrity assessment (RIN, 28S/18S), and protocol optimization.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Technical Specification: RNA Extraction Kits

!!! note "Official Source"
    Technical documentation published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and commercial orders: **[solarbio.store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Method | Sample Type | Typical Yield |
|---|---|---|---|---|
| Total RNA Extraction Kit (Trizol) | R1100 | Acid-phenol (Trizol) | Tissue, cells, blood | 50–100 μg (100 mg tissue) |
| Total RNA Extraction Kit (Column) | R1200 | Silica membrane + DNase I | Tissue, cells, bacteria | 30–80 μg (20 mg tissue) |
| Plant Total RNA Extraction Kit | R1300 | CTAB-silica membrane | Plant tissue, fungi | 20–50 μg (100 mg) |
| Blood Total RNA Extraction Kit | R1400 | Erythrocyte lysis + column | Whole blood (0.3–1 mL) | 3–15 μg |

### 1.1 Extraction Method Comparison

| Parameter | Trizol (R1100) | Column (R1200) | Plant (R1300) |
|---|---|---|---|
| RNA size selection | All RNA (< 200 nt included) | Standard: > 200 nt | > 200 nt |
| DNase treatment | Optional (post-extraction) | On-column (included) | On-column (included) |
| Protocol time | 45–60 min | 25–35 min | 35–45 min |
| Organic solvent | Phenol:chloroform:isoamyl alcohol | None (column only) | None (column only) |
| Maximum RNA input | 100 mg tissue | 30 mg tissue | 100 mg tissue |
| miRNA recovery | Yes (with isopropanol precipitation) | No (with standard protocol) | No |
| Protein contamination risk | Low (phase separation) | Low | Moderate (polyphenols) |

## 2. Key Specifications

### 2.1 Trizol-based Kit (R1100)

| Parameter | Specification |
|---|---|
| RNA yield (mouse liver, 50 mg) | 80–120 μg |
| A₂₆₀/A₂₈₀ | 1.9–2.1 |
| A₂₆₀/A₂₃₀ | ≥2.0 |
| RNA integrity | 28S/18S ≥ 1.5 (denaturing gel) |
| gDNA contamination | <0.01% (qPCR, 35 cycles) |
| Protein contamination | Not detectable (A₂₈₀ profile) |
| DNase/RNase | Not detectable |
| Storage | 2–8°C (Trizol), -20°C (RNA), -80°C (long-term RNA archive) |

### 2.2 Column-based Kit (R1200)

| Parameter | Specification |
|---|---|
| Binding capacity | >100 μg per column |
| RNA length recovered | >200 nt (standard) / all sizes (with 0.5× ethanol protocol for small RNA) |
| Elution volume | 30–50 μL |
| On-column DNase digestion | Included (DNase I, 15 min at RT) |
| Purity (A₂₆₀/A₂₈₀) | 1.9–2.1 |
| Purity (A₂₆₀/A₂₃₀) | ≥1.8 |
| PCR-ready | Yes, ≤5% of eluate per RT reaction |
| Maximum loading | 30 mg tissue or 1×10⁷ cells |

### 2.3 Plant RNA Extraction Kit (R1300)

| Parameter | Specification |
|---|---|
| Binding capacity | >60 μg per column |
| Polyphenol removal | PVP-40 in lysis buffer (+ optional polyclar AT) |
| Polysaccharide removal | CTAB precipitation + ethanol wash |
| DNase treatment | On-column DNase I (included) |
| Typical yield (Arabidopsis leaf, 100 mg) | 15–30 μg |
| A₂₆₀/A₂₈₀ | 1.9–2.1 |
| A₂₆₀/A₂₃₀ | ≥1.7 (≥1.9 for low-phenolic species) |
| Protocol time | 40–55 min |

### 2.4 Blood RNA Extraction Kit (R1400)

| Parameter | Specification |
|---|---|
| Blood volume | 0.3–1.0 mL whole blood (fresh or EDTA/citrate preserved) |
| Erythrocyte removal | NH₄Cl-based RBC lysis buffer |
| Leukocyte yield per mL blood | 4–6 × 10⁶ WBCs (healthy adult) |
| Typical RNA yield (1 mL blood) | 5–15 μg |
| Globin mRNA carryover | < 5% of total RNA (may be reduced with optional globin reduction) |
| A₂₆₀/A₂₈₀ | 1.8–2.0 |
| DNase treatment | Included |

## 3. RNA Extraction Chemistry

### 3.1 Trizol (Acid-Phenol) Method — R1100

The Trizol reagent contains guanidine isothiocyanate (denaturant), phenol (protein denaturant), and β-mercaptoethanol (RNase inhibitor). At acidic pH (4.5–5.5), RNA partitions to the aqueous phase while DNA partitions to the interphase and proteins to the organic phase.

**Phase separation equation:**

\[
\text{Homogenate} \xrightarrow{\text{CHCl}_3, \text{vortex, centrifuge}} \text{Aqueous phase (RNA)} + \text{Interphase (DNA)} + \text{Organic phase (protein, lipids)}
\]

After phase separation, the aqueous phase contains RNA with >99% DNA removal. RNA is precipitated with isopropanol (0.5 mL per 1 mL Trizol) and washed with 75% ethanol.

### 3.2 Column (Silica Membrane) Method — R1200

The column method uses a lysis buffer containing guanidine isothiocyanate to simultaneously denature RNases and lyse cells. After the lysate is cleared by centrifugation or filtration, 70% ethanol is added to create optimal binding conditions:

\[
[\text{Ethanol}]_{\text{final}} = 35\% \text{ is sufficient to promote RNA binding to silica}
\]

At this ethanol concentration, RNA (>200 nt) adsorbs to the silica membrane while smaller molecules (salt, protein fragments, DNA < 200 bp) flow through. The on-column DNase I step degrades co-purified genomic DNA:

\[
\text{gDNA} \xrightarrow{\text{DNase I, Mg}^{2+}, 15\text{ min at RT}} \text{Oligonucleotide fragments (< 20 bp)}
\]

The DNase I is removed during the subsequent wash steps, and RNA is eluted in RNase-free water.

### 3.3 RNA Recovery from GC-Rich Tissues

Tissues with high RNase content (pancreas, spleen) or structural polysaccharides (plant cell walls) require specific modifications:

| Tissue/Organ | Recommended Kit | Special Handling |
|---|---|---|
| Pancreas | R1100 (Trizol) | Increase Trizol to 2 mL per 50 mg; homogenize immediately in liquid nitrogen |
| Spleen | R1100 or R1200 | Rapid homogenization; keep samples frozen until Trizol/lysis buffer addition |
| Muscle | R1200 | Extend Proteinase K digestion (if included) to 20 min at RT |
| Leaf (high-polyphenol) | R1300 | Add 2% PVP-40; use β-ME at 2% v/v |
| Seeds (high-starch) | R1300 | Increase centrifugation to 15,000×g; remove starch pellet |

## 4. Quality Control (All Kits)

| Test | Method | Specification |
|---|---|---|
| RNase activity | MS2 RNA incubation, 4 h at 37°C | Not detectable |
| DNase activity | pUC19 incubation, 4 h at 37°C | Not detectable |
| Endotoxin | LAL test | <10 EU/mL |
| Bioburden | Membrane filtration | Sterile |
| Functional test | RT-qPCR (GAPDH) | Ct ≤ 28 from 1 μg RNA |
| RNA integrity (control tissue) | Denaturing agarose gel | 28S/18S ≥ 1.5 |
| gDNA carryover (R1200) | qPCR (GAPDH, no RT control) | Ct ≥ 35 or undetermined |

## 5. Sample Preparation Guide

| Sample Type | R1100 (Trizol) | R1200 (Column) |
|---|---|---|
| Animal tissue (20–50 mg) | Homogenize in 1 mL Trizol (Polytron or bead mill, 30 s) | Homogenize in lysis buffer + β-ME |
| Cultured cells (10⁵–10⁷) | Lyse directly in 1 mL Trizol; mix by pipetting 10× | Lyse in 350 μL lysis buffer + 1% β-ME |
| Whole blood (0.3 mL) | Add 1 mL Trizol LS, mix vigorously | Use R1400 protocol (RBC lysis first) |
| Bacteria (10⁸–10⁹) | Lyse in Trizol with glass bead beating (30 s, 4°C) | Lysozyme pretreatment (3 mg/mL, 15 min, 37°C) + column |
| Plant tissue (100 mg) | Use R1300 protocol | Use R1300 protocol |
| Yeast (10⁷–10⁸ cells) | Lyse in Trizol with glass beads (45 s, 4°C) | Zymolyase treatment + column |

### 5.1 RNA Stability in Different Storage Conditions

| Condition | RNA Integrity (28S/18S) | Duration |
|---|---|---|
| Tissue in RNAlater (4°C) | > 1.5 | ≤ 1 month |
| Tissue flash-frozen in LN₂ (−80°C) | > 1.8 | ≥ 2 years |
| Purified RNA in water (−80°C) | Stable (RIN decrease < 0.5/year) | ≥ 5 years |
| Purified RNA in water (−20°C) | RIN decrease 1–2/year | ≤ 1 year |
| Purified RNA in TE buffer (−80°C) | More stable than water (EDTA chelates Mg²⁺-dependent RNases) | ≥ 10 years |
| RNA after 3× freeze-thaw | 28S/18S decreases 0.2–0.5 per cycle | Avoid > 5 cycles |

## 6. RNA Integrity Assessment

### 6.1 Denaturing Agarose Gel Evaluation

| 28S/18S Ratio | Integrity Assessment | Suitability |
|---|---|---|
| ≥ 2.0 | Excellent | All downstream applications |
| 1.5–2.0 | Good | Standard RT-PCR, RT-qPCR, Northern blot |
| 1.0–1.5 | Fair | Single-gene RT-PCR (3′ biased) |
| < 1.0 | Poor | Not recommended for quantitative applications |

### 6.2 A₂₆₀/A₂₈₀ and A₂₆₀/A₂₃₀ Interpretation

| A₂₆₀/A₂₈₀ | Interpretation |
|---|---|
| 1.9–2.1 | Pure RNA |
| < 1.8 | Protein or phenol contamination |
| > 2.2 | RNA degraded (degradation products absorb at A₂₆₀) |
| **A₂₆₀/A₂₃₀** | **Interpretation** |
| ≥ 2.0 | No significant guanidine/phenol/polysaccharide contamination |
| 1.6–1.9 | Acceptable for RT-qPCR (component carryover may affect A₂₃₀ only) |
| < 1.5 | Significant chaotrope/polysaccharide carryover; re-precipitate |

[▶ Related Protocol: RNA Extraction Protocol](../protocols/rna-extraction-protocol.md)
[▶ See also: Reverse Transcription Reagents](reverse-transcription.md)
[▶ See also: Real-Time PCR Reagents](real-time-pcr.md)

*For product procurement: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
