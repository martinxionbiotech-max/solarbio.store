---
title: "Technical Specification: Apoptosis Detection Kits"
description: "Technical specifications for Solarbio apoptosis detection kits — Annexin V-FITC/PI dual staining, TUNEL assay, and caspase activity detection. Detailed assay mechanisms, reaction equations, detection limits, and protocol optimization for flow cytometry and microscopy applications."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "TechArticle",
 "headline": "Technical Specification: Apoptosis Detection Kits",
 "description": "Technical specifications for Solarbio apoptosis detection kits — Annexin V-FITC/PI dual staining, TUNEL assay, and caspase activity detection. Detailed assay mechanisms, reaction equations, detection limits, and protocol optimization for flow cytometry and microscopy applications.",
 "author": {"@type": "Organization", "name": "Beijing Solarbio Science & Technology Co., Ltd.", "url": "https://solarbio.store"},
 "publisher": {"@type": "Organization", "name": "Solarbio", "url": "https://solarbio.store"}
}
</script>



# Technical Specification: Apoptosis Detection Kits

## 1. Product Range

| Product | SKU | Method | Detection Platform | Assays per Kit |
|---|---|---|---|---|
| Annexin V-FITC Apoptosis Detection Kit | CA1020 | Annexin V-FITC/PI dual stain | Flow cytometry, fluorescence microscopy | 50–100 assays |
| TUNEL Apoptosis Assay Kit | CA1040 | TdT-mediated dUTP nick end-labeling | Fluorescence microscopy | 50 assays |
| Caspase-3 Activity Assay Kit | BC3830 | DEVD-pNA cleavage, 405 nm | Microplate reader | 100 assays |
| Annexin V-APC/PI Apoptosis Detection Kit | CA1025 | Annexin V-APC/PI dual stain | Flow cytometry (APC channel compatible) | 50–100 assays |
| Hoechst 33342/PI Double Stain Kit | CA1120 | Hoechst 33342 + PI dual stain | Fluorescence microscopy | 100 assays |

## 2. Technical Parameters

### Annexin V-FITC/PI Kit (CA1020)

**Principle:** Annexin V is a 35.8 kDa Ca²⁺-dependent phospholipid-binding protein with high affinity for phosphatidylserine (PS). In viable cells, PS is sequestered to the inner leaflet of the plasma membrane by flippase (an ATP-dependent aminophospholipid translocase). During early apoptosis, flippase is inactivated and scramblase is activated, causing PS externalization to the outer membrane leaflet. Annexin V-FITC binds exposed PS. Propidium Iodide (PI) is a membrane-impermeant nucleic acid dye that enters only cells with compromised plasma membranes (late apoptosis or necrosis).

The binding reaction:

```
PS(externalized) + Annexin V-FITC  →  PS-Annexin V-FITC complex
  (Ca²⁺-dependent, Kd ≈ 5 nM)
```

| Parameter | Specification |
|---|---|
| Cell preparation | 1×10⁵–5×10⁵ cells per assay |
| Staining time | 15 min at room temperature (dark) |
| Detection wavelengths | FITC Ex/Em: 488/525 nm; PI Ex/Em: 535/615 nm |
| Binding buffer | 10 mM HEPES/NaOH pH 7.4, 140 mM NaCl, 2.5 mM CaCl₂ |
| Viable cells | Annexin V⁻, PI⁻ |
| Early apoptosis | Annexin V⁺, PI⁻ |
| Late apoptosis/necrosis | Annexin V⁺, PI⁺ |
| Necrosis (primary) | Annexin V⁻, PI⁺ |
| Kit storage | 2–8°C, 12 months |
| Detection limit | ≥1% apoptotic cells in population |

### TUNEL Assay Kit (CA1040)

**Principle:** During apoptosis, endonucleases (primarily CAD — caspase-activated DNase) cleave genomic DNA at internucleosomal linker regions, generating double-strand breaks with 3′-hydroxyl (3′-OH) ends. Terminal deoxynucleotidyl transferase (TdT) catalyzes the template-independent incorporation of fluorescein-dUTP onto these 3′-OH ends. The incorporated fluorescein can then be detected by fluorescence microscopy or flow cytometry.

The enzymatic reaction:

```
DNA(3′-OH ends) + Fluorescein-dUTP  →  DNA-3′-Fluorescein-dUMP + PPi
              ↑                          ↑
            TdT enzyme        Catalyzed by TdT
```

