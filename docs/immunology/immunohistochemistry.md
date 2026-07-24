---
title: "Technical Specification: Immunohistochemistry Reagents"
description: "Technical specifications for Solarbio immunohistochemistry products — IHC detection systems (HRP/DAB polymer), antigen retrieval buffers (citrate pH 6.0, EDTA pH 9.0), DAB chromogen substrate, and ancillary reagents. Protocol optimization, troubleshooting, and signal amplification specifications."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Immunohistochemistry Reagents",
 "description": "Technical specifications for Solarbio immunohistochemistry products — IHC detection systems (HRP/DAB polymer), antigen retrieval buffers (citrate pH 6.0, EDTA pH 9.0), DAB chromogen substrate, and ancillary reagents. Protocol optimization, troubleshooting, and signal amplification specifications.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Immunohistochemistry Reagents

## 1. Product Range

Solarbio IHC reagents cover the complete immunohistochemistry workflow — from antigen retrieval and blocking through detection, chromogenic visualization, and counterstaining. All detection systems are validated for formalin-fixed paraffin-embedded (FFPE) tissue sections and frozen sections.

| Product | SKU | Application | Format |
|---|---|---|---|
| IHC Detection Kit (HRP/DAB, mouse) | SP0020 | DAB chromogenic IHC — mouse primary antibodies | 50–200 tests |
| IHC Detection Kit (HRP/DAB, rabbit) | SP0022 | DAB chromogenic IHC — rabbit primary antibodies | 50–200 tests |
| IHC Detection Kit (HRP/DAB, mouse/rabbit) | SP0025 | DAB chromogenic IHC — mouse and rabbit primary antibodies | 50–200 tests |
| Antigen Retrieval Buffer (Citrate, pH 6.0) | C1030 | Heat-induced epitope retrieval (HIER) | 500 mL, 1 L (1×) |
| Antigen Retrieval Buffer (EDTA, pH 9.0) | C1032 | Heat-induced epitope retrieval (HIER) | 500 mL, 1 L (1×) |
| DAB Chromogen Kit | DAB0030 | Brown chromogenic detection | 500 reactions (15 mL) |
| Normal Goat Serum | S0100 | Blocking, IHC/IF | 10 mL, 50 mL |
| Hematoxylin (Mayer's) | H8070 | Nuclear counterstain | 500 mL |
| Permanent Mounting Medium | M8430 | Coverslip mounting, xylene-based | 15 mL |
| Aqueous Mounting Medium | M8440 | Coverslip mounting, water-based | 15 mL |
| IHC PAP Pen | P2600 | Hydrophobic barrier for tissue sections | 1 pen (4 mL) |

## 2. IHC Detection System Specifications

Solarbio IHC Detection Kits use a **dextran polymer technology** that conjugates multiple HRP molecules to a single polymer backbone, which is already linked to secondary antibodies. This polymer-based detection system provides higher sensitivity (3–5×) than traditional avidin-biotin complex (ABC) methods, with lower background and fewer steps.

| Parameter | SP0020 / SP0022 / SP0025 |
|---|---|
| Detection mechanism | Dextran polymer-HRP conjugated to secondary antibody (polymer chain) |
| Signal amplification | Direct polymer (no biotin-avidin step); ~40 HRP molecules per polymer |
| Sensitivity | Equivalent to or greater than ABC method; no biotin interference |
| Species reactivity (SP0025) | Mouse IgG and rabbit IgG |
| Primary antibody requirement | 100–500 μg/mL for optimal signal |
| DAB incubation | 3–10 min at RT (monitor microscopically) |
| Counterstain | Hematoxylin (Mayer's), 30–60 s |
| Total detection time | Approximately 30 min (after primary antibody) |
| Storage | 2–8°C, 12 months (do not freeze) |
| Endogenous biotin interference | Eliminated (no biotin in detection system) |
| Endogenous peroxidase | Requires 3% H₂O₂ blocking step (included in kit) |

## 3. Antigen Retrieval Buffer Specifications

### 3.1 Mechanism of Antigen Retrieval

Formalin fixation creates methylene cross-links between proteins, masking epitopes and reducing antibody accessibility. Heat-induced epitope retrieval (HIER) uses high temperature (95–120°C) to hydrolyze these cross-links, restoring protein conformation for antibody binding. The pH of the retrieval buffer critically affects which epitopes are exposed.

### 3.2 Citrate Buffer (pH 6.0, C1030) vs. EDTA Buffer (pH 9.0, C1032)

| Parameter | Citrate Buffer (pH 6.0) | EDTA Buffer (pH 9.0) |
|---|---|---|
| Composition | 10 mM sodium citrate, 0.05% Tween 20 | 1 mM EDTA, 0.05% Tween 20 |
| Final pH (1×) | 6.0 ± 0.1 | 9.0 ± 0.1 |
| Retrieval mechanism | High-temperature hydrolysis at mild pH | High-temperature hydrolysis at alkaline pH; stronger cross-link breakage |
| Recommended antibodies | Nuclear and cytoplasmic targets | Membrane-bound and some nuclear targets |
| Tissue compatibility | All tissue types | All tissue types; may cause section detachment with prolonged heating |
| Heating method | Microwave, autoclave, pressure cooker, water bath | Microwave, autoclave, pressure cooker, water bath |
| Typical heating time | 15–20 min at 95–100°C | 10–15 min at 95–100°C |
| Cooling time | 20–30 min at RT | 20–30 min at RT |
| Reuse | Single use only | Single use only |

### 3.3 Antigen Retrieval Decision Guide

| Target | Recommended Buffer | Notes |
|---|---|---|
| Ki-67 (nuclear proliferation marker) | Citrate pH 6.0 | 20 min microwave; excellent nuclear signal |
| HER2/neu (membrane, breast cancer) | EDTA pH 9.0 | Alkaline retrieval enhances membrane staining |
| CD3 (T-cell membrane) | EDTA pH 9.0 | Membrane signal stronger with alkaline retrieval |
| p53 (nuclear, tumor suppressor) | Citrate pH 6.0 | Nuclear accumulation detectable |
| CK7/CK20 (cytoplasmic, cytokeratins) | Citrate pH 6.0 or EDTA pH 9.0 | Both work; citrate preferred for cleaner background |
| ER/PR (nuclear, hormone receptors) | Citrate pH 6.0 | Standard for breast cancer IHC panels |
| CD20 (B-cell membrane) | Citrate pH 6.0 | Robust membrane staining |
| PD-L1 (membrane/cytoplasmic) | EDTA pH 9.0 | Alkaline retrieval improves PD-L1 staining |
| Vimentin (cytoplasmic) | EDTA pH 9.0 | Strong signal with alkaline buffer |

## 4. DAB Chromogen Kit (DAB0030)

**Principle:** 3,3′-Diaminobenzidine (DAB) is oxidized by HRP in the presence of hydrogen peroxide to produce a brown, insoluble precipitate at the site of the antigen-antibody reaction. The DAB polymer is alcohol- and xylene-resistant, allowing for permanent mounting.

```
DAB (reduced, colorless)  →  DAB (oxidized, brown precipitate)
                    ↑     
                HRP + H₂O₂
```

| Parameter | Specification |
|---|---|
| Composition | DAB tablet (10 mg) + DAB buffer (15 mL H₂O₂ in stabilizing solution) |
| Preparation | Dissolve 1 DAB tablet in 1 mL DAB buffer; then add 14 mL distilled water |
| Working solution stability | 2–8°C, 1 week (dark) |
| Color | Brown |
| Water solubility (after oxidation) | Insoluble (permanent) |
| Counterstain compatibility | Hematoxylin (blue nuclei); methyl green |
| Dehydration | Dehydrate through graded alcohols, clear in xylene |
| Mounting | Xylene-based permanent mounting medium |
| Sensitivity | 3–5 ng of target per section (approximately 100–500 molecules/cell) |
| Storage | -20°C, 12 months (tablet desiccated) |

## 5. Protocol Overview

| Step | Reagent | Time | Temperature | Notes |
|---|---|---|---|---|
| 1. Deparaffinize/Hydrate | Xylene (3×), 100% → 70% ethanol, water | 30 min | RT | Complete deparaffinization is critical; insufficient xylene time → patchy staining |
| 2. Antigen retrieval | Citrate pH 6.0 or EDTA pH 9.0 | 15–20 min | 95–100°C | Microwave 5 min × 3 at medium-high power; do not boil dry |
| 3. Cool | Retrieval buffer | 20–30 min | RT | Let slides cool in buffer; rapid cooling may cause antigen collapse |
| 4. Block endogenous peroxidase | 3% H₂O₂ in methanol or PBS | 10–15 min | RT | Covers entire section; wash 3× PBS |
| 5. Blocking | Normal goat serum (10% in PBS) | 30 min | RT | Do not wash; tap off excess |
| 6. Primary antibody | Diluted in PBS | Overnight | 4°C | Or 1 h at 37°C; use humidified chamber |
| 7. Wash | PBS | 5 min × 3 | RT | Gentle agitation |
| 8. Detection system | HRP-polymer conjugate | 30 min | RT | Eliminates need for biotin blocking |
| 9. Wash | PBS | 5 min × 3 | RT | Thorough washing reduces background |
| 10. DAB | DAB + H₂O₂ substrate | 3–10 min | RT | Monitor microscopically; stop when target turns brown |
| 11. Wash | Distilled water | 5 min | RT | Remove excess DAB |
| 12. Counterstain | Hematoxylin (Mayer's) | 30–60 s | RT | Filter hematoxylin before use |
| 13. Blue | Tap water (bluing) | 5 min | RT | Change water until clear |
| 14. Dehydrate | 70% → 100% ethanol, xylene | 5 min each | RT | Clear in xylene before mounting |
| 15. Mount | Permanent mounting medium | — | RT | Coverslip; avoid air bubbles |

## 6. Troubleshooting

| Issue | Possible Cause | Solution |
|---|---|---|
| No staining | Antigen retrieval failed; primary antibody inactive | Increase retrieval time; verify primary on positive control tissue |
| Weak staining | Insufficient retrieval; primary dilution too low | Titrate primary; use EDTA pH 9.0 instead of citrate; extend DAB to 10 min |
| High background (nuclear) | Primary antibody cross-reactivity; retrieval too harsh | Reduce retrieval time; try reduced primary concentration |
| High background (diffuse) | Inadequate blocking; secondary polymer overspill | Increase blocking to 1 h; wash more thoroughly |
| Tissue detachment | Over-heating during retrieval; slides not coated | Use poly-L-lysine or silane-coated slides; reduce heating time |
| DAB precipitates in solution | DAB solution old; self-polymerization | Prepare fresh DAB; use within 15 min |
| Patchy staining | Incomplete deparaffinization; uneven antigen retrieval | Extend xylene time to 30 min; ensure full coverage with retrieval buffer |
| Hematoxylin too dark | Over-counterstaining | Reduce hematoxylin to 15–20 s; use automated staining |

## 7. Cross-References

- [▶ Related Protocol: Western Blot](../protocols/western-blot.md)
- [▶ See also: Antibodies](antibodies.md)
- [▶ See also: ELISA Kits](elisa-kits.md)
- [▶ See also: Flow Cytometry Reagents](flow-cytometry.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
