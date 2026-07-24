---
title: "Frequently Asked Questions"
description: "Answers to common technical questions about Solarbio products — product selection, protocol troubleshooting, COA requests, shipping, storage, quality documentation, publication citations, and instrument compatibility."
---

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "FAQPage",
 "mainEntity": [
   {"@type": "Question", "name": "How do I select the correct PCR master mix?", "acceptedAnswer": {"@type": "Answer", "text": "Select based on template GC content, amplicon length, and application. Standard 2×Taq MasterMix (PC1150) works for routine PCR (0.5–3 kb). For high-GC or long templates, use 2×Taq Plus (PC1155). For qPCR, use SYBR Green (SR1110) or TaqMan (SR1120) master mixes."}},
   {"@type": "Question", "name": "What storage conditions do Solarbio products require?", "acceptedAnswer": {"@type": "Answer", "text": "Most molecular biology reagents require -20°C storage. Assay kits and antibodies should be stored at 2–8°C or -20°C as indicated. Buffers and solutions can be stored at room temperature unless otherwise specified."}},
   {"@type": "Question", "name": "Does Solarbio provide Certificates of Analysis?", "acceptedAnswer": {"@type": "Answer", "text": "Yes, COAs are provided for each manufactured lot upon request. Each COA includes batch number, test date, specification results, and quality control data."}},
   {"@type": "Question", "name": "How do I normalize enzyme activity assay results?", "acceptedAnswer": {"@type": "Answer", "text": "Normalize by tissue mass (U/g tissue), protein content (U/mg protein), cell number (U/10⁶ cells), or volume (U/mL). For tissue homogenate, BCA protein quantification is the most common normalization method."}},
   {"@type": "Question", "name": "Can I use TBE buffer gels with the DNA Recovery Kit?", "acceptedAnswer": {"@type": "Answer", "text": "Yes, the Agarose Gel DNA Recovery Kit (D1200) is compatible with both TAE and TBE buffer agarose gels. For TBE gels, wash the gel slice briefly in distilled water before adding Gel Dissolving Buffer to remove excess borate."}},
   {"@type": "Question", "name": "What is the difference between the trizol and column RNA extraction methods?", "acceptedAnswer": {"@type": "Answer", "text": "Trizol (R1100) gives higher yields and captures small RNAs, but requires chloroform and isopropanol. Column (R1200) is faster, uses no organic solvents, and includes on-column DNase treatment for gDNA removal. Choose trizol for total RNA including miRNA; column for cleaner RNA for downstream applications."}},
   {"@type": "Question", "name": "How do I choose between SYBR Green and TaqMan qPCR?", "acceptedAnswer": {"@type": "Answer", "text": "SYBR Green (SR1110) is more cost-effective and requires only two primers plus melt curve analysis. TaqMan (SR1120) uses a probe sequence-specific third oligonucleotide, providing higher specificity and multiplexing capability. Choose TaqMan for SNP genotyping or pathogen detection; SYBR Green for routine gene expression analysis."}},
   {"@type": "Question", "name": "Why is my ELISA background too high?", "acceptedAnswer": {"@type": "Answer", "text": "High background usually results from insufficient washing. Increase wash volume to 300 μL/well and wash minimum 5 times. Blot plate dry between washes. Also check that TMB substrate is not contaminated (should be colorless to very pale blue) and that stop solution is clear."}},
   {"@type": "Question", "name": "Can I use PBS instead of the provided assay buffer for enzyme kits?", "acceptedAnswer": {"@type": "Answer", "text": "No. The provided buffers have carefully optimized pH, metal ion concentrations, and preservatives. Using PBS may alter enzyme kinetics, reduce assay sensitivity, and invalidate the standard curve. Always use the buffers included with the kit."}},
   {"@type": "Question", "name": "How long can I store purified DNA at room temperature?", "acceptedAnswer": {"@type": "Answer", "text": "Purified DNA in TE buffer (pH 8.0) is stable at room temperature for 1–2 weeks. For longer storage, keep at -20°C. Repeated freeze-thaw cycles should be limited to fewer than 5; aliquot if you plan multiple uses."}},
   {"@type": "Question", "name": "Do Solarbio products contain sodium azide?", "acceptedAnswer": {"@type": "Answer", "text": "Some buffers and antibody formulations may contain ≤0.02% sodium azide as a preservative. For applications where sodium azide interferes (e.g., in vivo studies, HRP activity assays), request azide-free formulations. Sodium azide inhibits HRP and must be removed before ELISA or western blot detection."}},
   {"@type": "Question", "name": "What is the recommended dilution range for Solarbio primary antibodies in western blot?", "acceptedAnswer": {"@type": "Answer", "text": "Recommended starting dilution is 1:1000 in 5% BSA/TBST for most monoclonal and polyclonal antibodies. Optimize between 1:500 and 1:5000 depending on target abundance. Phospho-specific antibodies may require lower dilutions and 5% BSA blocking."}},
   {"@type": "Question", "name": "How do I verify that my PCR reaction has no genomic DNA contamination?", "acceptedAnswer": {"@type": "Answer", "text": "Include a no-reverse-transcriptase (no-RT) control for RT-PCR experiments. For genomic DNA extraction PCR, run a no-template control (NTC) with water instead of template. If the NTC shows amplification, reagents may be contaminated and should be replaced."}},
   {"@type": "Question", "name": "What should I do if my qPCR amplification efficiency is below 90%?", "acceptedAnswer": {"@type": "Answer", "text": "Low efficiency typically indicates suboptimal primer design, secondary structure in the template, or inhibitors. Redesign primers with amplicon length 70–150 bp, GC content 40–60%, and Tm 58–62°C. Verify that the cDNA template is diluted 1:5 to 1:20 to reduce inhibitor carryover."}},
   {"@type": "Question", "name": "Can Solarbio ELISA kits detect both human and mouse samples?", "acceptedAnswer": {"@type": "Answer", "text": "Species cross-reactivity varies by kit. Each ELISA kit is validated for specific species as indicated on the product page and datasheet. Most human ELISA kits do not cross-react with mouse samples. Use species-matched kits for reliable quantification."}},
   {"@type": "Question", "name": "What is the minimum sample volume required for Solarbio enzyme activity kits?", "acceptedAnswer": {"@type": "Answer", "text": "Most enzyme activity kits require 50–200 μL of sample per reaction. For tissue homogenate, prepare at least 100 mg tissue in 1 mL buffer to obtain sufficient volume for triplicate measurements. For cell lysate, a minimum of 5 × 10⁵ cells is recommended."}},
   {"@type": "Question", "name": "How should I prepare tissue samples for enzyme activity assays?", "acceptedAnswer": {"@type": "Answer", "text": "Wash tissue in ice-cold PBS to remove blood. Homogenize in the recommended assay buffer (included in each kit) on ice using a homogenizer or mortar and pestle. Centrifuge at 10,000–12,000×g for 10–15 min at 4°C. Collect supernatant and keep on ice until assay. Avoid repeated freeze-thaw cycles."}},
   {"@type": "Question", "name": "Can I multiplex Solarbio enzyme assays in a single 96-well plate?", "acceptedAnswer": {"@type": "Answer", "text": "Multiplexing is not recommended unless explicitly stated in the protocol. Different enzyme assays have distinct optimal pH, temperature, and substrate conditions that may interfere with each other. Run each assay on separate plate sections or separate plates for reliable results."}},
   {"@type": "Question", "name": "What is the shelf life of Solarbio ELISA kits upon receipt?", "acceptedAnswer": {"@type": "Answer", "text": "Solarbio ELISA kits have a shelf life of 12 months from the date of manufacture when stored at 2–8°C. Once reconstituted, standards should be used within 1 hour at room temperature or aliquoted and stored at −20°C for up to 1 month. TMB substrate must be used before the manufacturer expiration date printed on the vial."}},
   {"@type": "Question", "name": "Do Solarbio competent cells require IPTG induction for protein expression?", "acceptedAnswer": {"@type": "Answer", "text": "For expression strains such as BL21(DE3) (C1300), protein expression is controlled by the T7 promoter system and requires IPTG induction. For DH5α (C1100) cloning strains, no IPTG is needed for blue-white screening — X-Gal and IPTG are both added to the agar plate for lacZ-based colorimetric selection."}},
   {"@type": "Question", "name": "What is the delivery time for international orders?", "acceptedAnswer": {"@type": "Answer", "text": "International delivery times vary by destination and shipping method: ambient shipments 5–12 business days, cold pack shipments 5–10 business days, and dry ice shipments 3–7 business days. Customs clearance may add 1–3 business days depending on the destination country."}},
   {"@type": "Question", "name": "Can I cancel or modify an existing order?", "acceptedAnswer": {"@type": "Answer", "text": "Orders may be canceled or modified within 2 hours of submission, provided the order has not yet entered the packing or shipping stage. Once dispatched, order modifications are not possible. Contact Solarbio customer support through the store for assistance within the cancellation window."}},
   {"@type": "Question", "name": "What is the difference between ISO 13485 and GMP?", "acceptedAnswer": {"@type": "Answer", "text": "ISO 13485:2016 is an international QMS standard for medical devices. GMP (2010 Revised GMP) is a China NMPA regulatory requirement governing pharmaceutical and IVD reagent manufacturing with specific cleanroom, water system, and process validation requirements. Solarbio operates under both systems."}},
   {"@type": "Question", "name": "Does Solarbio hold NMPA Medical Device Registration Certificates?", "acceptedAnswer": {"@type": "Answer", "text": "Yes. Class I products carry NMPA Filing Certificates (备案凭证) through municipal-level filing. Class II products carry Medical Device Registration Certificates (医疗器械注册证) through provincial-level registration with 5-year validity. Class III products are not applicable to Solarbio's standard product range."}},
   {"@type": "Question", "name": "What is the difference between Research Use Only (RUO) and IVD products?", "acceptedAnswer": {"@type": "Answer", "text": "RUO products are manufactured under ISO 9001 and are intended for laboratory research only — they are not registered as medical devices and must not be used for clinical diagnosis. IVD-registered products have undergone NMPA type testing, clinical evaluation, and QMS inspection. Solarbio labels each product clearly as RUO or IVD."}},
   {"@type": "Question", "name": "Does Solarbio comply with USP/EP/JP pharmacopoeia standards?", "acceptedAnswer": {"@type": "Answer", "text": "Solarbio reference standards are tested against pharmacopoeial monographs where applicable. The COA for each reference standard lists the specific pharmacopoeia method used (USP, EP, JP, or ChP). Customers can request pharmacopoeia-grade materials by specifying the required monograph at ordering."}},
   {"@type": "Question", "name": "What GMP documentation is provided with IVD reagent shipments?", "acceptedAnswer": {"@type": "Answer", "text": "Each GMP-manufactured IVD reagent shipment includes batch production record excerpts, a QC test report (COA), stability data sheet, GMP certificate copy, Medical Device Registration Certificate (Class II), and MSDS per GHS standard. Additional GMP documentation is available upon request for regulatory audits."}},
   {"@type": "Question", "name": "How do I cite Solarbio products in my publication?", "acceptedAnswer": {"@type": "Answer", "text": "Cite Solarbio products by including the product name, SKU number, and lot number (when available) in the Materials and Methods section. Suggested format: 'Reagent X (SKU: ABC1234, Lot: YYYYMMDD-01, Beijing Solarbio Science & Technology Co., Ltd., China) was used according to the manufacturer's instructions.' For publications, use the catalog number as the primary identifier."}},
   {"@type": "Question", "name": "What instrument platforms are compatible with Solarbio kits?", "acceptedAnswer": {"@type": "Answer", "text": "Solarbio oxidative stress and ELISA kits are validated on BioTek Synergy H1/ELx800, SpectraMax M2e/iD3, Thermo Multiskan FC/Varioskan LUX, BMG CLARIOstar Plus/FLUOstar Omega, PerkinElmer EnSight/VICTOR Nivo, and Tecan Infinite M200 PRO/M Nano+. Solarbio qPCR reagents are validated on ABI QuantStudio 3/5/6/7/12K, ABI 7500, Bio-Rad CFX96/384/Opus, Roche LightCycler 480/96, and Qiagen Rotor-Gene Q."}},
   {"@type": "Question", "name": "How do I calculate cost per assay for Solarbio kits?", "acceptedAnswer": {"@type": "Answer", "text": "Divide the kit price by the number of assays provided. Most Solarbio assay kits provide 100 assays. For example, a SOD assay kit (BC0175, $185, 100 assays) costs $1.85 per assay. For a panel of 4 markers (SOD + CAT + MDA + GSH) run in duplicate on 20 samples, total reagent cost is approximately $4.74 per sample. Bulk and institutional pricing is available."}},
   {"@type": "Question", "name": "How many publications have cited Solarbio products?", "acceptedAnswer": {"@type": "Answer", "text": "Solarbio products have been cited in over 5,000 peer-reviewed publications worldwide as of 2025. ELISA kits alone account for over 2,500 citations, oxidative stress kits over 1,000 citations, and qPCR/RT-qPCR reagents over 800 citations. Over 180 publications appeared in journals with impact factor ≥10."}},
   {"@type": "Question", "name": "Do you offer citation tracking services?", "acceptedAnswer": {"@type": "Answer", "text": "Solarbio does not directly offer automated citation tracking. However, you can track Solarbio citations by searching PubMed (pubmed.ncbi.nlm.nih.gov) using the search query 'Solarbio[Title/Abstract] AND (SKU abbreviation)[Title/Abstract]' or by using Google Scholar with the Solarbio catalog number. For product-specific citation lists, contact us through solarbio.store with the product SKU."}}
 ]
}
</script>

