---
title: "Genomic DNA Extraction Protocol"
description: "Official Solarbio protocol for genomic DNA extraction from animal tissue and cells using the Genomic DNA Extraction Kit (D1700). Step-by-step procedure with yield expectations, quality checks, and troubleshooting for various sample types."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Genomic DNA Extraction Protocol",
 "description": "Official Solarbio protocol for genomic DNA extraction from animal tissue and cells using the Genomic DNA Extraction Kit (D1700). Step-by-step procedure with yield expectations, quality checks, and troubleshooting.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>

# Genomic DNA Extraction Protocol

Using Solarbio Animal Tissue/Cell Genomic DNA Extraction Kit (D1700). This protocol yields high-molecular-weight genomic DNA suitable for PCR, qPCR, Southern blot, restriction digestion, and next-generation sequencing library preparation.

## Equipment and Reagents Checklist

| Item | Recommended / Specification | Notes |
|---|---|---|
| Microcentrifuge | 12,000–16,000 ×g capability | Pre-cooled if processing RNase-sensitive samples |
| Heat block or water bath | 56°C ± 1°C, 70°C ± 1°C | Preheat before starting |
| Vortex mixer | Standard | — |
| Pipettes (10 μL, 100 μL, 1000 μL) | DNase/RNase-free tips with aerosol barrier | Pre-wet tips for viscous solutions |
| 1.5 mL microcentrifuge tubes | DNase/RNase-free | — |
| 96–100% ethanol | Molecular biology grade | Denatured ethanol with additives is NOT acceptable |
| Sterile forceps / scalpel | For tissue dissection | Clean with 70% ethanol between samples |
| Liquid nitrogen (optional) | For tissue pulverization | Yields highest-quality DNA from fibrous tissue |

## Materials — Kit Components per Prep

| Component | Volume per Prep | Notes |
|---|---|---|
| Sample | 20 mg tissue or 1×10⁶ cells | See sample-specific notes below |
| Proteinase K | 20 μL | Pre-warmed to RT (viscous solution) |
| Lysis Buffer LB | 200 μL | If precipitate visible, warm to 37°C until dissolved |
| Binding Buffer BB | 200 μL | Must be at RT before use |
| Wash Buffer WB (ethanol added) | 500 μL × 2 | Confirm 96–100% ethanol added per label instructions |
| Elution Buffer EB | 50–100 μL | Pre-warm to 56°C for higher recovery |

## Protocol

### Step 1: Sample Preparation

**Time:** 5 min.

**Tissue:** Weigh 20 mg (maximum 30 mg). Cut into pieces < 1 mm³ using a sterile scalpel. Place in a 1.5 mL microcentrifuge tube. For fibrous tissue (heart, muscle, tail), pulverize in liquid nitrogen with mortar and pestle before adding lysis buffer.

**Cells:** Harvest 1×10⁶ cells (maximum 5×10⁶). Wash twice with 1 mL PBS. Centrifuge at 300×g for 5 min at RT. Discard supernatant completely. For suspension cells, spin directly in the culture tube.

**Precaution:** Do not exceed the recommended sample input. Excess tissue results in incomplete lysis and low DNA purity.

### Step 2: Lysis

| Component | Tissue (20 mg) | Cells (1×10⁶) |
|---|---|---|
| Lysis Buffer LB | 200 μL | 200 μL |
| Proteinase K | 20 μL | 20 μL |

Add Lysis Buffer LB and Proteinase K. Vortex thoroughly for 15 s until the sample is fully suspended. For tissue, ensure no large clumps remain.

**Incubation:**
- **Tissue:** 56°C for 30 min (60 min for fibrous or hard tissue). Vortex for 5 s every 10 min.
- **Cells:** 56°C for 15 min. Vortex once after 7 min.

**Expected appearance:** The lysate should become clear to slightly translucent. If lysate remains cloudy after 30 min, extend incubation to 60 min and add an additional 10 μL Proteinase K.

**Time:** 15–60 min.

### Step 3: Binding

| Component | Volume | Instructions |
|---|---|---|
| Binding Buffer BB | 200 μL | Add, vortex immediately for 5 s |
| Incubation | 70°C, 10 min | Helps denature residual proteins |
| Ethanol (96–100%) | 200 μL | Vortex 10 s immediately after addition |

Add Binding Buffer BB and vortex. Incubate at 70°C for 10 min.

Add 200 μL ethanol (96–100%). Vortex immediately for 10 s. The solution should appear homogeneous.

**Precaution:** If a precipitate forms upon ethanol addition, vortex more vigorously until dissolved. This does not affect DNA binding.

Transfer the entire mixture (≈ 620 μL) to a spin column placed in a collection tube. Centrifuge at 12,000×g for 1 min. Discard the flow-through.

**Time:** 12 min.

### Step 4: Wash

| Wash Step | Wash Buffer WB | Centrifuge | Discard |
|---|---|---|---|
| Wash 1 | 500 μL | 12,000×g, 1 min | Flow-through |
| Wash 2 | 500 μL | 12,000×g, 1 min | Flow-through |
| Dry spin | — | 12,000×g, 2 min | Collection tube discarded |

Add 500 μL Wash Buffer WB (ensuring ethanol has been added per label instructions). Centrifuge at 12,000×g for 1 min. Discard flow-through.

Repeat the wash step once.

After the second wash, centrifuge at 12,000×g for 2 min to remove residual ethanol. **Important:** Residual ethanol inhibits downstream PCR and restriction digestion. The dry spin is essential.

Discard the collection tube and place the column in a clean 1.5 mL microcentrifuge tube.

