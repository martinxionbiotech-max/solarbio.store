---
title: "Competent Cell Transformation Protocol"
description: "Official Solarbio protocol for chemical transformation of competent cells — heat-shock method for DH5α (C1100), DH5α-T1 (C1180), and BL21(DE3) (C1300) strains with efficiency data and troubleshooting."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Competent Cell Transformation Protocol",
 "description": "Official Solarbio protocol for chemical transformation of competent cells — heat-shock method for DH5α (C1100), DH5α-T1 (C1180), and BL21(DE3) (C1300) strains with efficiency data and troubleshooting.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Competent Cell Transformation Protocol

Using Solarbio Competent Cells: DH5α (C1100), DH5α-T1 (C1180), BL21(DE3) (C1300). This protocol covers chemical transformation via the standard heat-shock method, applicable to all Solarbio chemically competent _E. coli_ strains.

---

## Principle

Chemical transformation uses calcium chloride-treated competent cells to introduce exogenous DNA through the bacterial membrane during a controlled heat-shock step. The Ca²⁺ ions neutralize electrostatic repulsion between the DNA phosphate backbone and the negatively charged cell membrane, while the temperature shift (0°C to 42°C) creates transient membrane permeability that allows DNA entry. Following a recovery period in rich medium, cells express antibiotic resistance and can be selected on solid medium.

---

## Equipment and Reagents Checklist

| Item | Specification | Purpose |
|---|---|---|
| Water bath or heat block | 42°C (precisely calibrated) | Heat shock |
| Ice bath | Crushed ice with water | Cell handling |
| Shaking incubator | 37°C, 200 rpm rotation | Outgrowth/recovery |
| Static incubator | 37°C | Plate incubation |
| Microcentrifuge | Standard, for small volumes | Not required for standard protocol |
| SOC medium | SKU M2100 | Recovery/outgrowth |
| LB agar plates | Pre-poured with appropriate antibiotic | Colony selection |
| Sterile spreader | L-shaped glass or plastic | Even bacteria plating |
| P20 and P200 pipettes | Filtered tips recommended | DNA addition and plating |
| Sterile culture tubes | 14–17 mL (Falcon round-bottom or equivalent) | Recovery incubation |

---

## Materials

| Item | Solarbio SKU |
|---|---|
| Competent cells (50 μL aliquots) | Various (C1100, C1180, C1300) |
| SOC medium (2% tryptone, 0.5% yeast extract, 10 mM NaCl, 2.5 mM KCl, 10 mM MgCl₂, 20 mM glucose) | M2100 |
| LB agar plates (with appropriate antibiotic) | Pre-poured or prepared from LB Agar (L1010) |
| pUC19 control DNA | Provided with competent cells |
| Ice bath | — |
| 42°C water bath | — |

---

## Detailed Protocol (Step by Step)

### Step 1: Thaw Competent Cells

1. Remove competent cells from −80°C storage and place immediately on dry ice or directly into an ice bath.
2. Allow cells to thaw on ice for 5–10 minutes. Do not vortex, do not warm above 4°C, and do not pipette to resuspend — the cells will settle naturally.
3. Gently flick the tube 2–3 times when a small ice crystal remains to complete the thaw.
4. **Critical**: Once thawed, cells must remain on ice. Transformation efficiency drops rapidly if cells warm above 4°C.

### Step 2: DNA Addition

1. Add 1–5 μL ligation product or 0.1–10 ng purified plasmid DNA directly into 50 μL competent cells.
2. Flick the tube gently 3–4 times to mix. Do not pipette up and down — shear forces can damage competent cells.
3. **Positive control**: Add 1 μL (10 pg) pUC19 control DNA to a separate 50 μL aliquot.
4. **Negative control**: Add 1 μL nuclease-free water to a separate 50 μL aliquot (no DNA control).

### Step 3: Incubation on Ice

1. Incubate the DNA-cell mixture on ice for 30 minutes.
2. Do not shorten this incubation — the 30-minute ice incubation is essential for DNA binding to the cell surface.

### Step 4: Heat Shock

1. Transfer the tube to a 42°C water bath or heat block for exactly 45 seconds.
2. The timing is critical — 45 seconds at 42°C is optimal for all Solarbio chemically competent strains. Longer (>60 s) reduces cell viability; shorter (<30 s) reduces DNA uptake.

| Strain | Heat Shock Temp | Duration | Purpose |
|---|---|---|---|
| DH5α (C1100) | 42°C | 45 s | Routine cloning, blue-white screening |
| DH5α-T1 (C1180) | 42°C | 45 s | High-efficiency cloning, large constructs |
| BL21(DE3) (C1300) | 42°C | 45 s | Protein expression (T7 promoter system) |

### Step 5: Recovery on Ice

1. Immediately return the tube to ice for 2 minutes. This stabilizes the cells after the thermal shock.

### Step 6: Outgrowth in SOC Medium

1. Add 500 μL SOC medium (M2100) pre-warmed to 37°C to each tube.
2. Mix gently by inverting or flicking.
3. Incubate at 37°C with shaking at 200 rpm for exactly 1 hour.
4. For BL21(DE3) expression strains, the 1-hour recovery at 37°C is sufficient. Do not exceed 1 hour or cells may enter stationary phase and show reduced viability.

### Step 7: Plate Transformants

1. Spread the appropriate volume onto pre-warmed LB agar plates containing the selective antibiotic:

| Transformation Type | Volume to Plate | Expected Outcome |
|---|---|---|
| Plasmid (high efficiency) | 10–50 μL | >100 colonies (typically lawn at 50 μL) |
| Ligation (low efficiency) | 100–200 μL | 10–200 colonies |
| Control (pUC19, 10 pg) | 50 μL | >500 colonies (DH5α-T1) |
| No DNA control | 100 μL | 0 colonies |

