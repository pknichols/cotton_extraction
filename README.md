# Laboratory Protocol: eDNA Preservation & Extraction from Water Samples on Cotton Membranes

**Version:** 1.0  
**Effective Date:** 2026/09  
**Author:** Dr. Patrick Nichols  
**Last Modified:** 2026/09/07

---

## 1.0 Purpose and Scope

This protocol describes a **simple, efficient, and cost-effective** method for preserving and extracting environmental DNA (eDNA) from **cotton membrane filters** collected from **aquatic environments**.

- **Sample Type:** ~50 mm cotton membrane with ~2 mL retained water
- **Extraction Method:** Salting out, ethanol precipitation, silica spin columns
- **Expected Yield:** 10–50 ng/µL (Qubit-confirmed)
- **Total Time:** ~24 hours
- **Storage After Extraction:** -20°C for short-term; -80°C for long-term

---

## 2.0 Pre-Operational Checklist

Before starting, complete the following checklist:

- [ ] Workstation prepared: Bench cleared, decontaminated with 10% bleach followed by 70% EtOH
- [ ] Personal Protective Equipment (PPE): Lab coat, gloves, and safety glasses
- [ ] Reagents checked: Expiration dates and aliquots prepared
- [ ] Centrifuge pre-cooled to 4°C
- [ ] Heat blocks pre-heated to 55°C and 70°C
- [ ] Sample tracking sheet ready for metadata and yields
- [ ] Waste disposal containers available
- [ ] Negative extraction control tube prepared (empty tube processed alongside samples)

---

## 3.0 Equipment and Reagents

### 3.1 Equipment & Consumables

| **Item** | **Specification** |
| :--- | :--- |
| Freezer | -20°C and -80°C storage |
| Forceps | Sterile, single-use OR decontaminated with DNA-ExitusPlus |
| Micropipettes | P20, P200, P1000 with filter tips |
| Centrifuge | Capable of 6,000 xg with 15 mL and 2 mL rotors |
| Vortex mixer | Standard |
| Heat blocks | 55°C and 70°C |
| Nanodrop / Qubit | For quantification |
| Microcentrifuge tubes | 1.5 mL or 2.0 mL |
| Conical tubes | 50 mL, 15 mL, and 5 mL |
| Spin columns | OMEGA E.Z.N.A. or equivalent silica column kit |
| Pipette tips | Sterile, filter |

### 3.2 Storage/Lysis Buffer (2× Concentrated)

Prepare in a 50 mL falcon tube. Store at room temperature (15-25°C), protected from light.

| **Reagent** | **Stock Concentration** | **Volume (mL)** | **Final 2× Concentration** |
| :--- | :--- | :--- | :--- |
| dH₂O |  | 18 mL |  |
| NaCl | 5 M | 4 mL | 0.4 M |
| Tris-HCl | 1 M (pH 8.0) | 10 mL | 0.2 M |
| EDTA | 0.5 M (pH 8.0) | 2 mL | 0.02 M |
| SDS | 10% w/v | 10 mL | 2% |
| *Total* | *2×* | *44 mL* |  |

**Note:** When mixed 1:1 with ~2 mL water (final volume ~4.5 mL in 5 mL tube), final concentrations are:
- Tris-HCl: 100 mM
- EDTA: 10 mM
- SDS: 1%
- NaCl: ~100 mM (plus additional from salting-out step)

**Storage:** Room temperature, protected from light. If precipitates form, warm to 37°C with gentle mixing until dissolved. Discard if buffer is >6 months old or precipitates don't fully dissolve.

### 3.3 Additional Reagents

| **Reagent** | **Concentration** | **Storage** |
| :--- | :--- | :--- |
| Proteinase K | 20 mg/mL | -20°C |
| NaCl | 5 M | Room temperature |
| Ethanol | 96-100% | -20°C |
| Ethanol | 70% | Room temperature or -20°C |
| Spin Column Kit | OMEGA E.Z.N.A. or equivalent | Room temperature |

---

## 4.0 Extraction Protocol

### 4.1 Sample Preservation

1. **Prepare 5 mL tubes:** Add **2.5 mL of 2× Storage/Lysis Buffer** to each labeled 5 mL tube.
2. **Add sample:** Place the cotton membrane (with ~2 mL retained water) into the tube.
   - Ensure the membrane is **fully submerged**.
   - If it floats, gently push down with a sterile pipette tip or forceps.
3. **Mix:** Cap tightly and vortex briefly (5 seconds) or shake vigorously.
4. **Store:** Keep at **room temperature** for up to 2 weeks before extraction.
5. **Record metadata:** Sample ID, date, site, coordinates, membrane deployment duration, etc.