| Parameter | Specification |
|---|---|
| Sample type | Fixed cells, paraffin-embedded tissue sections |
| Fixation | 4% paraformaldehyde, 15 min at RT |
| Permeabilization | 0.1% Triton X-100 in 0.1% sodium citrate, 2 min on ice |
| TdT incubation | 60 min at 37°C (dark, humidified) |
| Detection | Fluorescein Ex/Em: 488/525 nm |
| Counterstain | DAPI or PI |
| Positive control | DNase I-treated sample (10 U/mL, 10 min at RT) |
| Kit storage | -20°C, 12 months |

### Caspase-3 Activity Assay Kit (BC3830)

**Principle:** Caspase-3 (CPP32/apopain), a 32 kDa proenzyme classified as an executioner caspase, is proteolytically cleaved at Asp175-Ser176 and Asp28-Ser29 to generate active p17 and p12 subunits during apoptosis. The kit uses a synthetic tetrapeptide substrate, DEVD-pNA (Asp-Glu-Val-Asp conjugated to p-nitroaniline). Active caspase-3 cleaves the DEVD-pNA substrate, releasing free pNA, which absorbs at 405 nm.

The enzymatic reaction:

```
Ac-DEVD-pNA  →  Ac-DEVD-OH + pNA
        ↑                              ↑
    Caspase-3             Free pNA (absorbs at 405 nm)
```

| Parameter | Specification |
|---|---|
| Substrate | Ac-DEVD-pNA (200 μM final concentration) |
| Detection wavelength | 405 nm (reference 630 nm) |
| Incubation time | 1–2 h at 37°C |
| Protein input | 20–100 μg total protein per assay |
| LOD (recombinant caspase-3) | ~1 U/mL |
| Linear detection range | 1–50 U/mL recombinant caspase-3 |
| Intra-assay CV | <8% |
| Kit storage | -20°C, 12 months |
| Total assay time | Approximately 2.5 h |

## 3. Performance Data — Representative Caspase-3 Activity Standard Curve

| Recombinant Caspase-3 (U/mL) | A₄₀₅ (Mean ± SD, n=3) | CV% |
|---|---|---|
| 0 (blank) | 0.025 ± 0.002 | 8.0 |
| 0.5 | 0.032 ± 0.002 | 6.3 |
| 1 | 0.042 ± 0.003 | 7.1 |
| 2.5 | 0.076 ± 0.004 | 5.3 |
| 5 | 0.135 ± 0.005 | 3.7 |
| 10 | 0.248 ± 0.008 | 3.2 |
| 25 | 0.512 ± 0.015 | 2.9 |
| 50 | 0.898 ± 0.022 | 2.5 |

## 4. Protocol Optimization Guidelines

### Cell Treatment Duration for Apoptosis Induction

| Inducer | Typical Concentration | Recommended Duration |
|---|---|---|
| Staurosporine (broad kinase inhibitor) | 1 μM | 4–6 h (early apoptosis) |
| Etoposide (topoisomerase II inhibitor) | 10–50 μM | 12–24 h |
| Doxorubicin (DNA intercalator) | 1–10 μM | 12–24 h |
| Actinomycin D (transcription inhibitor) | 0.1–1 μg/mL | 6–12 h |
| UV irradiation (254 nm) | 50–100 J/m² | 4–8 h post-exposure |
| Fas ligand (300 ng/mL) + cycloheximide | 1 μg/mL | 4–6 h |
| H₂O₂ (oxidative stress) | 100–500 μM | 2–6 h |

### Critical Considerations for Each Method

| Method | Key Optimization Parameters | Common Pitfalls |
|---|---|---|
| Annexin V-FITC/PI | Ca²⁺ concentration in binding buffer; gentle resuspension | Excessive washing loses early apoptotic cells; prolonged incubation (>1 h) allows late-stage PI uptake |
| TUNEL | Permeabilization time; TdT concentration | Over-permeabilization causes false positives; insufficient TdT reduces sensitivity |
| Caspase-3 Activity | Protein input normalization; substrate saturating concentration | Degraded lysates lose activity; hemoglobin/heme interference in 405 nm read |

## 5. Related Products and Cross-References

- [▶ Related Protocol: Cell Culture Protocol](../protocols/cell-culture-protocol.md)
- [▶ See also: Cell Staining Reagents](cell-staining.md)
- [▶ See also: Flow Cytometry Reagents](../immunology/flow-cytometry.md)

*For product procurement: [solarbio.store](https://solarbio.store)*