2. Spread evenly using a sterile spreader until the liquid is fully absorbed.
3. Invert plates and incubate overnight (14–18 hours) at 37°C.
4. **Do not incubate longer than 18 hours** — satellite colonies may appear with certain antibiotic selections.

---

## Quality Checks During Protocol

| Stage | Check | Expected Result |
|---|---|---|
| After thaw | Cells on ice throughout | Cells remain cold until heat shock |
| After heat shock | Timer accuracy | Exactly 45 sec at 42°C |
| Positive control (pUC19) | Colonies on ampicillin plate | >1000 (DH5α), >5000 (DH5α-T1) |
| Negative control (water) | Colonies on plate | 0 colonies |
| No-DNA control | Colonies on plate | 0 colonies (no contamination) |

---

## Expected Results

| Strain | pUC19 (10 pg) Competence | Ligated Vector | Comments |
|---|---|---|---|
| DH5α (C1100) | ≥1 × 10⁸ CFU/μg (>1000 colonies) | 10–200 colonies | Routine subcloning, blue-white screening |
| DH5α-T1 (C1180) | ≥1 × 10⁹ CFU/μg (>5000 colonies) | 50–500 colonies | High-efficiency cloning; T1 phage resistant |
| BL21(DE3) (C1300) | ≥2 × 10⁷ CFU/μg (>200 colonies) | — | Protein expression; contains T7 RNA polymerase gene |

---

## Efficiency Data

| Parameter | DH5α (C1100) | DH5α-T1 (C1180) | BL21(DE3) (C1300) |
|---|---|---|---|
| Transformation efficiency (pUC19) | ≥1 × 10⁸ CFU/μg | ≥1 × 10⁹ CFU/μg | ≥2 × 10⁷ CFU/μg |
| Blue-white screening | White colonies (lacZΔM15 intact) | White colonies (lacZΔM15 intact) | Not applicable |
| Recombination | recA1 (reduced, suitable for unstable inserts) | recA1 (reduced, suitable for unstable inserts) | Not required |
| Endonuclease | endA1 (improved plasmid quality) | endA1 (improved plasmid quality) | N/A |
| Phage resistance | F− | F−, tonA (T1/T5 phage resistant) | F− |
| Genotype key features | φ80lacZΔM15, Δ(lacZYA-argF)U169 | φ80lacZΔM15, Δ(lacZYA-argF)U169, tonA (T1R) | F− ompT hsdSB(rB− mB−) gal dcm rne131 (DE3) |

---

## Troubleshooting Table

| Problem | Cause | Solution | Prevention |
|---|---|---|---|
| No colonies on positive control | Competent cells dead | Use fresh cells from −80°C; do not leave on ice >30 min | Store at −80°C; never re-freeze after thawing |
| | Heat shock temperature wrong | Calibrate 42°C water bath with thermometer | Verify water bath temperature monthly |
| | Heat shock too short | Time exactly 45 s | Use a timer; do not approximate |
| | Antibiotic overdose | Verify antibiotic concentration; check plate preparation date | Use antibiotic within expiration; store at 4°C (dark) |
| No colonies on ligation plate | Ligation failed | Run ligation product on gel to check insert | Use positive control ligation; include T4 ligase control |
| | Ligase inhibitor present | Purify ligation product (column cleanup) | Ensure gel extraction removes all gel solubilization buffer |
| | Too much ligation product | Reduce to 1 μL per transformation | Ligation products >5 μL may inhibit transformation |
| | Insert-to-vector ratio suboptimal | Test 3:1 and 5:1 molar ratios | Calculate molar ratio; do not use mass or volume ratio |
| Satellite colonies | β-lactamase degradation | Use fresh antibiotic at correct concentration | Store ampicillin plates at 4°C ≤4 weeks |
| | Incubation >18 h | Harvest colonies after 14–16 h | Set incubation timer at 14 h |
| Lawn of colonies (no selection) | Missing antibiotic | Verify plate preparation | Always include no-DNA control |
| | Contaminated SOC medium | Filter-sterilize SOC medium | Prepare SOC fresh or use commercial M2100 |
| Blue colonies (X-Gal/IPTG plates) | IPTG not active | Add fresh IPTG to plates | Store IPTG at −20°C; protect from light |
| | Insert cloned but no disruption of lacZ | Check reading frame | Subclone into different restriction site |

---

## Optimization Notes

- **For high-efficiency cloning (DH5α-T1)**: Plate only 10 μL of the outgrowth culture. The efficiency of ≥1 × 10⁹ CFU/μg means 50 μL plating will produce a lawn on LB-ampicillin plates with standard pUC19 transformation.
- **For library construction**: Use DH5α-T1 (C1180) and electrocompetent cells (C1100-E) for maximum efficiency. Electroporation typically yields 2–10× higher efficiency than chemical transformation. For electroporation, use 0.1 cm cuvettes at 1.8 kV, 25 μF capacitance, 200 Ω resistance.
- **For BL21(DE3) protein expression**: After picking a single colony, inoculate 5 mL LB with antibiotic and 1% glucose (to suppress basal T7 expression). Grow at 37°C to OD₆₀₀ = 0.4–0.6, then induce with 0.1–1.0 mM IPTG. Optimal induction time and IPTG concentration must be empirically determined for each target protein.
- **Scaling up plasmid production**: For maxi-prep scale (500 mL culture), transform with diluted plasmid (0.1–1 ng) and use a single colony to inoculate the starter culture. This minimizes the risk of satellite colonies and ensures clonal homogeneity.

---

*[solarbio.store](https://solarbio.store)*
