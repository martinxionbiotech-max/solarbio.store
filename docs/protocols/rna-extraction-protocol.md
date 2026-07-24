---
title: "Total RNA Extraction Protocol"
description: "Official Solarbio protocol for total RNA extraction — trizol-based and column-based methods for animal tissue, cells, blood, and plant samples, with quality control specifications."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Total RNA Extraction Protocol",
 "description": "Official Solarbio protocol for total RNA extraction — trizol-based and column-based methods for animal tissue, cells, blood, and plant samples, with quality control specifications.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Total RNA Extraction Protocol

Using Solarbio Total RNA Extraction Kit — Trizol Method (R1100) or Column Method (R1200). This document describes both methods, including equipment requirements, step-by-step procedures, quality checks, and troubleshooting for each approach.

---

## Principle

RNA extraction requires rapid denaturation of RNases, effective separation of RNA from DNA and proteins, and recovery of intact total RNA. The Trizol method (R1100) uses a monophasic solution of phenol and guanidine isothiocyanate to lyse cells and inactivate RNases, followed by chloroform phase separation and isopropanol precipitation. The column method (R1200) uses a silica membrane in a chaotropic salt system, with on-column DNase treatment to remove genomic DNA contamination without an organic extraction step.

---

## Equipment and Reagents Checklist

| Item | Specification | Trizol Required | Column Required |
|---|---|---|---|
| Microcentrifuge | 4°C and RT capable, 12,000–16,000×g | Yes | Yes |
| Vortex mixer | Standard | Yes | Yes |
| Homogenizer | Rotor-stator or bead homogenizer | Yes | Yes |
| Heat block | 55°C | No | Yes (DNase step) |
| Refrigerated centrifuge | Capable of 4°C, 12,000×g | Yes | No |
| Sterile 1.5 mL microcentrifuge tubes | RNase-free | Yes | Yes |
| RNase-free water | DEPC-treated or certified nuclease-free (R1600) | Yes | Yes |
| Chloroform (molecular biology grade) | ≥99% purity | Yes | No |
| Isopropanol (molecular biology grade) | ≥99.5% purity | Yes | No |
| 75% ethanol | Prepared with RNase-free water | Yes | No |
| β-mercaptoethanol | Fresh, added to Lysis Buffer | No | Yes |
| DNase I | RNase-free (provided with R1200 kit) | No | Yes |

---

## Precautions

- **RNase-free technique is essential**: Wear gloves at all times. Use only certified RNase-free pipette tips, tubes, and reagents.
- **Work in a dedicated RNA area**: Clean the work surface with 70% ethanol or RNase decontamination solution before starting.
- **Keep samples cold**: After homogenization, minimize the time samples spend at room temperature before adding Trizol or Lysis Buffer.
- **Avoid over-drying**: Air-dried RNA pellets for ≤10 min; over-dried pellets are difficult to dissolve and may degrade.

---

## Section A: Trizol Method (R1100)

### Protocol

| Step | Detail | Time | Notes |
|---|---|---|---|
| Homogenize | Add 1 mL Trizol per 50 mg tissue or 10⁶ cells in a microcentrifuge tube | 1–2 min | Homogenize on ice; use RNase-free rotor-stator or liquid nitrogen grinding |
| Phase separation | Add 0.2 mL chloroform per 1 mL Trizol used. Shake tube vigorously for 15 seconds | 2 min | The solution should appear milky pink after shaking |
| Centrifuge | 12,000×g, 15 min, 4°C | 15 min | Three phases form: colorless upper aqueous phase (RNA), white interphase (DNA), and pink lower organic phase (protein) |
| Transfer aqueous phase | Carefully transfer the colorless upper phase (≈500 μL per 1 mL Trizol) to a fresh RNase-free tube | 1–2 min | Do not disturb the interphase — aspirate from the top down using a P200 pipette |
| Precipitate RNA | Add 0.5 mL isopropanol per 1 mL Trizol used. Mix gently by inversion. Incubate at room temperature for 10 min | 10 min | Do not vortex after adding isopropanol |
| Centrifuge | 12,000×g, 10 min, 4°C | 10 min | RNA pellet should be visible at the bottom of the tube (white or translucent) |
| Wash | Remove supernatant carefully. Add 1 mL of 75% ethanol (prepared in RNase-free water), vortex briefly | 2 min | The wash removes residual Trizol and isopropanol |
| Centrifuge | 7,500×g, 5 min, 4°C | 5 min | |
| Dry | Remove supernatant. Air-dry the RNA pellet for 5–10 min at room temperature | 5–10 min | Do not vacuum dry or heat dry; over-drying reduces solubility |
| Dissolve | Add 30–50 μL RNase-free water (R1600). Incubate at 55°C for 10 min with occasional flicking | 10 min | If the pellet is difficult to dissolve, pipette gently up and down |
| **Total time** | | **~40 min** | |