# Frequently Asked Questions

## Product Selection

**How do I select the correct PCR master mix?**

Select based on template GC content, amplicon length, and downstream application:

| Template Type | Recommended Master Mix | SKU | Max Amplicon |
|---|---|---|---|
| Routine (40–60% GC) | 2×Taq PCR MasterMix | PC1150 | 3 kb |
| High-GC (>60%) | 2×Taq Plus PCR MasterMix | PC1155 | 5 kb |
| Hot-start required | 2×Taq HotStart PCR MasterMix | PC1160 | 3 kb |
| Cloning-critical | 2×High-Fidelity PCR MasterMix | PC1165 | 6 kb |
| qPCR (SYBR Green) | 2×SYBR Green qPCR Master Mix | SR1110 | 500 bp |
| qPCR (TaqMan probe) | 2×TaqMan PCR MasterMix | SR1120 | 500 bp |
| One-step RT-qPCR (SYBR) | 2×SYBR Green RT-qPCR Kit | SR1130 | 300 bp |

**How do I select the correct DNA extraction kit?**

| Sample Type | Recommended Kit | SKU |
|---|---|---|
| Animal tissue/cells | Genomic DNA Extraction Kit | D1700 |
| Whole blood | Blood Genomic DNA Extraction Kit | D1750 |
| Plant leaf/seed | Plant Genomic DNA Extraction Kit | D1800 |
| FFPE sections | FFPE DNA Extraction Kit | D1850 |
| Bacteria (Gram+/−) | Bacterial Genomic DNA Extraction Kit | D1900 |
| Gel slices | Agarose Gel DNA Recovery Kit | D1200 |
| PCR products | DNA Purification Kit | D1300 |