---

> ⚠️ **Important:** Perform all steps in a designated pre-PCR clean area when possible.

> ⚠️ **Before starting:** Thaw Proteinase K on ice. Ensure heat block/incubator is at 55°C.

### 4.2 Lysis & Digestion (Day 1)

1. **Add Proteinase K:** Add **100 µL Proteinase K (20 mg/mL)** directly to the 5 mL tube.
2. **Mix:** Vortex briefly (5-10 seconds) to mix thoroughly.
3. **Incubate:** Place at **55°C overnight** (12-16 hours).
   - If time is limited or using a fraction of the filter membrane, 2-3 hours with shaking (400 rpm) is sufficient.

---

### 4.3 Salting-Out (Day 2)

> ⚠️ **Before starting:** Prepare clean, labeled 15 mL tubes. Pre-cool centrifuge to 4°C.

1. **Vortex:** Briefly vortex the 5 mL tube after overnight digestion.
2. **Transfer:** Transfer up to 4 mL to new, labeled 5 mL conical tubes.
3. **Add NaCl:** Add **1 mL of 5 M NaCl** to the 5 mL tube.
   - Final NaCl concentration: ~1 M
4. **Mix:** Cap tightly and vortex briefly (5 seconds).
5. **Centrifuge:** Spin at **6,000 xg** for **15 minutes** at room temperature.
6. **Transfer supernatant:** Carefully pipette the supernatant into a new, labeled **15 mL tube**.
   - **CRITICAL:** Leave behind the last 100-500 µL to avoid the protein/SDS pellet.
   - Expected volume: ~4-5 mL

---

### 4.4 Ethanol Precipitation (Day 2)

> ⚠️ **Before starting:** Cool 100% ethanol to -20°C. 

1. **Add ethanol:** Add **1 volume of ice-cold 100% ethanol** to the 15 mL tube.
   - Example: If you transferred 3.5 mL, add 3.5 mL ethanol.
2. **Mix:** Cap and invert 10-15 times (or vortex briefly for 5 seconds).
3. **Incubate:** Place at **-20°C overnight**.
   - If time is limited, 2-3 hours may be sufficient.

---

### 4.5 Pellet Recovery (Day 3)

> ⚠️ **Before starting:** Pre-cool centrifuge to 4°C. Cool 70% ethanol to -20°C. Heat block to 55°C.

1. **Centrifuge:** Spin at **6,000 xg** for **30 minutes** at 4°C.
2. **Remove supernatant:** Carefully decant or pipette off the ethanol supernatant, without disturbing the pellet.
3. **Wash pellet:** Add **1 mL of 70% ethanol** to the tube.
   - Gently invert 2-3 times to wash. **Do NOT vortex**.
4. **Centrifuge:** Spin at **6,000 xg** for **5 minutes** at 4°C.
5. **Remove supernatant:** Carefully pipette off the 70% ethanol.
6. **Repeat wash:** Repeat the **70% ethanol** wash a second time.
7. **Air dry:** Leave the tube open at room temperature for **5-10 minutes**.
   - **CRITICAL:** Do not over-dry. If the pellet turns completely clear and cracks, it becomes difficult to resuspend. A slight glistening at the bottom is fine.

---

### 4.6 Resuspension (Day 3)

1. **Add buffer:** Add **200 µL of TL Buffer** (or equivalent kit lysis buffer) directly to the pellet.
2. **Resuspend:** Pipette up and down 10-15 times to dissolve the pellet.
3. **Heat if needed:** If the pellet doesn't dissolve, incubate at **55°C for 5-10 minutes** with occasional pipetting to mix.

---

### 4.7 Column Cleanup (Day 3)

> ⚠️ **Before starting:** Set heat block to 70°C and warm Elution Buffer.

Proceed with the OMEGA E.Z.N.A. column extraction protocol (or equivalent):

1. **Add ethanol:** Add **200 µL of ice-cold 100% ethanol** to the resuspended sample.
2. **Mix:** Vortex thoroughly (10 seconds).
3. **Load column:** Transfer entire mixture to a labeled spin column in a collection tube.
   - If volume exceeds column capacity, load in multiple aliquots, centrifuging between each.
4. **Centrifuge:** Spin at **6,000 xg** for **1 minute**. Discard flow-through.
5. **Wash 1 (HBC Buffer):** Add **500 µL HBC Buffer**. Centrifuge at 6,000 xg for 30 seconds. Discard flow-through.
6. **Wash 2 (Wash Buffer):** Add **700 µL Wash Buffer**. Centrifuge at 6,000 xg for 30 seconds. Discard flow-through.
7. **Repeat Wash 2:** Add another **700 µL Wash Buffer**. Centrifuge at 6,000 xg for 30 seconds. Discard flow-through.
8. **Dry column:** Centrifuge at **maximum speed** for **4 minutes** to remove residual ethanol.
   - **CRITICAL:** This ensures no ethanol contaminates the final eluate.