**Time:** 5 min.

### Step 5: Elution

| Parameter | Standard | For Low DNA | For High Concentration |
|---|---|---|---|
| Elution Buffer EB volume | 100 μL | 50 μL | 30 μL |
| Incubation | RT, 2 min | RT, 5 min | 56°C, 5 min |
| Centrifuge | 12,000×g, 2 min | 12,000×g, 2 min | 12,000×g, 2 min |

Add 50–100 μL Elution Buffer EB to the center of the membrane. Ensure the buffer contacts the membrane directly — avoid pipetting onto the column walls.

Incubate at room temperature for 2 min.

Centrifuge at 12,000×g for 2 min. The eluate contains purified genomic DNA.

For maximum recovery: re-apply the eluate to the column membrane, re-incubate for 2 min, and re-spin.

**Time:** 4 min.

## Quality Checks During Protocol

### During Lysis

| Observation | Interpretation |
|---|---|
| Lysate clear within 15–30 min | Normal; proceed |
| Lysate remains viscous after 30 min | High molecular weight DNA releasing slowly (normal for spleen, thymus) |
| Lysate remains cloudy after 30 min | Incomplete protein digestion — extend lysis to 60 min |
| Clumps visible | Poor homogenization — increase vortexing |

### After Elution

| Check | Method | Expected Result |
|---|---|---|
| Concentration | UV spectrophotometer (260 nm) | 50–350 ng/μL (from 20 mg tissue, 100 μL EB) |
| Purity A₂₆₀/A₂₈₀ | UV spectrophotometer | 1.8–2.0 |
| Purity A₂₆₀/A₂₃₀ | UV spectrophotometer | ≥ 1.8 |
| Integrity | 0.7–1% agarose gel | Single band > 20 kb (no smearing) |
| Functional test | PCR (GAPDH, 35 cycles) | Single band at expected size |

## Expected Yield

| Sample | Input | Yield | A₂₆₀/A₂₈₀ | Integrity |
|---|---|---|---|---|
| Mouse liver | 20 mg | 25–35 μg | 1.85–1.95 | >30 kb |
| HeLa cells | 1×10⁶ | 5–10 μg | 1.85–1.95 | >30 kb |
| Mouse tail | 1 cm (≈20 mg) | 10–20 μg | 1.80–1.90 | 15–30 kb |
| E. coli pellet | 1×10⁹ | 20–40 μg | 1.80–1.90 | >30 kb |
| Rat kidney | 20 mg | 20–30 μg | 1.85–1.95 | >30 kb |
| Mouse brain | 20 mg | 12–20 μg | 1.80–1.90 | >20 kb |

## Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| Low DNA yield | Incomplete lysis | Extend Proteinase K incubation to 60 min; add fresh Proteinase K |
| | Poor binding | Ensure Binding Buffer BB is at RT; ethanol concentration is 96–100% |
| | Elution insufficient | Use 50 μL EB pre-warmed to 56°C; incubate 5 min |
| | Sample over-dried | Do not exceed 2 min dry spin (dried membrane reduces recoverable yield) |
| A₂₆₀/A₂₈₀ < 1.7 | Protein contamination | Add additional Proteinase K; extend lysis time |
| | Incomplete wash | Ensure Wash Buffer WB has ethanol added; use correct volume |
| A₂₆₀/A₂₃₀ < 1.5 | Chaotrope carryover | Increase wash steps to 3×; ensure dry spin is complete |
| | Polysaccharide contamination (plant) | Use plant-specific kit D1800 |
| DNA degraded | Nuclease contamination | Use DNase/RNase-free tubes and tips; keep samples on ice before lysis |
| | Excessive vortexing after lysis | Vortex gently; high molecular weight DNA is shear-sensitive |
| | Multiple freeze-thaw cycles | Aliquot eluted DNA; do not freeze-thaw > 5× |
| No DNA in eluate | Ethanol not added to Binding Buffer | Repeat with ethanol; or check Wash Buffer ethanol addition |
| | Column orientation reversed | Arrow on column must face the same direction as centrifuge rotor hinge |
| PCR inhibition | Residual ethanol in eluate | Increase dry spin to 3 min; air-dry column for 2 min before elution |
| | Inhibitor co-purification | Dilute DNA 1:10 in EB or water; re-purify by ethanol precipitation |

## Optimization Notes

| Sample Type | Recommended Modifications |
|---|---|
| Adipose tissue (brain, fat) | After lysis, centrifuge 12,000×g for 5 min at 4°C. Remove fatty top layer before adding Binding Buffer BB. |
| Hard tissue (bone, cartilage) | Increase Proteinase K to 40 μL; extend lysis to 60 min or overnight at 56°C. Pulverize in liquid nitrogen before lysis. |
| Fibrotic tissue (scar, heart) | Use 30 mg maximum; increase lysis to 60 min; use bead mill homogenization. |
| Small tissue samples (< 10 mg) | Reduce all volumes proportionally (100 μL LB, 10 μL PK). Use 30 μL EB for elution. |
| High cell number (> 5×10⁶) | Split across two columns; or increase LB to 400 μL and PK to 40 μL. |
| Paraffin-embedded tissue | Use FFPE DNA Extraction Kit (D1850) with overnight deparaffinization and extended Proteinase K digestion. |

[▶ See also: DNA Extraction Kit Technical Spec](../molecular-biology/dna-extraction.md)
[▶ See also: DNA Purification & Gel Recovery](../molecular-biology/dna-purification.md)

*[solarbio.store](https://solarbio.store)*
