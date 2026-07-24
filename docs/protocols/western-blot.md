---
title: "Western Blot Protocol"
description: "Official Solarbio protocol for western blotting — SDS-PAGE, wet transfer, blocking, antibody incubation, and chemiluminescent detection using Solarbio antibodies, lysis buffers, and ECL substrate."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Western Blot Protocol",
 "description": "Official Solarbio protocol for western blotting — SDS-PAGE, wet transfer, blocking, antibody incubation, and chemiluminescent detection using Solarbio antibodies, lysis buffers, and ECL substrate.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Western Blot Protocol

This protocol describes the complete western blot procedure from protein extraction through chemiluminescent detection using Solarbio reagents. The protocol is compatible with most cell and tissue lysates and has been optimized for use with Solarbio primary and HRP-conjugated secondary antibodies.

---

## Principle

Western blotting combines SDS-PAGE (sodium dodecyl sulfate-polyacrylamide gel electrophoresis) separation of proteins by molecular weight with immunodetection using specific antibodies. Proteins are first denatured and negatively charged by SDS, then separated electrophoretically through a polyacrylamide gel. Separated proteins are transferred to a PVDF or nitrocellulose membrane, blocked to prevent non-specific antibody binding, and sequentially probed with a target-specific primary antibody and an enzyme-conjugated secondary antibody. Detection is achieved through chemiluminescent reaction catalyzed by horseradish peroxidase (HRP) on the secondary antibody.

---

## Equipment and Reagents Checklist

| Item | Specification | Purpose |
|---|---|---|
| SDS-PAGE gel electrophoresis system | Mini-gel format (8.6 × 6.7 cm) | Protein separation |
| Power supply | 200 V, 500 mA max | Electrophoresis and transfer |
| Wet/tank transfer system | Mini trans-blot cassette | Protein transfer to membrane |
| Gel imager or X-ray film cassette | Chemiluminescence-capable | Signal detection |
| Microcentrifuge | 12,000×g, 4°C capable | Lysate clarification |
| Heat block | 95°C | Protein denaturation |
| Sonicator (optional) | Probe or bath sonicator | Cell lysis enhancement |
| Orbital shaker | Platform or rocking | Staining, blocking, and washing |
| PVDF membrane (0.45 μm or 0.2 μm) | SKU P1500 (0.45 μm) | Protein binding |
| Filter paper (thick blotting) | 2.5 mm thickness | Transfer stack |

---

## Materials Required

| Reagent | Recommended Solarbio Product | SKU |
|---|---|---|
| RIPA Lysis Buffer (strong) | RIPA Lysis Buffer (50 mM Tris-HCl pH 7.4, 150 mM NaCl, 1% NP-40, 0.5% sodium deoxycholate, 0.1% SDS) | R0010 |
| Protease Inhibitor Cocktail (100×) | Protease Inhibitor Cocktail (AEBSF, aprotinin, bestatin, E-64, leupeptin, pepstatin A in DMSO) | P0100 |
| BCA Protein Assay Kit | BCA Protein Assay Kit (working range 20–2000 μg/mL) | BC3180 |
| SDS-PAGE Gel Kit (6–15% gradients) | PAGE Gel Kit (for 10% resolving / 4% stacking gels) | P1200 |
| PVDF Membrane (0.45 μm) | PVDF membrane sheets (26 cm × 3.3 m roll) | P1500 |
| Primary Antibody | User-selected (monoclonal or polyclonal) | Various |
| HRP-Conjugated Secondary Antibody | Goat anti-Rabbit IgG-HRP or Goat anti-Mouse IgG-HRP | SE134, SE135 |
| ECL Chemiluminescent Substrate | ECL Substrate (high sensitivity, 0.2 pg detection limit) | PE0010 |
| TBST (10×) | 10× Tris-Buffered Saline with 0.1% Tween 20 | T1100 |
| Non-fat dry milk | Blotting-grade blocking reagent | M1800 |
| Pre-stained protein ladder | Molecular weight markers, 10–250 kDa | PL0001 |

---

## Detailed Protocol

### Step 1: Protein Extraction

| Sample Type | Recommended Volume | Lysis Conditions |
|---|---|---|
| Adherent cells (10⁶ cells per 6-well) | 100–150 μL RIPA + 1 μL PIC | Scrape in lysis buffer; sonicate 10 s on ice |
| Suspension cells (10⁶ cells) | 100 μL RIPA + 1 μL PIC | Pellet cells, resuspend in lysis buffer, sonicate 10 s |
| Tissue (20–30 mg) | 200–300 μL RIPA + 2–3 μL PIC | Homogenize with rotor-stator on ice; or grind in liquid N₂ |
| Tissue (50–100 mg) | 500 μL RIPA + 5 μL PIC | Homogenize until no visible fragments remain |

