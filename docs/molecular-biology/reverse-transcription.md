---
title: "Technical Specification: Reverse Transcription Reagents"
description: "Technical specifications for Solarbio reverse transcription kits — first-strand cDNA synthesis using M-MLV RNase H⁻, random hexamer/oligo-dT priming, one-step RT-qPCR kits, enzyme kinetics, reaction optimization, and performance data."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Reverse Transcription Reagents",
 "description": "Technical specifications for Solarbio reverse transcription kits — M-MLV RNase H⁻ first-strand cDNA synthesis, one-step RT-qPCR, priming strategies, enzyme kinetics, reaction optimization, and troubleshooting.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"},
 "about": {"@type": "DefinedTerm", "name": "Reverse Transcription"}
}
</script>

# Technical Specification: Reverse Transcription Reagents

!!! note "Official Source"
    Technical documentation published by Beijing Solarbio Science & Technology Co., Ltd. For product procurement and custom orders: **[solarbio.store](https://solarbio.store)** | **[solarbio.store](https://solarbio.store)**

## 1. Product Range

| Product | SKU | Chemistry | Feature | Best For |
|---|---|---|---|---|
| First-Strand cDNA Synthesis Kit | PC1170 | M-MLV RT (RNase H⁻) | Random hexamer + oligo-dT₁₈, 2-step RT | Gene expression, cloning, qPCR template |
| 2×SYBR Green RT-qPCR Kit | SR1130 | M-MLV RT + Hot-start Taq | One-step SYBR Green RT-qPCR | RNA quantification, fast workflow |
| 2×TaqMan RT-qPCR Kit | SR1140 | M-MLV RT + Hot-start Taq | One-step TaqMan RT-qPCR | RNA virus detection, multiplex |

### 1.1 Key Advantages of Solarbio RT Reagents

| Advantage | Details |
|---|---|
| RNase H⁻ mutant M-MLV | 5× higher thermal stability than wild-type M-MLV; retains activity at 50°C for GC-rich RNA templates |
| Combined hexamer + oligo-dT priming | Uniform coverage across mRNA length; improved 5′ end representation vs. oligo-dT alone |
| RNase inhibitor included | Porcine RNase inhibitor (RNasin homolog) — protects RNA during reaction setup |
| One-step kits (SR1130/SR1140) | No separate cDNA step reduces hands-on time by 60 min; minimizes pipetting errors |
| Long cDNA synthesis | Full-length cDNA up to 7 kb (PC1170) with optimized extension time |

## 2. Enzyme Specifications (PC1170)

### 2.1 M-MLV Reverse Transcriptase (RNase H⁻)

| Parameter | Specification |
|---|---|
| Reverse transcriptase | M-MLV (RNase H⁻ mutant) — point mutation in RNase H domain |
| Molecular weight | 76 kDa (monomer) |
| Optimal temperature | 37–42°C standard; up to 50°C with GC-rich or structured RNA |
| Optimal pH | 8.3 (Tris-HCl) at 37°C |
| DTT requirement | 5 mM (included in 2× buffer) |
| Input RNA | 10 pg – 5 μg total RNA; 1 pg – 500 ng poly(A)+ mRNA |
| Reaction time | 30 min (standard), up to 60 min (GC-rich, long template) |
| Inactivation | 70°C, 10 min (irreversible denaturation) |
| Primers supplied | Random hexamer (50 μM) + Oligo-dT₁₈ (50 μM) — 1:1 ratio in primer mix |
| Reaction volume | 20 μL (standard), scalable to 100 μL |
| cDNA length | Up to 7 kb (with optimized 60 min extension) |

### 2.2 The Reverse Transcription Reaction

The reverse transcription reaction catalyzed by M-MLV RT follows:

\[
\text{RNA} + \text{Primer} \xrightarrow{\text{M-MLV RT, dNTPs, Mg}^{2+}} \text{RNA/DNA hybrid} + \text{PP}_i
\]

The reaction is a three-step process:

1. **Primer annealing** (25°C, 10 min): Random hexamers and/or oligo-dT₁₈ hybridize to complementary sequences on the RNA template
2. **Extension** (42–50°C, 30–60 min): M-MLV RT extends the 3′-OH of the primer, incorporating dNTPs complementary to the RNA template. The RNase H⁻ mutation prevents degradation of the RNA template during first-strand synthesis, allowing full-length cDNA generation
3. **Inactivation** (70°C, 10 min): Heat denaturation inactivates the RT enzyme and dissociates the RNA/cDNA hybrid

### 2.3 Priming Strategy Comparison

| Primer Type | Mechanism | Best For | 5′/3′ Bias |
|---|---|---|---|
| Oligo-dT₁₈ | Anneals to poly(A) tail of mRNA | Full-length mRNA, 3′ gene expression | 3′ biased |
| Random hexamers (N₆) | Anneals to random complementary 6-mer sequences throughout all RNA species | Total RNA (including rRNA, viral RNA), 5′ coverage of long transcripts | Even coverage (5′-3′) |
| Gene-specific primers | Anneals to specific RNA sequence | Single-gene RT-qPCR, viral RNA detection | Target-specific |
| Combined (hexamer + oligo-dT) | Both mechanisms active simultaneously | Uniform 5′-3′ coverage, standard gene expression | Balanced (recommended default) |

### 2.4 M-MLV (RNase H⁻) vs. Wild-Type M-MLV

| Property | Wild-Type M-MLV | RNase H⁻ Mutant (PC1170) |
|---|---|---|
| RNase H activity | Present (degrades RNA in RNA/DNA hybrid) | <0.5% residual |
| Processivity | ~150 nt | ~350 nt |
| Optimal temperature | 37°C | 42°C (active to 50°C) |
| Half-life at 50°C | <5 min | ~30 min |
| cDNA yield (from 5 kb template) | Reference (1×) | 2–3× higher |
| Full-length cDNA (≥ 5 kb) | Variable | Consistent |

## 3. Two-Step RT-qPCR Workflow

### 3.1 Recommended cDNA Synthesis Setup (PC1170)

| Component | Volume (20 μL) | Final Concentration / Amount |
|---|---|---|
| Total RNA | Variable | 10 pg – 5 μg (1 μg recommended for standard qPCR) |
| 2× RT Buffer (includes dNTPs, DTT, Mg²⁺) | 10 μL | 1× |
| Primer Mix (random hexamer + oligo-dT₁₈) | 1 μL | 2.5 μM each |
| M-MLV RT (RNase H⁻) | 1 μL | 200 U |
| RNase inhibitor | 0.5 μL | 20 U |
| RNase-free water | To 20 μL | — |

### 3.2 Thermal Protocol

| Step | Temperature | Time | Purpose |
|---|---|---|---|
| Primer annealing | 25°C | 10 min | Allow random hexamers to anneal (not required for oligo-dT only) |
| Extension | 42°C | 30–60 min | First-strand cDNA synthesis |
| Inactivation | 70°C | 10 min | Heat-inactivate M-MLV RT and dissociate RNA/cDNA hybrid |
| Hold | 4°C | ∞ | |

### 3.3 cDNA Dilution and Storage

| Application | Recommended cDNA Dilution | Volume per qPCR (20 μL) |
|---|---|---|
| Standard gene expression (abundant targets) | 1:10 | 2 μL |
| Low-expression targets | 1:2–1:5 | 2–4 μL |
| Single-cell RT-qPCR | Undiluted | 5 μL (max 10% of reaction volume) |
| Long-term storage | −20°C (≤ 6 months) or −80°C (≥ 2 years) | Aliquot to avoid freeze-thaw |

### 3.4 No-RT Control

Always include a no-reverse-transcriptase (NRT) control for each RNA sample to assess genomic DNA contamination:

| NRT Reaction | Expected Result | Interpretation |
|---|---|---|
| All components except M-MLV RT | Ct ≥ 35 or undetermined | No significant gDNA contamination |
| NRT Ct < 33 | gDNA present | Treat RNA with DNase I; redesign primers to span introns |

## 4. One-Step RT-qPCR Kits (SR1130/SR1140)

### 4.1 Reaction Setup

| Component | Volume (20 μL) | Final |
|---|---|---|
| 2× One-Step RT-qPCR Master Mix | 10 μL | 1× |
| Forward primer (10 μM) | 0.4 μL | 0.2 μM |
| Reverse primer (10 μM) | 0.4 μL | 0.2 μM |
| Probe (10 μM) — for TaqMan only | 0.3 μL | 0.15 μM |
| RNA template | 1–5 μL | 10 pg – 1 μg |
| RT enzyme mix | 0.5 μL | — |
| ROX (if required) | 0.4 μL | 1× |
| RNase-free water | To 20 μL | — |

### 4.2 One-Step Thermal Protocol

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Reverse transcription | 50°C | 15 min | 1 |
| RT inactivation + Polymerase activation | 95°C | 2 min | 1 |
| Denaturation | 95°C | 10–15 s | 40 |
| Annealing/Extension (+ read) | 60°C | 30–45 s | 40 |
| Melt curve (SYBR only) | 65–95°C, 5 s/step | — | 1 |

### 4.3 One-Step vs. Two-Step RT-qPCR Comparison

| Factor | One-Step (SR1130/SR1140) | Two-Step (PC1170 + SR1110) |
|---|---|---|
| Time to result | 1.5 h | 3–3.5 h |
| Hands-on time | 10 min | 30 min |
| Sensitivity | Equivalent | Equivalent |
| Multiplex targets | Up to 4 (TaqMan) | Up to 4 (TaqMan) |
| Replicate RNA samples in qPCR | No (single RNA per reaction) | Yes (aliquots of same cDNA) |
| Archival cDNA for future assays | No | Yes |
| Flexibility to test different genes later | Limited | High (cDNA bank) |
| RNA secondary structure handling | 50°C RT, 15 min | 42°C, 30–60 min (better for structured RNA) |

## 5. Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| No cDNA / high Ct in qPCR | RNA degraded | Check RNA integrity (gel/RIN); use fresh RNA |
| | RT enzyme inactive | Store at -20°C; avoid freeze-thaw; check expiry |
| | RNase contamination | Use fresh aliquots of RNase-free water; change gloves |
| | Inhibitor in RNA eluate | Reduce RNA input; dilute RNA 1:5; re-purify RNA |
| Low signal in downstream qPCR | RNA input too low | Increase RNA to 1–2 μg (PC1170); use 0.5 μg minimum |
| | Priming suboptimal | Use combined hexamer + oligo-dT; consider gene-specific primers |
| | GC-rich RNA fails to reverse transcribe | Increase RT temperature to 50°C; extend to 60 min |
| Late Ct in NRT control | Genomic DNA contamination | DNase treat RNA; use intron-spanning primers; include NRT control |
| Multiple melt peaks in SYBR RT-qPCR | Non-specific RT priming | Reduce primer concentration; increase RT temperature gradually |
| | gDNA amplification | Design primers spanning exon-exon junctions |
| | RNA degradation fragments | Check RNA quality; re-extract if necessary |
| cDNA sheared / < 1 kb | RNase contamination during setup | Use fresh gloves, sterile bench, DEPC-treated water |
| | Excessive heating at 70°C | Do not exceed 70°C for 10 min |
| | Prolonged storage at 4°C | Store cDNA at -20°C; avoid 4°C for > 24 h |

[▶ Related Protocol: qPCR Setup Guide](../protocols/qpcr-setup.md)
[▶ See also: RNA Extraction Kits](rna-extraction.md)
[▶ See also: Real-Time PCR Reagents](real-time-pcr.md)

*For product procurement and technical support: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