### Quality Check (Trizol)

| Parameter | Acceptable Range | Method |
|---|---|---|
| A₂₆₀/A₂₈₀ | 1.9–2.1 | Spectrophotometry (NanoDrop or equivalent) |
| A₂₆₀/A₂₃₀ | ≥2.0 | Indicates no organic (phenol/chaotropic) contamination |
| Concentration | 50–2000 ng/μL (depends on input) | A₂₆₀ × 40 μg/mL per AU |
| Integrity (gel) | Sharp 28S and 18S ribosomal RNA bands; 28S:18S intensity ≈ 2:1 | 1% denaturing agarose gel or Bioanalyzer |
| gDNA contamination | Ct > 35 or no amplification in no-RT control PCR | RT-qPCR with intron-spanning primers |

---

## Section B: Column Method (R1200)

### Protocol

| Step | Detail | Time | Notes |
|---|---|---|---|
| Lyse | Add 350 μL Lysis Buffer (+ β-ME, added fresh to a final concentration of 10 μL β-ME per 1 mL Buffer R1). Vortex 30 s | 1 min | β-ME reduces RNase activity by breaking disulfide bonds |
| Filter | Transfer lysate to gDNA removal column (purple ring) pre-placed in 2 mL collection tube. Centrifuge 12,000×g, 30 s at RT | 1 min | The gDNA column retains genomic DNA; the flow-through contains total RNA |
| Bind | Add 350 μL of 70% ethanol (RNase-free) to flow-through, mix by pipetting. Transfer to RNA binding column (blue ring). Centrifuge 12,000×g, 30 s | 2 min | The 70% ethanol creates binding conditions for RNA on the silica membrane |
| Wash 1 | Add 500 μL Wash Buffer (ethanol added). Centrifuge 12,000×g, 30 s. Discard flow-through | 1 min | |
| DNase step | Add 80 μL DNase I mix (10 μL DNase I + 70 μL DNase buffer) directly onto membrane. Incubate 15 min at RT | 15 min | Do not centrifuge during this step; the DNase digests residual gDNA bound to the membrane |
| Wash 2 | Add 500 μL Wash Buffer. Centrifuge 12,000×g, 30 s. Discard flow-through | 1 min | |
| Wash 3 | Add 500 μL Wash Buffer. Centrifuge 12,000×g, 30 s. Discard flow-through | 1 min | |
| Dry | Centrifuge 12,000×g for 2 min to remove residual ethanol | 2 min | |
| Elute | Transfer column to clean RNase-free tube. Add 30–50 μL RNase-free water to membrane center. Centrifuge 12,000×g, 1 min | 2 min | |
| **Total time** | | **~25 min** | |

### Quality Check (Column)

| Parameter | Acceptable Range | Notes |
|---|---|---|
| A₂₆₀/A₂₈₀ | 1.9–2.1 | Higher than 2.1 may indicate RNA degradation |
| A₂₆₀/A₂₃₀ | ≥1.8 | Lower suggests residual wash buffer or ethanol |
| Concentration | 30–1500 ng/μL | Lower yields than Trizol; adequate for most downstream applications |
| gDNA contamination | None detectable by intron-spanning PCR | The on-column DNase step effectively removes gDNA |