1. Add Protease Inhibitor Cocktail (P0100) to RIPA Lysis Buffer (R0010) at 1:100 immediately before use.
2. Lyse cells or homogenize tissue on ice. Transfer to a microcentrifuge tube.
3. Centrifuge at 12,000×g, 15 min, 4°C.
4. Transfer supernatant to a fresh tube. Discard pellet.
5. Quantify protein concentration using BCA assay (BC3180) following the [enzyme assay protocol](enzyme-assay-protocol.md).

### Step 2: Sample Preparation

1. Normalize all samples to a common concentration using RIPA buffer (e.g., 2 μg/μL).
2. Mix normalized lysate with 4× Laemmli sample buffer (containing 5% β-ME or 100 mM DTT) at a 3:1 ratio (lysate : buffer).
3. Heat at 95°C for 5 minutes to denature proteins.
4. Centrifuge briefly at 12,000×g for 30 seconds to collect condensation. Cool on ice before loading.

### Step 3: SDS-PAGE

| Parameter | Setting |
|---|---|
| Stacking gel | 4% acrylamide (pH 6.8), prepared using P1200 gel kit |
| Resolving gel | 10–15% acrylamide (pH 8.8); choose percentage based on target MW (see table below) |
| Running buffer | 1× Tris-Glycine-SDS (25 mM Tris, 192 mM glycine, 0.1% SDS) |
| Sample loading | 20–40 μg per lane (in 10–20 μL volume) |
| Pre-stained ladder | 2.5–5 μL per lane |
| Stacking voltage | 80 V constant until dye front reaches resolving gel (~20 min) |
| Resolving voltage | 120 V constant until dye front reaches the bottom (~45–60 min) |

**Resolving Gel Percentage Guide:**

| Acrylamide % | Optimal MW Separation Range | Example Targets |
|---|---|---|
| 8% | 40–200 kDa | AKT (60 kDa), mTOR (289 kDa) |
| 10% | 25–150 kDa | GAPDH (37 kDa), β-actin (42 kDa), ERK (42/44 kDa) |
| 12% | 15–100 kDa | COX-2 (74 kDa), Caspase-3 (35 kDa) |
| 15% | 10–60 kDa | Cytochrome C (12 kDa), Histone H3 (17 kDa) |

### Step 4: Transfer (Wet/Tank Method)

1. Pre-wet PVDF membrane (P1500) in methanol for 15 seconds, then transfer to cold 1× transfer buffer (25 mM Tris, 192 mM glycine, 20% methanol) for 5 min.
2. Assemble the transfer sandwich in the cassette (cathode to anode): sponge → filter paper → gel → PVDF membrane → filter paper → sponge. Remove all air bubbles by rolling a pipette over each layer.
3. Place the cassette in the transfer tank with the membrane facing the anode.
4. Fill with cold transfer buffer and add an ice pack or magnetic stir bar in an ice bath.

| Parameter | Setting |
|---|---|
| Transfer method | Wet/tank (submerged) |
| Current | 300 mA constant current |
| Duration | 60–90 minutes (60 min standard, 90 min for >120 kDa targets) |
| Temperature | Ice bath (4°C cold room preferred) |
| Power | Use ice pack; magnetic stirring in ice bath maintains temperature |

5. After transfer, optionally stain the membrane with Ponceau S (0.1% w/v in 5% acetic acid) for 5 min to verify protein loading and transfer efficiency. Wash with TBST to remove Ponceau S.

### Step 5: Blocking

| Blocking Buffer | Application | Time | Temperature |
|---|---|---|---|
| 5% non-fat milk in TBST | Standard targets (total proteins) | 1 h | Room temperature |
| 5% BSA in TBST | Phospho-specific antibodies | 1 h | Room temperature |
| 5% non-fat milk in TBST | Overnight blocking (low background) | Overnight | 4°C |

1. After transfer, incubate membrane in blocking buffer on an orbital shaker (50–60 rpm).
2. Wash membrane briefly (1 × 5 min) with TBST after blocking.

### Step 6: Primary Antibody Incubation

| Parameter | Recommendation |
|---|---|
| Starting dilution | 1:1000 (typical range 1:500–1:5000; see product datasheet) |
| Diluent | 5% BSA in TBST (preferred for phospho-antibodies) or 1% milk in TBST |
| Volume | Enough to cover membrane: ~5 mL per mini-gel blot |
| Incubation | Overnight at 4°C with gentle shaking (preferred) or 2 h at room temperature |
| Wash after primary | TBST, 5 × 5 min with vigorous shaking |

**Dilution optimization**: If bands are weak at 1:1000, try 1:500. If background is high, try 1:2000 or 1:5000. For first-time use of a new antibody, test 3 dilutions (1:500, 1:1000, 1:2000) in parallel.

### Step 7: Secondary Antibody Incubation