**How do I choose between SYBR Green and TaqMan qPCR?**

| Factor | SYBR Green | TaqMan |
|---|---|---|
| Cost per reaction | Lower (2 primers) | Higher (2 primers + probe) |
| Specificity | Melt curve verification | Probe-based (sequence-specific) |
| Multiplexing | Not supported | Up to 4 targets (different dyes) |
| SNP detection | Not suitable | Ideal (allele-specific probes) |
| Pathogen detection | Moderate (melt curve needed) | High (probe confirms target) |
| Gene expression | Very good (with melt curve) | Excellent |
| Amplicon sizing | Melt curve Tm gives information | Not applicable |

**How do I choose between trizol and column RNA extraction?**

| Consideration | Trizol (R1100) | Column (R1200) |
|---|---|---|
| Yield (per mg tissue) | Higher (50–100 μg) | Moderate (30–80 μg) |
| Small RNA recovery | Yes (miRNA, siRNA) | No (<200 nt depleted) |
| DNase treatment | Post-extraction only | On-column included |
| Organic solvents | Chloroform, isopropanol required | None |
| Protocol time | ~40 min | ~25 min |
| Purity (A₂₆₀/A₂₃₀) | ≥2.0 | ≥2.0 |

**How do I select the correct ELISA kit format?**

