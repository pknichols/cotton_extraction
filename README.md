# Laboratory Protocol: eDNA Preservations & Extraction from Whole Cotton Membranes

**Version:** 1.0  
**Effective Date:** 2026/09  
**Author:** Dr. Patrick Nichols
**Lab Group:** Biodiversity Genomics Group

---

## 1.0 Purpose and Scope

This protocol describes the standardized procedure for preparing the room-temperature storage/lysis buffer and subsequent extraction of **eDNA** from **simple cotton membranes** for downstream applications such as qPCR and/or metabarcoding.

- **Sample Type:** ~50 mm cotton membrane
- **Extraction Method:** Salting out, ethanol precipitation, silica spin columns
- **Expected Yield:** 10–50 ng/µL
- **Storage After Extraction:** -20°C for short-term; -80°C for long-term

---

## 2.0 Pre-Operational Checklist

Before starting, complete the following checklist:

- [ ] Workstation prepared: Bench cleared, decontaminated (e.g., 10% bleach and 70% EtOH) ready.
- [ ] Personal Protective Equipment (PPE): Lab coat, gloves, and/or safety glasses are on.
- [ ] Reagents are thawed: Check expiration dates and aliquot sizes.
- [ ] Centrifuges on and pre-cooled to correct temperature (4°C)
- [ ] Heat blocks are pre-heated to the correct temperatures (55°C, 70°C).
- [ ] Sample tracking sheet is ready to record yields and storage positions.
- [ ] Waste disposal containers are available for liquid waste.

---

## 3.0 Equipment and Reagents

### 3.1 General Equipment/Consumables

- Freezer storage (-20°C or -80°C)
- Forceps
- Micropipettes (P20, P200, P1000) with filter tips
- Refrigerated centrifuge (6000 x g) capable of 15 mL falcon tubes and 2 mL micro-centrifuge tubes
- Vortex mixer
- Incubator and/or heat blocks (15 mL conical tube- and 2 mL microcentrifuge tube-capable)
- Nanodrop / Qubit for quantification
- 1.5 mL or 2.0 mL microcentrifuge tubes
- 50 mL conical tubes
- 15 mL conical tubes
- Spin columns & collection tubes
- Pipette tips (sterile, filter)
- 10% bleach decontamination bath (for forceps)
  
### 3.2 eDNA Storage/Lysis Buffer Stock Reagents

The 2x-concentrated **stock storage/lysis buffer** can be prepared in 50 mL falcon tubes, to be distributed into 15-mL (or 5-mL, if available) conical sample tubes (one per membrane).

| **Reagent** | **Concentration** | **Volume (mL)** |
| :--- | :--- | :--- |
| dH₂O |  | 18 mL |
| NaCl | 1 M | 10 mL |
| Tris-HCl | 1 M (pH 8) | 10 mL |
| Ethylenediaminetetraacetic acid (EDTA) | 0.5 M (pH 8) | 2 mL |
| Sodium Dodecyl Sulfate (SDS) | 10% | 10 mL |
| *Total* | *2x* | *50 mL* |

> **Note:** SDS can be omitted if samples will be immediately frozen at -20°C or -80°C, simplifying the extraction without a need for salting out (see Section 4.3 below).

---

## 4.0 Extraction Protocol

> ⚠️ **Important:** Extractions should be performed in a designated pre-PCR clean area and/or under a fume hood.

| **Reagent/Kit** | **Concentration** | **Storage** |
| :--- | :--- | :--- |
| Positive Control DNA | 1-10 ng/µL | -20°C |
| Proteinase K |  | -20°C |
| NaCl | 10 M | RT |
| Ethanol | 96-100% | -20°C |
| Ethanol | 70% | -20°C |
| Spin Column Extraction Kit, e.g., Qiagen DNeasy Blood & Tissue Kit or similar | Cat# 69504 | RT |

> **Note:** For semi-quantitative metabarcoding of eDNA, positive control DNA should be spiked into each sample to track extraction/amplification/sequencing efficiency. Therefore control DNA should either be synthetic or derived from a target organism that does not occur in the study area but is unlikely to differ at the primer-binding sites (e.g., _Panthera tigris_ when targeting Arctic mammals). The exact concentration spiked into each sample should be carefully noted. This step can be omitted, however, resulting read abundances should be interpreted with extreme caution and should not be considered semi-quantitative.

### 4.1 Sample Preparation

1. Vortex **stock eDNA storage/lysis buffer** briefly.
2. Distribute **2.0 - 2.5 mL storage/lysis buffer** to each conical sample tube.
3. Spike in **1 µL positive control DNA** to each sample tube.
4. Roll eDNA cotton membrane samples and place into sample tubes, ensuring entire membrane is submerged.
5. Shake vigorously and store at *< 25°C* up to two weeks.
6. Record sample metadata (ID, date, site, coordinates, filtration volume, deployment duration, etc.).

---

### 4.2 Lysis and Digestion

> ⚠️ **Before starting:** Thaw Proteinase K on ice. Ensure incubator is set to *55°C*.

