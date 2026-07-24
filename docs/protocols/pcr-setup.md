---
title: "PCR Setup Protocol"
description: "Official Solarbio protocol for PCR setup using 2×Taq PCR MasterMix (PC1150). Includes reaction assembly, thermal cycling conditions, primer design guidelines, gradient PCR, troubleshooting, and optimization for GC-rich and long amplicon templates."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "PCR Setup Protocol",
 "description": "Official Solarbio protocol for PCR setup using 2×Taq PCR MasterMix (PC1150). Reaction assembly, thermal cycling conditions, primer design, gradient PCR, troubleshooting.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# PCR Setup Protocol

Using Solarbio 2×Taq PCR MasterMix (PC1150). This protocol is suitable for routine genotyping, colony PCR, and amplicon generation from genomic DNA, plasmid DNA, or cDNA.

## Materials Required

| Item | Recommended Product | Alternative |
|---|---|---|
| 2×Taq PCR MasterMix | PC1150 (Solarbio) | — |
| Forward primer (10 μM) | User-supplied | Desalted or HPLC-purified |
| Reverse primer (10 μM) | User-supplied | Desalted or HPLC-purified |
| Template DNA | User-prepared (see concentration guide below) | — |
| Nuclease-free water | Solarbio R1600 | DEPC-treated water |
| PCR tubes (0.2 mL) | Thin-wall, flat-cap, DNase/RNase-free | 0.2 mL strip tubes or 96-well plate |
| Thermal cycler | Any standard model (Bio-Rad T100, ABI Veriti, Eppendorf Mastercycler) | — |
| Ice | — | Cold block |

### Template DNA Concentration Guide

| Template Type | Recommended Amount per 50 μL | Typical Purity Requirement |
|---|---|---|
| Genomic DNA (mammalian) | 10–100 ng | A₂₆₀/A₂₈₀ 1.8–2.0 |
| Genomic DNA (bacterial) | 10–100 ng | A₂₆₀/A₂₈₀ 1.8–2.0 |
| Plasmid DNA | 0.1–10 ng | A₂₆₀/A₂₈₀ 1.8–2.0 |
| cDNA | 0.1–1 μL (from 20 μL RT reaction) | — |
| Colony lysate | 1–2 μL (supernatant from 50 μL water boil, 10 min) | — |
| Viral DNA | 1–10 ng | — |

## Protocol

### Step 1: Thaw and Mix

Thaw the 2×Taq PCR MasterMix, primers, and template on ice. Vortex each briefly (2–3 s) and centrifuge (5 s, 10,000×g) to collect contents. Keep all components on ice throughout setup to prevent premature polymerase activity and primer-dimer formation.

**Time:** 5 min.

### Step 2: Calculate and Prepare Master Mix

Calculate the total number of reactions including a no-template control (NTC) and at least 10% excess volume for pipetting loss. Prepare a master mix without template:

| Component | Volume per 50 μL Reaction | Per 10 Reactions (incl. NTC) | Per 20 Reactions (incl. NTC) |
|---|---|---|---|
| 2×Taq PCR MasterMix | 25 μL | 275 μL | 550 μL |
| Forward primer (10 μM) | 1 μL | 11 μL | 22 μL |
| Reverse primer (10 μM) | 1 μL | 11 μL | 22 μL |
| Nuclease-free water | 18 μL | 198 μL | 396 μL |
| **Total master mix** | **45 μL** | **495 μL** | **990 μL** |

**Note:** For 2×Taq Plus (PC1155), 2×Taq HotStart (PC1160), and 2×High-Fidelity (PC1165), use the same volume ratios unless otherwise specified on the product label.

**Time:** 2 min.

### Step 3: Distribute Mix

Vortex the master mix gently for 2 s. Dispense 45 μL into each PCR tube or well. Change tips between each tube to avoid cross-contamination.

**Precaution:** If using a 96-well plate, seal before proceeding to template addition. Use a fresh seal for template addition.

**Time:** 2 min.

### Step 4: Add Template

Add 5 μL template DNA to each tube. For the NTC, add 5 μL nuclease-free water. Close tube caps immediately after adding template. For colony PCR: pick a single colony with a sterile pipette tip, streak on a replica plate, then dip the tip into the PCR tube.

**Precaution:** Change gloves after handling template DNA. Use positive-displacement pipettes for viscous genomic DNA.

**Time:** 3 min.

### Step 5: Place in Thermal Cycler

Centrifuge tubes briefly (5 s) to collect liquid at the bottom. Transfer to the thermal cycler and start the program.

### Step 6: Thermocycling

Select the program below based on your application:

#### Standard Protocol (default)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Initial denaturation | 95°C | 3 min | 1 |
| Denaturation | 95°C | 30 s | 30–35 |
| Annealing | Tm − 5°C (typically 55–65°C) | 30 s | 30–35 |
| Extension | 72°C | 30–60 s/kb | 30–35 |
| Final extension | 72°C | 5 min | 1 |
| Hold | 4°C | ∞ | — |