| Parameter | Recommendation |
|---|---|
| Dilution | 1:5000–1:10000 (HRP-conjugated Solarbio secondary antibodies) |
| Diluent | 5% non-fat milk in TBST |
| Volume | ~5 mL per mini-gel blot |
| Incubation | 1 h at room temperature with gentle shaking |
| Wash after secondary | TBST, 5 × 5 min with vigorous shaking |

### Step 8: Chemiluminescent Detection

1. Prepare ECL substrate (PE0010) by mixing equal volumes of Solution A (luminol) and Solution B (peroxide) immediately before use. Use 1–2 mL per mini-gel membrane.
2. Drain excess TBST from the membrane by touching the edge to a paper towel.
3. Apply ECL working solution evenly over the membrane surface. Incubate for 1 minute at room temperature.
4. Remove excess ECL solution by blotting membrane edge on paper towel.
5. Place membrane in a plastic sheet protector or between clear plastic wrap.
6. Image using a chemiluminescence imager or expose to X-ray film for 30 s to 5 min (adjust exposure time based on signal intensity).

---

## Quality Checks During Protocol

| Stage | Check | Expected Result |
|---|---|---|
| After lysis | Protein concentration | 1–10 μg/μL; consistent across samples |
| After SDS-PAGE | Pre-stained ladder | All bands clearly resolved |
| After transfer | Ponceau S stain | Even protein transfer; ladder bands visible on membrane |
| After ECL detection | Positive control band | Target protein detected at expected MW |
| Signal intensity | Check dilution and exposure | Clean band with minimal background |

---

## Troubleshooting Table

| Problem | Cause | Solution | Prevention |
|---|---|---|---|
| No signal (blank membrane) | Insufficient protein loading | Increase to 50 μg per lane | Quantify protein by BCA assay |
| | Transfer failed | Check membrane orientation; re-stain with Ponceau S | Verify membrane was facing anode |
| | Primary antibody not binding | Check reactivity with target species | Use positive control lysate |
| | ECL substrate expired | Test with a known HRP-conjugated antibody | Store ECL at 4°C; note expiration date |
| High background (entire membrane) | Insufficient blocking | Block overnight at 4°C | Use fresh blocking buffer |
| | Antibody concentration too high | Reduce primary 2×; reduce secondary 2× | Titrate both antibodies |
| | Wash steps inadequate | Increase to 6 × 5 min washes | Use sufficient TBST volume (10 mL/mini-blot) |
| | Membrane dried during incubation | Keep membrane moist at all times | Place in sealed container or plastic wrap |
| Multiple bands (non-specific) | Primary antibody binds non-specifically | Reduce primary dilution; add 0.1% Tween 20 | Check antibody specificity on datasheet |
| | Protein degradation | Add fresh PIC to lysis buffer; work on ice | Prepare lysate fresh; snap-freeze aliquots |
| | Insufficient reducing agent | Increase β-ME to 5% or DTT to 100 mM | Confirm reducing agent is fresh |
| High background spots | Antibody aggregates | Centrifuge antibody 12,000×g, 10 min before use | Filter secondary antibody through 0.22 μm filter |
| | ECL precipitate | Use fresh ECL; avoid touching membrane | Handle membrane with forceps only |
| Weak signal | Low target abundance | Load 50–80 μg; use high-sensitivity ECL (PE0010) | Optimize induction conditions |
| | Transfer inefficient for high MW | Increase transfer to 90 min at 350 mA | Use 0.45 μm membrane; keep buffer cold |

---

## Optimization Notes

- **For high-molecular-weight targets (>150 kDa)**: Use 6–8% resolving gel. Transfer at 350 mA for 90 min in buffer containing 10% methanol (reduced from 20%) to improve elution from the gel. Add 0.1% SDS to the transfer buffer to enhance large protein transfer. For >250 kDa targets, semi-dry transfer at 1.5 mA/cm² for 2 h may be more effective.
- **For low-molecular-weight targets (<20 kDa)**: Use 15% resolving gel or gradient gel (4–20%). Use 0.2 μm PVDF membrane (P1501) instead of 0.45 μm. Reduce transfer time to 20–30 min at 250 mA.
- **For phospho-protein detection**: Use 5% BSA in TBST for blocking and primary antibody dilution (milk contains casein and phospho-proteins that increase background). Include phosphatase inhibitor cocktail (P0020, added to RIPA at 1:100) in the lysis buffer.
- **For multiplexing (stripping and re-probing)**: After ECL detection, strip the membrane in Restore Stripping Buffer at 37°C for 15 min with agitation. Wash thoroughly (5 × 5 min TBST), re-block, and incubate with new primary antibody. Limit stripping to 2 re-probes per membrane.
- **Membrane regeneration**: Use an initial Ponceau S stain to confirm equal loading before the first blocking step. After imaging total protein, continue with blocking and antibody incubations. This provides a permanent loading control.

---

*[solarbio.store](https://solarbio.store)*