9. **Elute:** Place column in a new, labeled **1.5 mL microcentrifuge tube**.
   - Add **50 µL of Elution Buffer** (heated to 70°C) directly to the center of the membrane.
   - Let sit for 2 minutes.
   - Centrifuge at maximum speed for 1 minute.
10. **Optional double elution:** Repeat step 9 with a second 50 µL aliquot and combine eluates for increased yield.

---

## 5.0 Quality Control and Quantification

| **Parameter** | **Method** | **Acceptable Range** | **Action if Out of Range** |
| :--- | :--- | :--- | :--- |
| **Concentration** | **Qubit HS** | ≥ 1 ng/µL | Re-extract or concentrate (SpeedVac). |
| **Purity** | Nanodrop A260/A280 | 1.8 – 2.0 | Protein contamination. Increase Proteinase K digestion. |
| **Purity** | Nanodrop A260/A230 | 2.0 – 2.2 | Salt/ethanol contamination. Add extra 70% wash or dry longer. |

---

## 6.0 Cleanup and Documentation

1. Dispose of all hazardous waste in designated containers.
2. Clean workspace with 10% bleach followed by 70% ethanol.
3. Return reagents to proper storage temperatures.
4. Record all steps, deviations, and results in lab notebook.
5. Store extracted DNA at **-20°C** (short-term) or **-80°C** (long-term).

---

## 7.0 Troubleshooting

| **Problem** | **Possible Cause** | **Solution** |
| :--- | :--- | :--- |
| Low yield | Lysis incomplete | Increase Proteinase K digestion time (overnight) or temperature (60°C max). |
| Low yield | Inefficient precipitation | Ensure > 1 volume ethanol was used. Increase centrifugation to 45 minutes.|
| Low yield | Inefficient elution | Incubate elution buffer on membrane for 5 minutes. Use double elution. |
| Low A260/280 | Protein contamination | Increase Proteinase K digestion or add second Prot-K treatment. |
| Low A260/230 | Salt/ethanol contamination | Add extra 70% ethanol wash. Dry column longer (5 min). |
| Column clogged | SDS carryover | Be more careful transferring supernatant (avoid pellet). Reduce sample input. |
| Negative control positive | Contamination | Review decontamination procedures. Replace reagents. Use fresh tips. |
| PCR inhibition | Co-purified humic acids | Dilute eluate 1:10. Add inhibitor removal step (e.g., Zymo OneStep). Switch to inhibitor-specific column kit (e.g., Qiagen PowerSoil)|
| PCR inhibition | Co-precipitated SDS | Avoid bottom liquid/pellet after 5M NaCl salting out. Ensure two 70% ethanol wash steps of pellet. |

---

## 8.0 Quick Reference: Volumes and Times

| **Step** | **Tube** | **Volume** | **Time** | **Temp** | **Speed** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Sample preservation | 5 mL | 2.5 mL buffer + ~2 mL water | - | RT | - |
| Proteinase K digestion | 5 mL | 100 µL ProtK | Overnight | 55°C | - |
| Salting-out | 5 mL | 1 mL 5M NaCl | 15 min | RT | 6,000 xg |
| Ethanol precipitation | 15 mL | 1 vol 100% ethanol | 1-2 hours | -20°C | - |
| Pellet recovery | 15 mL | - | 30 min | 4°C | 6,000 xg |
| Wash | 15 mL | 1-2 mL 70% ethanol | 5 min | 4°C | 6,000 xg |
| Resuspend | 1.5 mL | 200 µL TL Buffer | 5-10 min | 55°C | - |
| Column elution | Spin column | 50-100 µL | 2 min | 70°C | Max speed |

---

## 9.0 Safety Information

| **Reagent** | **Hazard** | **Precaution** |
| :--- | :--- | :--- |
| SDS | Skin/eye irritant | Wear gloves and safety glasses. |
| Ethanol | Flammable | Use away from open flames. |
| Bleach | Corrosive | Use in well-ventilated area. Neutralize before disposal. |
| Proteinase K | Allergen | Avoid inhalation of aerosolized enzyme. |

---

**For internal use only.**  
**Biodiversity Genomics Group**  
Ecology and Genetics Research Unit  
University of Oulu, Finland  
https://biodiversitygenomics.org/

---