#### GC-Rich Template Protocol (GC content > 65%)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Initial denaturation | 98°C | 3 min | 1 |
| Denaturation | 98°C | 15 s | 32–35 |
| Annealing | 60–68°C (use touchdown) | 30 s | 32–35 |
| Extension | 72°C | 45 s/kb | 32–35 |
| Final extension | 72°C | 7 min | 1 |
| Hold | 4°C | ∞ | — |

**Additives:** Add DMSO to 3–5% (v/v) or betaine to 1 M final if GC > 70%.

#### Long Amplicon Protocol (> 3 kb)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Initial denaturation | 95°C | 3 min | 1 |
| Denaturation | 95°C | 20 s | 30 |
| Annealing | 58–62°C | 30 s | 30 |
| Extension | 72°C | 1 min/kb (incremental +10 s/cycle after cycle 20) | 30 |
| Final extension | 72°C | 10 min | 1 |
| Hold | 4°C | ∞ | — |

**Use:** 2×High-Fidelity PCR MasterMix (PC1165) for > 3 kb amplicons.

#### Touchdown Protocol (for difficult/specific targets)

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Initial denaturation | 95°C | 3 min | 1 |
| Touchdown (step 1) | 95°C, 30 s → 68°C, 30 s → 72°C, 30 s/kb | — | 5 |
| Touchdown (step 2) | 95°C, 30 s → 65°C, 30 s → 72°C, 30 s/kb | — | 5 |
| Touchdown (step 3) | 95°C, 30 s → 62°C, 30 s → 72°C, 30 s/kb | — | 5 |
| Touchdown (step 4) | 95°C, 30 s → 59°C, 30 s → 72°C, 30 s/kb | — | 5 |
| Amplification | 95°C, 30 s → 57°C, 30 s → 72°C, 30 s/kb | — | 15–20 |
| Final extension | 72°C | 5 min | 1 |
| Hold | 4°C | ∞ | — |

## Primer Design Guidelines

| Parameter | Recommended Value |
|---|---|
| Length | 18–25 nt |
| GC content | 40–60% |
| Tm | 55–65°C (use nearest-neighbor calculation) |
| Tm difference (pair) | ≤5°C |
| 3′ end | End with G or C if possible (terminal GC clamp) |
| Avoid | 3′ complementarity, long homopolymers (>4 nt), internal secondary structure (ΔG < −6 kcal/mol) |
| Amplicon length | 100–3000 bp (standard Taq) |
| Concentration (final) | 0.1–0.5 μM each primer |
| Hairpin stability | ΔG > −3 kcal/mol (check with OligoAnalyzer or Primer3) |

## Quality Checks During Protocol

| Step | What to Verify | Expected Result |
|---|---|---|
| After PCR | Run 5 μL product on 1–2% agarose gel | Single band at expected size |
| NTC well | No template control | No detectable band after 35 cycles |
| Positive control | Known template with validated primers | Band at expected size |
| Gel marker | Ladder loaded alongside samples | All marker bands visible |

### Expected Results

| PCR Outcome | Yield (per 50 μL) | Interpretation |
|---|---|---|
| Single bright band | 200–500 ng | Successful amplification |
| Weak but single band | 20–100 ng | Low yield — optimize template or cycles |
| Multiple bands | — | Non-specific — increase annealing temperature |
| Smear | — | DNA degradation or excess template |
| No product | — | See troubleshooting |

## Troubleshooting

| Problem | Possible Cause | Solution |
|---|---|---|
| No amplification | Poor primer design | Redesign primers, check Tm |
| | Template degraded | Check template integrity by gel |
| | PCR inhibitor present | Dilute template 1:10, 1:100; add BSA 0.1 μg/μL |
| | Taq polymerase inactivated | Verify storage at -20°C; check expiration |
| | Annealing temperature too high | Lower 2–5°C; use gradient PCR |
| Non-specific bands | Annealing temperature too low | Increase by 2–5°C |
| | Too many cycles | Reduce to 28–30 cycles |
| | Primer dimer | Redesign primers, use hot-start |
| | Mg²⁺ concentration too high | Reduce to 2 mM (use MgCl₂ optimization) |
| Weak amplification | Insufficient template | Increase 2–5× |
| | Extension time too short | Increase to 1 min/kb |
| | Too few cycles | Increase to 38 cycles |
| | Primers degraded | Re-order or re-purify primers |
| Smear on gel | Excessive template | Dilute template |
| | Degraded template | Prepare fresh template |
| | Voltage too high during electrophoresis | Reduce to 5 V/cm |
| Primer-dimer present | Excessive primer | Reduce to 0.1–0.2 μM |
| | Low template | Increase template amount |
| | Room temperature setup | Keep all components on ice |
| Bands in NTC | Contamination | Use fresh water, filter tips; UV-decontaminate PCR hood |

[▶ Related Protocol: qPCR Setup Guide](../protocols/qpcr-setup.md)
[▶ See also: PCR Master Mix Technical Spec](../molecular-biology/pcr-mastermixes.md)

*For product procurement: [solarbio.store](https://solarbio.store) | [solarbio.store](https://solarbio.store)*