---

## Method Comparison

| Consideration | Trizol (R1100) | Column (R1200) |
|---|---|---|
| Yield (per mg tissue) | Higher (50–100 μg from 50 mg liver) | Moderate (30–80 μg from 50 mg liver) |
| Small RNA recovery | Yes (miRNA, siRNA, piRNA recovered) | No (<200 nt fragments depleted) |
| On-column DNase treatment | Not available — post-extraction only | Yes — included in protocol |
| Organic solvent usage | Chloroform and isopropanol required | None |
| Protocol time | ~40 min | ~25 min |
| Hands-on time | ~20 min | ~15 min |
| Purity (A₂₆₀/A₂₃₀) | ≥2.0 (with careful aqueous phase transfer) | ≥1.8 |
| Suitable for RNA-seq | Yes | Yes (with RIN >7) |
| Suitable for miRNA analysis | Yes (preserves small RNA) | No (small RNA depleted) |

---

## Troubleshooting Table

| Issue | Cause | Solution |
|---|---|---|
| Low A₂₆₀/A₂₃₀ (<1.8) | Phenol/guanidine contamination (Trizol) | Redo aqueous phase transfer more carefully; leave more behind |
| | Wash buffer carryover (Column) | Add an extra wash step; dry column for 2 min |
| Low RNA yield | Incomplete homogenization | Increase homogenization time; use liquid N₂ powdering for tough tissues |
| | Inadequate lysis | Increase Trizol or Lysis Buffer volume; reduce tissue input |
| | RNA pellet lost during washes | Centrifuge at higher g-force; pour off supernatant carefully |
| RNA degraded (gel shows smear, no 28S/18S) | RNase contamination | Use fresh RNase-free tips and tubes; DEPC-treat water; spray surfaces with 70% ethanol |
| | Sample not fresh | Process samples immediately after collection or snap-freeze in liquid N₂ |
| | Sample stored improperly | Store tissue in RNAlater or at −80°C; do not thaw without lyzing |
| gDNA contamination (Column) | DNase step skipped or shortened | Ensure 15 min incubation at RT; do not shorten this step |
| | gDNA removal column overloaded | Reduce tissue input to ≤30 mg per column |
| gDNA contamination (Trizol) | Interphase disturbed during aqueous phase transfer | Transfer less aqueous phase; leave a 2–3 mm safety margin above the interphase |

---

## Optimization Notes

- **For lipid-rich tissues (brain, adipose)**: Trizol method is preferred. After the chloroform step, the aqueous phase may be cloudy due to lipids. Avoid transferring any cloudy material — this may reduce yield but improves RNA purity. For column method, use up to 20 mg tissue only and centrifuge lysate to pellet lipids before loading onto the gDNA removal column.
- **For fibrous tissues (heart, muscle, plant leaves)**: Use a rotor-stator homogenizer or grind to a fine powder under liquid nitrogen before adding Trizol or Lysis Buffer. For plant samples, use the Plant RNA Extraction Kit (R1400) for optimal results.
- **For blood samples**: Use 250 μL fresh whole blood per extraction. For Trizol method, add 750 μL Trizol and proceed. For column method, lyse red blood cells with Erythrocyte Lysis Buffer before adding Lysis Buffer.
- **For cell culture**: Harvest 1–5 × 10⁶ cells per extraction. Wash cells with D-PBS (D1040) before adding Trizol or Lysis Buffer to remove residual serum which contains RNase inhibitors from FBS.
- **DNase treatment after Trizol extraction**: If gDNA-free RNA is critical (e.g., RT-qPCR for intronless targets), treat the dissolved RNA with RNase-free DNase I after Trizol extraction, followed by acid-phenol-chloroform purification or column cleanup.

---

*[solarbio.store](https://solarbio.store)*