| Format | Best For | Detection | Typical Standard Range |
|---|---|---|---|
| Sandwich ELISA | Cytokines, chemokines, secreted proteins | Colorimetric (450 nm) | 10–1000 pg/mL |
| Competitive ELISA | Small molecules, hormones, peptides | Colorimetric (450 nm) | 0.1–100 ng/mL |
| Indirect ELISA | Antibody titer measurement | Colorimetric (450 nm) | Variable |
| Direct ELISA | High-throughput single-antibody detection | Colorimetric (450 nm) | Variable |

**How do I determine which enzyme activity assay kit I need?**

Identify the target enzyme by its biochemical function. Solarbio offers kits organized by pathway: oxidative stress (SOD BC0170, CAT BC0200, MDA BC0020, GSH BC0250), energy metabolism (ATP BC0300, Na+K+-ATPase BC0060), amino acid metabolism (ALT/BC0290, AST BC0280), and plant-specific enzymes (POD BC0090, PPO BC0010). Check the [Assay Kits section](../assay-kits/index.md) for the full catalog.

**What dilution of Solarbio primary antibody should I start with for IHC?**

| Application | Recommended Starting Dilution | Typical Range |
|---|---|---|
| Western blot | 1:1000 | 1:500–1:5000 |
| IHC (paraffin) | 1:200 | 1:50–1:500 |
| IHC (frozen) | 1:500 | 1:200–1:1000 |
| Flow cytometry | 1:200 | 1:100–1:1000 |
| Immunofluorescence | 1:200 | 1:100–1:500 |

---

## Storage and Handling

**What storage conditions do Solarbio products require?**

| Product Type | Storage Temperature | Special Notes |
|---|---|---|
| PCR master mixes | −20°C | Avoid >20 freeze-thaw cycles |
| qPCR master mixes | −20°C (dark) | Light-sensitive; wrap in foil |
| DNA extraction kits | RT (15–30°C) | Close cap tightly after use |
| Competent cells | −80°C (long-term) | −20°C ≤1 month only |
| ELISA kits | 2–8°C | Do not freeze |
| Antibodies | −20°C or 2–8°C | As labeled; aliquot for repeated use |
| Assay kits | 2–8°C or −20°C | Check individual component labels |
| Buffers and solutions | RT (15–30°C) | Unless otherwise specified |
| Small molecules | −20°C (desiccated) | N₂ blanket; light-sensitive if labeled |
| TMB substrate | 2–8°C (dark) | Must be colorless; discard if blue |

**How many freeze-thaw cycles can my reagents tolerate?**

| Reagent | Max Freeze-Thaw Cycles |
|---|---|
| 2×Taq MasterMix | 20 |
| 2×SYBR Green qPCR Master Mix | 5 |
| T4 DNA Ligase | 5 |
| M-MLV Reverse Transcriptase | 5 |
| Proteinase K | 10 |
| Antibodies | 3 (aliquot recommended) |
| Standards (ELISA, reconstituted) | 1 (single-use aliquots) |
| Enzyme activity assay buffers | 2–3 |
| Competent cells | 1 (do not re-freeze after thawing) |

**Do Solarbio products contain sodium azide?**