1. Add **100 - 200 µL Proteinase K** to each sample tube.
2. Vortex briefly.
3. Incubate at *55°C* overnight.
4. Vortex briefly
5. Centrifuge at 6000 x g for 5 minutes
6. Transfer up to 5 mL to new, labeled **15 mL conical tubes**, avoiding the precipitated debris pellet.

---

### 4.3 Salting Out

Salting out is required to not co-precipitate SDS in the following steps.

> **Note:** This section is not necessary if omitting SDS from the **storage/lysis buffer**. Continue to Section 4.4.

1. Add **1 mL NaCl (10M)** to each sample tube.
2. Vortex briefly.
3. Centrifuge at 6000 x g for 15 - 20 minutes.
4. Carefully transfer the supernatant to new, labeled **15 mL conical tubes**.

---

### 4.4 Ethanol Precipitation

> ⚠️ **Before starting:** Cool 96 - 100% ethanol to *-20°C*.

1. Add 2 - 2.5 volumes **(10 - 12.5 mL) ice-cold 96 - 100% ethanol**.
2. Vortex briefly.
3. Incubate at *-20°C* overnight.

> ⚠️ **Before starting:** Begin pre-cooling of centrifuge (*4°C*). Cool 70% ethanol to *-20°C*.

5. Centrifuge at 6000 x g and *4°C* for 30 minutes.
6. Discard the supernatant, being careful not to disturb the pellet.
7. Add **1 mL ice-cold 70% ethanol** and wash by inverting several times.
8. Decant the ethanol and air dry the pellet (5 - 10 minutes, using a P20 pipette for any remaining).
9. Add **200 µL kit lysis buffer** (provided with the column extraction kit; e.g., BL Buffer, ATL Buffer, or similar).

---

### 4.5 Column Extraction

Proceed with the extraction protocol as described by the manufacturer. Below is the modified extraction using the OMEGA E.Z.N.A. Extraction kits:

> ⚠️ **Before starting:** Set heat block to *55°C*. Set second heat block to *70°C* and begin warming aliquots of Elution Buffer. Cool 96 - 100% ethanol to *-20°C*.

1. Add **200 µL of kit lysis buffer (Buffer BL)**.
2. Incubate for 1 hour at *55°C*.
3. Add **200 µL ice-cold ethanol (96-100%)** to the mixture.
4. Vortex thoroughly.
5. Transfer the entire mixture to a **labeled spin column** placed in a collection tube.
6. Centrifuge at 6,000 x g for 1 minute.
7. Discard the flow-through and collection tube.
8. Place the column into a **new collection tube**.
9. Add **500 µL of Wash Buffer 1 (AW1)** to the column.
10. Centrifuge at 6,000 x g for 1 minute.
11. Discard flow-through and collection tube.
12. Place the column into a new collection tube.
13. Add **500 µL of Wash Buffer 2 (AW2)** to the column.
14. Centrifuge at maximum speed for 3 minutes to dry the membrane.

> ⚠️ **Critical Step:** This ensures no residual ethanol contaminates the final eluate.

14. Discard flow-through and collection tube.
15. Place the column into a new, **labeled 1.5 mL microcentrifuge tube**.
16. Add **50 µL of Elution Buffer (Buffer AE)** heated to *70°C* directly to the center of the membrane.
17. Incubate at room temperature for 2 minutes.
18. Centrifuge at 6,000 x g for 1 minute to collect DNA eluate.
19. Optional: Re-elute by repeating steps 16 - 18 to increase yield.

---

## 5.0 Quality Control and Quantification

| **Parameter** | **Method** | **Acceptable Range** | **Action if Out of Range** |
| :--- | :--- | :--- | :--- |
| **Concentration** | Nanodrop (A260) / Qubit | ≥ 1 ng/µL | Re-extract or concentrate. |
| **Purity (DNA)** | A260/A280 ratio | 1.8 – 2.0 | Protein contamination. Increase Prot-K and digestion. |
| **Purity (DNA)** | A260/A230 ratio | 2.0 – 2.2 | Salts/ethanol contamination. Dry pellet and/or column longer. |

---

## 6.0 Cleanup and Documentation

1. Dispose of all hazardous waste in designated waste containers.
2. Clean the workspace with 10% bleach followed by 70% ethanol.
3. Return reagents to their proper storage temperatures.
4. Record all steps, deviations, and results in the lab notebook or electronic system.
5. Store the extracted nucleic acids at **-20°C** (if proceeding to PCR) or **-80°C** (for longer-term storage).

---

## 7.0 Troubleshooting

| **Problem** | **Possible Cause** | **Solution** |
| :--- | :--- | :--- |
| Low yield | Lysis incomplete | Increase Proteinase K digestion time or temperature. |
| Low yield | Inefficient elution | Incubate elution buffer on membrane longer. Re-elute. |
| Low A260/280 | Protein contamination | Increase Proteinase K digestion. |
| Low A260/230 | Salt/EtOH contamination | Add an extra wash step or dry column longer. |
| Column clogged | Sample too large | Reduce sample input. |

---

**For internal use only.**  
**Biodiversity Genomics Group**  
Ecology and Genetics Research Unit  
University of Oulu, Finland  
https://biodiversitygenomics.org/