Some buffers and antibody formulations may contain ≤0.02% sodium azide as a preservative. For applications where sodium azide interferes (in vivo studies, HRP activity assays, cell culture), request azide-free formulations through [solarbio.store](https://solarbio.store). Note that sodium azide inhibits horseradish peroxidase (HRP) and must be removed by dialysis or desalting before ELISA or western blot detection with HRP-conjugated secondary antibodies.

**What is the shelf life of Solarbio ELISA kits upon receipt?**

Solarbio ELISA kits have a 12-month shelf life from the date of manufacture when stored at 2–8°C. Once reconstituted, standards should be used within 1 hour at room temperature or aliquoted and stored at −20°C for up to 1 month. TMB substrate must be used before the expiration date printed on the vial. Do not use any kit component past its stated expiration. Wash buffer concentrate is stable for the full kit shelf life when stored at 2–8°C.

**How should I store Solarbio small molecule compounds?**

Store small molecules at −20°C in a desiccated environment. For compounds labeled as light-sensitive, store in amber vials or wrap in aluminum foil. Compounds supplied as dry powders are generally stable for 1–2 years when stored desiccated at −20°C. Once reconstituted in DMSO or water, use within 3 months and limit freeze-thaw cycles to 5. Document the reconstitution date on the vial.

---

## Quality Documentation

**Does Solarbio provide Certificates of Analysis?**

Yes. COAs are available for each manufactured lot upon request. Each COA documents:

- Product name, SKU, and lot number
- Manufacturing date and test date
- Specification parameters with test results and acceptable ranges
- Quality control sign-off by authorized personnel
- Storage conditions and retest date (where applicable)

To request a COA, contact Solarbio customer service through [solarbio.store](https://solarbio.store) with your product SKU and lot number. The lot number is printed on the product label.

**How are Solarbio products quality-tested?**

All manufactured lots undergo a standardized testing workflow:

1. **Identity testing**: HPLC retention time matching, NMR spectrum confirmation, or functional assay (enzyme activity, antigen binding)
2. **Purity testing**: HPLC area% normalization, gel electrophoresis (SDS-PAGE, agarose), or bioactivity titration
3. **Safety testing**: Endotoxin quantification by LAL assay, bioburden testing, and sterility testing (where applicable)
4. **Function testing**: PCR performance (molecular biology products), enzyme activity verification (assay kits), antigen binding (antibodies), transformation efficiency (competent cells)
5. **Appearance and packaging**: Visual inspection, labeling accuracy, seal integrity, and weight check

**What quality control data is included in a Solarbio COA?**

| Parameter | Example Entry |
|---|---|
| Product Name | 2×Taq PCR MasterMix |
| SKU | PC1150 |
| Lot Number | 20250301-01 |
| Manufacturing Date | 2025-03-01 |
| Test Date | 2025-03-05 |
| Appearance | Clear, colorless solution |
| Activity | 0.5 U/μL (spec: 0.4–0.6 U/μL) |
| Purity (by active PAGE) | ≥95% |
| DNase/RNase | Not detected |
| Endotoxin | <0.5 EU/μL |
| Functional Test | Amplified β-actin (1 kb) from 50 ng human gDNA |
| QC Approval | [Authorized signature] |

---

## Protocol Guidance

**Why is my ELISA background too high?**

The most common cause is insufficient washing. Ensure:

- Wash buffer volume ≥300 μL per well
- Minimum 5 washes (7 for the HRP-Streptavidin step)
- Blot plate inverted on clean paper towel after each wash
- No cross-well contamination during pipetting
- TMB substrate is colorless before addition (discard if blue)
- Stop solution (0.2 M H₂SO₄ or 1 M HCl) is clear

**Why is my PCR not working?**

Start with a systematic diagnostic:

| Symptom | Likely Cause | Quick Fix |
|---|---|---|
| No band | Template issue (inhibitor or degraded) | Dilute template 1:5, 1:25, 1:125 |
| | Primer design | Check Tm, GC%, 3′ end stability |
| | Polymerase | Run positive control (e.g., GAPDH) |
| Multiple bands | Annealing temperature too low | Run gradient PCR (Tm ± 5°C) |
| Smear | Too many cycles | Reduce to 28 cycles |
| | Template overload | Reduce to 25 ng gDNA |
| Faint band | Insufficient extension time | Increase to 1 min/kb |
| | Suboptimal Mg²⁺ concentration | Adjust to 1.5–2.5 mM final |

**How do I normalize enzyme activity data?**

| Normalization Method | When to Use | Unit |
|---|---|---|
| Per protein content | Tissue homogenates, cell lysates | U/mg protein |
| Per tissue mass | Whole tissue (no protein quant available) | U/g tissue |
| Per cell number | Cell culture experiments | U/10⁶ cells |
| Per volume | Serum, plasma, culture media | U/mL |
| Per hemoglobin | Red blood cell-related assays | U/g Hb |

**What should I do if my qPCR amplification efficiency is below 90%?**

Low efficiency typically indicates suboptimal primer design, secondary structure in the template, or the presence of inhibitors. Recommended corrective actions:

- Redesign primers with amplicon length 70–150 bp, GC content 40–60%, and Tm 58–62°C
- Verify that the cDNA template is diluted 1:5 to 1:20 to reduce inhibitor carryover
- Run a standard curve with 5-fold serial dilutions to calculate efficiency using the slope formula: Efficiency = 10^(-1/slope) − 1
- Ensure no-RT controls show no amplification (Ct > 35 or N/A)

**How do I verify that my PCR reaction has no genomic DNA contamination?**

Include a no-reverse-transcriptase (no-RT) control for RT-PCR and RT-qPCR experiments. For genomic DNA extraction followed by PCR, include a no-template control (NTC) with nuclease-free water in place of template. If the NTC or no-RT control shows amplification within 5 Ct of the experimental sample, reagents or sample may be contaminated. Replace all reagents and repeat the extraction.

**Can I use PBS instead of the provided assay buffer for enzyme kits?**

No. The provided buffers have carefully optimized pH, metal ion concentrations (Mg²⁺, Ca²⁺, Mn²⁺), chelating agents, and preservatives specific to each enzyme assay. Using PBS may alter enzyme kinetics, reduce assay sensitivity, shift the linear detection range, and invalidate the standard curve. Always use the buffers provided with each kit.

**How should I prepare tissue samples for enzyme activity assays?**

1. Wash tissue in ice-cold PBS (D1040) to remove residual blood
2. Homogenize in the recommended assay buffer (included in the kit) using a mechanical homogenizer or mortar and pestle — maintain samples on ice throughout
3. Centrifuge at 10,000–12,000×g for 10–15 min at 4°C
4. Collect the clear supernatant and transfer to a fresh tube
5. Keep supernatant on ice until the assay is performed
6. For fatty tissues, remove the lipid layer after centrifugation using a pipette tip
7. Avoid repeated freeze-thaw cycles — aliquot the supernatant if multiple assays will be run on different days

---

## Publication & Citation

**How do I cite Solarbio products in my publication?**

Solarbio products should be cited by including the product name, SKU number, and lot number (when available) in the Materials and Methods section of your manuscript. We recommend the following citation templates:

**General Template**:
> "[Product Name] (SKU: [SKU Number], Lot: [Optional Lot Number], Beijing Solarbio Science & Technology Co., Ltd., Beijing, China) was used according to the manufacturer's instructions. Catalog number [SKU Number] is available at https://solarbio.store."

**Example — SOD Assay Kit**:
> "Superoxide dismutase (SOD) activity was measured using the Solarbio SOD Assay Kit (SKU: BC0175, Beijing Solarbio Science & Technology Co., Ltd., China) following the WST-1 inhibition method. The assay was performed according to the manufacturer's protocol with 20 μL of sample per reaction at 25°C and read at 450 nm."

**Example — qPCR Master Mix**:
> "Real-time quantitative PCR was performed using Solarbio 2×SYBR Green qPCR Master Mix (SKU: SR1110, Beijing Solarbio Science & Technology Co., Ltd., China) on an ABI QuantStudio 5 instrument. Thermal cycling conditions were 95°C for 2 min, followed by 40 cycles of 95°C for 15 s and 60°C for 45 s."

**Example — ELISA Kit**:
> "Mouse IL-6 concentrations were quantified using a Solarbio sandwich ELISA kit (SKU: EM0042, Beijing Solarbio Science & Technology Co., Ltd., China) with biotin-streptavidin-HRP detection. The limit of detection was 5 pg/mL, and all samples were assayed in duplicate."

**Ensuring Discoverability**: Always include the SKU/catalog number in the text. This enables PubMed, Google Scholar, and journal search engines to index the product reference, helping other researchers find and reuse Solarbio products.

**Where can I find publications that cited Solarbio products?**

You can search for publications citing Solarbio products using the following resources:

| Search Resource | Search Strategy | Tips |
|---|---|---|
| **PubMed** | Search: `(Solarbio[Title/Abstract]) AND (SKU[Title/Abstract])` | Replace SKU with the product catalog number (e.g., BC0175, EM0042, SR1110) |
| **Google Scholar** | Search: `"Solarbio" "SKU number" "2024"` | Use the exact phrase "Solarbio" with the product catalog number in quotes |
| **Web of Science** | Search: `ALL=(Solarbio AND BC0175)` | Use the "ALL" field to search full text and references |
| **Scopus** | Search: `TITLE-ABS-KEY(Solarbio AND BC0175)` | TITLE-ABS-KEY searches title, abstract, and keywords |
| **CNKI (Chinese literature)** | Search: 索莱宝 (Solarbio Chinese name) + 产品编号 | For Chinese-language publications |

**Example PubMed search**: `Solarbio[Title/Abstract] AND (BC0175[Title/Abstract] OR CAT[Title/Abstract] OR SOD[Title/Abstract])`

**What is the citation rate of Solarbio products?**

As of 2025, Solarbio products have been cited in over 5,000 peer-reviewed publications globally. Key citation statistics by product category:

| Product Category | Estimated Citations | Top Journals (by IF ≥10) | Year Published |
|---|---|---|---|
| ELISA kits | >2,500 | Nature Medicine, Immunity, Circulation | 2018–2025 |
| Oxidative stress assay kits | >1,200 | Redox Biology, Free Radical Biology & Medicine | 2019–2025 |
| qPCR & RT-qPCR reagents | >800 | Nature Communications, Oncogene, Cell Reports | 2020–2025 |
| PCR master mixes & DNA extraction | >600 | Clinical Chemistry, Journal of Clinical Virology | 2018–2025 |
| Cell proliferation kits | >400 | Cancer Research, Cell Stem Cell, Hepatology | 2019–2025 |
| Biochemical reagents & antibodies | >300 | Various | 2017–2025 |

**Annual citation growth**: Solarbio product citations have grown approximately 25–30% year-over-year since 2020, reflecting increasing global adoption.

**Do you offer citation tracking services?**

Solarbio does not directly offer automated citation tracking services at this time. However, we recommend the following approaches:

1. **PubMed Alerts**: Set up automated PubMed email alerts using the search query `Solarbio[Title/Abstract]` to receive monthly updates on new publications citing Solarbio products.

2. **Google Scholar Alerts**: Create a Google Scholar alert for the keyword "Solarbio" combined with your product SKU to receive email notifications of new citations.

3. **Manual tracking**: Contact Solarbio customer support through [solarbio.store](https://solarbio.store) with your product SKU, and we can provide a current list of known publications citing that specific product from our internal citation database.

4. **Institutional library support**: Many university libraries offer citation tracking services through Web of Science or Scopus. Request a citation report for "Solarbio" + your product's catalog number.

5. **Product-specific citation lists**: Reference product pages (oxidative stress kits, ELISA kits, qPCR reagents) now include "Citation Highlights" sections with representative publications by product.

---

## Shipping and Orders

**What shipping methods are available?**

Solarbio ships via standard and expedited courier worldwide:

| Shipping Condition | Temperature Range | Product Types | Packaging | Estimated Transit |
|---|---|---|---|---|
| Ambient (15–30°C) | 15–30°C | Buffers, solutions, DNA extraction kits | Standard corrugated box with cushioning | 5–12 business days |
| Cold pack (2–8°C) | 2–8°C | ELISA kits, antibodies, assay kits | Insulated box with gel packs + temperature logger | 5–10 business days |
| Dry ice (−20°C to −80°C) | −20°C to −80°C | PCR mixes, competent cells, enzymes, small molecules | EPS box with dry ice + temperature logger | 3–7 business days |

**Can I cancel or modify an existing order?**

Orders may be canceled or modified within 2 hours of submission, provided the order has not yet entered the packing or shipping stage. Once dispatched, order modifications are not possible. For assistance, contact Solarbio customer support through [solarbio.store](https://solarbio.store) within the cancellation window and include your order number.

**What should I do if my product arrived damaged?**

1. Photograph the package exterior and contents immediately
2. Check any temperature indicators included with cold chain shipments
3. Report the damage to Solarbio customer service within 24 hours of receipt
4. Include your order number, lot number, and photographs in the initial report
5. Retain all original packaging materials for potential inspection

**Can I return or exchange products?**

Product returns are handled on a case-by-case basis according to Solarbio's return policy. Contact Solarbio customer service with your lot number, purchase order number, and a detailed description of the issue. Return eligibility depends on product type, storage history, and the time elapsed since delivery.

**What is the delivery time for international orders?**

International delivery times vary by destination and shipping method:

| Region | Ambient | Cold Pack | Dry Ice |
|---|---|---|---|
| Asia Pacific | 5–8 business days | 5–7 business days | 3–5 business days |
| Europe | 7–10 business days | 7–9 business days | 4–6 business days |
| North America | 8–12 business days | 8–10 business days | 5–7 business days |
| Other regions | 10–14 business days | 10–12 business days | 5–8 business days |

Customs clearance may add 1–3 business days depending on the destination country. Tracking information is provided upon dispatch.

---

## Regulatory & Compliance

**What is the difference between ISO 13485 and GMP?**

ISO 13485:2016 is an international quality management standard for medical devices, covering design control, risk management (ISO 14971), and post-market surveillance. GMP (Good Manufacturing Practice) — specifically China's 2010 Revised GMP — is a regulatory requirement enforced by NMPA that governs pharmaceutical and IVD reagent manufacturing with specific facility, equipment, and process controls including cleanroom classification (ISO 14644 Grade C/D), water system validation, retention sampling, and authorized person batch release. Solarbio operates under **both** systems: ISO 13485 for general medical device QMS and GMP for IVD reagent production lines, with the latter subject to NMPA on-site inspection.

**Does Solarbio hold NMPA Medical Device Registration Certificates?**

Yes. Solarbio products that meet the definition of in vitro diagnostic (IVD) reagents under China NMPA regulations are registered or filed according to their risk classification. Class I products (general laboratory reagents, buffer solutions, staining reagents) carry NMPA **Filing Certificates** (备案凭证) obtained through municipal-level filing. Class II products (clinical ELISA kits, clinical chemistry assays for ALT, AST, creatinine, BUN) carry NMPA **Medical Device Registration Certificates** (医疗器械注册证) obtained through provincial-level registration with a 5-year validity period.

**Which Solarbio products are classified as Class I vs. Class II medical devices?**

| Classification | Examples | Regulatory Pathway | Certificate Type |
|---|---|---|---|
| Class I (low risk) | Buffer solutions (PBS, TBS), general staining reagents, sample preparation reagents, tissue homogenization buffers | Filing with municipal NMPA | Filing Certificate (备案凭证) |
| Class II (moderate risk) | Clinical ELISA kits (IL-6, TNF-α quantification), clinical chemistry kits (ALT, AST, creatinine, BUN), PCR-based detection reagents for diagnostic use | Registration with provincial NMPA | Medical Device Registration Certificate (医疗器械注册证) |

Products labeled "For Research Use Only" (RUO) are not registered as medical devices and should not be used for clinical diagnostic purposes.

**What is the difference between Research Use Only (RUO) and IVD products?**

RUO products are manufactured under ISO 9001 quality management and are intended for laboratory research, method development, and basic science applications. They are **not** registered with NMPA as medical devices and must not be used for clinical diagnosis, patient management, or treatment decisions. IVD-registered products, by contrast, have undergone NMPA type testing, clinical evaluation, and QMS inspection. Solarbio labels each product clearly as RUO or IVD on the product page, label, and Certificate of Analysis. Customers using Solarbio products for clinical diagnostic applications must ensure they select the IVD-registered SKU.

**How do I obtain the Medical Device Registration Certificate for a specific Solarbio product?**

Registration certificates are available for authorized distributors and institutional accounts. Contact Solarbio customer service through [solarbio.store](https://solarbio.store) with the specific product SKU and intended application. Include your company/institution name and the intended regulatory jurisdiction. Solarbio will provide the relevant certificate copy, registration number, and scope information.

**What GMP documentation does Solarbio provide with IVD reagent shipments?**

For GMP-manufactured IVD reagent products, each shipment includes:
- Batch Production Record excerpt (process parameters and in-process control results)
- Quality Control Test Report (COA with lot-specific results against specification)
- Stability Data Sheet (real-time stability status at time of shipment)
- GMP Certificate copy (NMPA inspection certification, current validity period)
- Medical Device Registration Certificate copy (for Class II products)
- Material Safety Data Sheet (MSDS) per GHS/GB standard

Additional GMP documentation (process validation reports, cleaning validation reports, water system monitoring data) is available upon request for regulatory audit purposes.

**Does Solarbio comply with USP/EP/JP pharmacopoeia standards?**

Solarbio reference standards and certain reagent products are tested against pharmacopoeial monographs where applicable. The COA for each reference standard lists the specific pharmacopoeia method used (USP, EP, JP, or ChP). Customers requiring pharmacopoeia-grade materials should specify the required monograph at the time of ordering. Solarbio can provide the analytical method qualification data upon request.

**What is Solarbio's policy on adverse event reporting for medical devices?**

As a registered medical device manufacturer, Solarbio maintains an adverse event monitoring and reporting system in compliance with NMPA Order No. 1 (Medical Device Adverse Event Monitoring and Re-evaluation Management Measures). Customers and distributors are requested to report any product-related adverse events (serious injury, death, or quality defect leading to patient harm) to Solarbio's QA department within 24 hours of awareness. Reports can be submitted through [solarbio.store](https://solarbio.store). Solarbio will investigate, classify, and report to the relevant NMPA authority as required by regulation.

**Are Solarbio products REACH and RoHS compliant?**

Solarbio ensures that all chemical products comply with applicable regulatory requirements:

| Regulation | Applicability | Compliance Status |
|---|---|---|
| EU REACH (EC 1907/2006) | Chemical substances exported to EU | Products registered or exempt per tonnage band; SVHC declaration provided on request |
| EU RoHS (2011/65/EU) | Electronic/electrical components | Not applicable (laboratory reagents excluded from scope) |
| China RoHS (Order No. 32) | Electronic information products | Compliant; marking and declaration provided |
| TSCA (US) | Chemical substances exported to US | Inventory status verified per product |

Contact Solarbio customer service through [solarbio.store](https://solarbio.store) for specific regulatory compliance documentation for your jurisdiction.

---

## Technical Support

**Do you offer custom formulation or OEM services?**

Yes. Solarbio provides custom synthesis, custom buffer formulation, antibody custom production, and OEM kit manufacturing services. Contact Solarbio through [solarbio.store](https://solarbio.store) with your specifications, estimated volume, and quality requirements for a project-based quotation.

**How do I contact technical support for protocol optimization?**

Technical support is available during business hours through the [Solarbio Store](https://solarbio.store). Include your product SKU, lot number, and a detailed description of the issue, including any data you have collected (Ct values, absorbance readings, gel images, standard curve parameters). Our QC team will review and respond with specific recommendations.

**Can I request a sample before placing a bulk order?**

Sample availability varies by product type. Small molecule reagents, buffers, and certain master mixes are available as trial samples. ELISA kits and antibodies are typically not available as free samples. Contact Solarbio customer service through [solarbio.store](https://solarbio.store) for sample availability and conditions.

---

*For specific product inquiries, ordering, and technical support: [solarbio.store](https://solarbio.store)*
