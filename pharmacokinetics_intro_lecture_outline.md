# Introduction to Pharmacokinetics: Lecture Outline
## Based on Boomer.org PHAR 7632 Syllabus

**Duration:** 90 minutes
**Level:** Introductory
**Target Audience:** Students new to pharmacokinetics

---

## Learning Objectives

By the end of this lecture, students will be able to:
1. Define pharmacokinetics and explain its clinical importance
2. Describe the four ADME processes
3. Understand and calculate basic PK parameters (Vd, Cl, t½)
4. Interpret a concentration-time curve
5. Distinguish between first-order and zero-order kinetics
6. Explain the concept of bioavailability

---

## Lecture Structure (90 minutes)

### PART 1: Introduction & Fundamentals (20 minutes)

#### Slide 1: Title Slide
**Title:** Introduction to Pharmacokinetics
**Subtitle:** What the Body Does to the Drug

**Speaker Notes:**
- Contrast with pharmacodynamics (what the drug does to the body)
- Reference: Boomer.org Chapter 3

---

#### Slide 2: What is Pharmacokinetics?
**Content:**
- **Definition:** Study of drug movement through the body over time
- **Clinical Importance:**
  - Dosing regimen design
  - Predicting drug concentrations
  - Individualizing therapy
  - Understanding drug interactions

**Visual:** Simple diagram of drug journey through body

**Speaker Notes:**
- Give real-world example: Why does aspirin work for 4-6 hours but needs to be redosed?
- Why do some drugs require loading doses?

---

#### Slide 3: ADME - The Four Fundamental Processes
**Content:**
- **A**bsorption - Drug enters bloodstream
- **D**istribution - Drug disperses through body compartments
- **M**etabolism - Drug is chemically transformed
- **E**xcretion - Drug is removed from body

**Visual:** Flow diagram showing ADME sequence

**Speaker Notes:**
- Each process affects drug concentration over time
- These processes often occur simultaneously
- Reference: Boomer.org Chapter 3

**Interactive Element:** Ask students to guess which process is fastest for IV vs oral administration

---

#### Slide 4: The Concentration-Time Relationship
**Content:**
- Drug effect relates to concentration at site of action
- We measure plasma/blood concentration as surrogate
- Concentration changes over time due to ADME

**Visual:** Generic concentration-time curve showing:
- Peak concentration (Cmax)
- Time to peak (Tmax)
- Elimination phase

**Speaker Notes:**
- This curve tells the "story" of the drug in the body
- Shape varies by route of administration

---

### PART 2: Compartment Models & IV Bolus (25 minutes)

#### Slide 5: Introduction to Compartment Models
**Content:**
- **Compartment:** Theoretical space where drug distributes uniformly
- **One-Compartment Model:** Simplest case
  - Assumes instantaneous distribution
  - Drug behaves as if in single homogeneous space

**Visual:** Box diagram showing:
```
     Dose → [Central Compartment] → Elimination
              (Volume = Vd)
```

**Speaker Notes:**
- This is a mathematical model, not anatomical
- Useful for many drugs
- Reference: Boomer.org Chapter 4

---

#### Slide 6: IV Bolus - Simplest Administration
**Content:**
- **IV Bolus:** Entire dose given instantly into bloodstream
- Absorption = 100% (bypasses absorption)
- Allows us to focus on distribution and elimination

**Visual:** Syringe → bloodstream diagram

**Equation:**
```
C(t) = C₀ · e^(-k·t)
```
Where:
- C(t) = concentration at time t
- C₀ = initial concentration
- k = elimination rate constant
- t = time

**Speaker Notes:**
- This exponential equation describes first-order elimination
- Most drugs follow first-order kinetics

---

#### Slide 7: KEY PARAMETER 1 - Volume of Distribution (Vd)
**Content:**
**Definition:** Theoretical volume needed to account for all drug in the body at the same concentration as plasma

**Formula:**
```
Vd = Dose / C₀
```

**Clinical Interpretation:**
- Small Vd (5-15 L): Drug stays in plasma (e.g., warfarin)
- Moderate Vd (15-50 L): Distributes to extracellular fluid
- Large Vd (>50 L): Extensively distributed to tissues (e.g., digoxin ~500 L)

**Visual:** Comparison diagram showing drug distribution in different Vd scenarios

**Speaker Notes:**
- Vd > total body water means extensive tissue binding
- Affects loading dose calculations
- Reference: Boomer.org Chapter 4
- **Practice:** If 1000 mg gives C₀ = 20 mg/L, what is Vd? (Answer: 50 L)

---

#### Slide 8: KEY PARAMETER 2 - Clearance (Cl)
**Content:**
**Definition:** Volume of plasma completely cleared of drug per unit time

**Formula:**
```
Cl = k · Vd
```
Or:
```
Cl = Dose / AUC
```

**Units:** mL/min or L/h

**Clinical Interpretation:**
- Measure of drug elimination efficiency
- Affected by liver function (hepatic Cl) and kidney function (renal Cl)
- Determines maintenance dose

**Visual:** Diagram showing blood flowing through eliminating organ

**Speaker Notes:**
- Total Cl = Hepatic Cl + Renal Cl + Other
- Renal impairment reduces Cl → need dose adjustment
- Reference: Boomer.org Chapter 4

---

#### Slide 9: KEY PARAMETER 3 - Half-Life (t½)
**Content:**
**Definition:** Time required for plasma concentration to decrease by 50%

**Formula:**
```
t½ = 0.693 / k
```
Or:
```
t½ = (0.693 · Vd) / Cl
```

**Clinical Significance:**
- Determines dosing interval
- Time to steady-state ≈ 5 × t½
- Time to eliminate ≈ 5 × t½

**Visual:** Graph showing concentration halving over time intervals

**Practice Problem:**
If C₀ = 100 mg/L and t½ = 4 hours:
- C at 4h? (50 mg/L)
- C at 8h? (25 mg/L)
- C at 12h? (12.5 mg/L)

**Speaker Notes:**
- After 5 half-lives, ~97% of drug is eliminated
- Reference: Boomer.org Chapter 5

---

#### Slide 10: First-Order vs Zero-Order Kinetics
**Content:**

**First-Order (Most Common):**
- Constant fraction eliminated per unit time
- Exponential decay
- t½ is constant
- Examples: Most drugs

**Zero-Order (Rare):**
- Constant amount eliminated per unit time
- Linear decay
- t½ changes with concentration
- Examples: Ethanol (at high doses), phenytoin, aspirin (high doses)

**Visual:** Side-by-side graphs comparing first-order curve (exponential) vs zero-order (linear)

**Speaker Notes:**
- Zero-order occurs when elimination mechanisms are saturated
- Clinical importance: Small dose changes can cause large concentration changes
- Reference: Boomer.org Chapter 22

---

### PART 3: IV Infusion & Steady State (15 minutes)

#### Slide 11: Continuous IV Infusion
**Content:**
- Drug administered at constant rate (R₀)
- Builds up to steady-state
- Input rate = Elimination rate at steady state

**Formula:**
```
Css = R₀ / Cl
```

**Visual:** Graph showing concentration rising to plateau (steady-state)

**Time to Steady-State:**
- 50% of Css at 1 × t½
- 75% of Css at 2 × t½
- 87.5% of Css at 3 × t½
- 97% of Css at 5 × t½

**Speaker Notes:**
- Used for drugs needing constant levels (e.g., dopamine, heparin)
- Reference: Boomer.org Chapter 6

---

#### Slide 12: Loading Dose Concept
**Content:**
**Problem:** Takes 5 × t½ to reach steady-state. What if we need therapeutic levels immediately?

**Solution:** Loading Dose

**Formula:**
```
Loading Dose = Vd · Ctarget
```

**Example:**
- Drug with t½ = 24 hours (5 days to steady-state!)
- Loading dose achieves therapeutic level immediately
- Maintenance dose maintains it

**Visual:** Graph comparing with vs without loading dose

**Speaker Notes:**
- Common for digoxin, phenytoin, some antibiotics
- Risk: Toxicity if Vd estimated incorrectly

---

### PART 4: Oral Administration & Bioavailability (15 minutes)

#### Slide 13: Oral Administration - A Different Story
**Content:**
**Differences from IV:**
- Must be absorbed (absorption phase)
- Cmax < C₀ for same dose
- Tmax - time to reach peak
- First-pass metabolism reduces amount reaching circulation

**Visual:** Oral vs IV concentration-time curves overlaid

**Speaker Notes:**
- Oral is most convenient route
- But more complex pharmacokinetics
- Reference: Boomer.org Chapters 7-8

---

#### Slide 14: Bioavailability (F)
**Content:**
**Definition:** Fraction of administered dose that reaches systemic circulation unchanged

**Formula:**
```
F = (AUC_oral · Dose_IV) / (AUC_IV · Dose_oral)
```

**Range:** 0 to 1 (or 0% to 100%)

**Factors Affecting F:**
- First-pass metabolism
- Drug stability in GI tract
- Absorption across GI membrane
- Formulation factors

**Examples:**
- IV: F = 1.0 (100%)
- Oral morphine: F ≈ 0.25 (25%)
- Oral amoxicillin: F ≈ 0.80 (80%)

**Speaker Notes:**
- Low F means oral dose must be higher than IV dose
- Varies between patients
- Reference: Boomer.org Chapters 9-10

---

#### Slide 15: Bioequivalence
**Content:**
**Definition:** Two formulations are bioequivalent if they deliver same amount of drug to circulation at same rate

**Criteria:**
- Same AUC (extent of absorption)
- Same Cmax and Tmax (rate of absorption)

**Clinical Importance:**
- Generic vs brand-name drugs
- Changing formulations

**Visual:** Graph showing overlapping curves for bioequivalent products

**Speaker Notes:**
- FDA requires bioequivalence studies for generics
- 90% confidence interval for 80-125% ratio

---

### PART 5: Clinical Applications & Examples (10 minutes)

#### Slide 16: Putting It All Together - Case Example
**Content:**
**Clinical Scenario:**
Patient needs gentamicin (antibiotic)
- Target Css = 5 mg/L
- Gentamicin: Vd = 20 L, Cl = 100 mL/min, t½ = 2.3 hours

**Calculate:**
1. **Infusion rate for steady-state:**
   ```
   R₀ = Css · Cl = 5 mg/L · 100 mL/min · 60 min/h ÷ 1000 mL/L
   R₀ = 30 mg/h
   ```

2. **Loading dose (if needed):**
   ```
   LD = Vd · Ctarget = 20 L · 5 mg/L = 100 mg
   ```

3. **Time to steady-state without loading dose:**
   ```
   ~5 × t½ = 5 × 2.3h ≈ 11.5 hours
   ```

**Speaker Notes:**
- Walk through calculation step-by-step
- Emphasize clinical decision-making

---

#### Slide 17: Special Populations
**Content:**
**PK Parameters Change With:**

**Renal Impairment:**
- ↓ Clearance (for renally eliminated drugs)
- ↑ Half-life
- Need dose reduction

**Hepatic Impairment:**
- ↓ Metabolism
- ↓ Clearance
- ↑ Half-life

**Elderly:**
- ↓ Renal function
- ↓ Lean body mass
- Often need lower doses

**Pediatric:**
- Age-dependent changes in Vd, Cl
- Dosing often weight-based

**Obesity:**
- ↑ Vd for lipophilic drugs
- May need adjusted dosing

**Speaker Notes:**
- Always consider patient-specific factors
- Reference: Boomer.org Chapter 25

---

### PART 6: Summary & Next Steps (5 minutes)

#### Slide 18: Key Concepts Summary
**Content:**
**What We Covered:**
1. ✓ Pharmacokinetics = what body does to drug
2. ✓ ADME processes
3. ✓ Three critical parameters: Vd, Cl, t½
4. ✓ First-order kinetics (exponential decay)
5. ✓ IV infusion and steady-state
6. ✓ Bioavailability for oral drugs

**The Foundation:**
These basic principles underlie ALL pharmacokinetic calculations and clinical applications

---

#### Slide 19: What's Next? (Advanced Topics)
**Content:**
**Build on this foundation:**
- Multiple compartment models
- Multiple dosing and accumulation
- Non-linear kinetics
- Therapeutic drug monitoring
- Population pharmacokinetics
- Pharmacokinetic/pharmacodynamic modeling

**Resources:**
- Boomer.org complete syllabus: https://www.boomer.org/c/p4/syllabus.html
- Interactive calculators and simulations available

---

#### Slide 20: Practice Problems for Students
**Content:**

**Problem 1:**
A 1000 mg IV bolus dose yields C₀ = 25 mg/L. The half-life is 6 hours.
- Calculate Vd
- Calculate k
- Calculate concentration at 12 hours

**Problem 2:**
A drug has Cl = 50 mL/min. What infusion rate achieves Css = 10 mg/L?

**Problem 3:**
If a drug has F = 0.5 and you need 200 mg to reach circulation, what oral dose should be given?

**Answers:**
1. Vd = 40 L; k = 0.116 h⁻¹; C₁₂ₕ = 6.25 mg/L
2. R₀ = 30 mg/h
3. Oral dose = 400 mg

---

## Visual Assets Needed

1. **ADME Flow Diagram** - Show drug journey through body
2. **Concentration-Time Curves** - Multiple versions:
   - IV bolus (exponential decay)
   - Oral (absorption + elimination)
   - IV infusion (rise to steady-state)
   - First-order vs zero-order comparison
3. **Compartment Model Diagrams** - Box and arrow representations
4. **Vd Conceptual Diagram** - Show how different Vd values represent different distribution
5. **Clearance Mechanism** - Blood flowing through eliminating organ
6. **Half-Life Illustration** - Step-wise halving of concentration
7. **Bioavailability Factors** - GI tract showing first-pass effect

---

## Interactive Elements

### Polling Questions (if using audience response system):
1. "Which process is bypassed with IV administration?" (A: Absorption)
2. "A Vd of 500 L in a 70 kg patient suggests what?" (A: Extensive tissue distribution)
3. "After 3 half-lives, approximately what % of drug remains?" (A: 12.5%)

### Think-Pair-Share Activities:
1. After Slide 7: "Why might two drugs with same dose have very different C₀ values?"
2. After Slide 14: "Why is oral morphine dose much higher than IV morphine dose?"

### Demonstration Ideas:
1. Use online calculator from Boomer.org to show real-time PK simulation
2. Show how changing Cl affects steady-state concentration

---

## Additional Resources for Students

### Boomer.org Chapter References:
- **Chapter 1-2:** Mathematical background (review as needed)
- **Chapter 3:** Pharmacokinetic fundamentals - START HERE
- **Chapter 4:** One-compartment IV bolus - Core material
- **Chapter 5:** Derived parameters (Vd, Cl, t½)
- **Chapter 6:** IV infusion and steady-state
- **Chapter 7-8:** Oral administration and bioavailability

### Recommended Reading Order:
1. Start with Chapter 3 (fundamentals)
2. Work through Chapters 4-5 (IV bolus)
3. Review Chapter 6 (infusion)
4. Then Chapters 7-8 (oral/bioavailability)

### Online Tools:
- Boomer.org interactive calculators
- Concentration-time curve simulators
- Practice problem sets with solutions

---

## Instructor Notes

### Timing Adjustments:
- If running short on time, condense slides 16-17 (clinical applications)
- Can move bioequivalence (slide 15) to advanced lecture
- Can expand problem-solving if students need more practice

### Common Student Misconceptions:
1. **Vd is a real volume:** Emphasize it's theoretical/apparent
2. **Half-life is when drug "stops working":** Clarify it's about concentration, not effect
3. **Zero-order is common:** Most drugs follow first-order
4. **Bioavailability only about absorption:** First-pass metabolism is major factor

### Difficult Concepts (Plan Extra Time):
- Volume of distribution > body volume (seems paradoxical)
- Logarithmic vs linear scales on graphs
- Relationship between k, Cl, Vd, and t½
- Why steady-state takes 5 × t½

### Assessment Suggestions:
- **Formative:** Practice problems throughout lecture
- **Summative:** Problem set covering calculations of Vd, Cl, t½, dosing
- **Application:** Case-based scenarios requiring PK reasoning

---

## Equipment/Technology Needed

- Projector/screen
- Computer with internet access (for Boomer.org demonstrations)
- Whiteboard/markers for working through calculations
- Optional: Audience response system (Poll Everywhere, Mentimeter, etc.)
- Optional: Graphing software (Excel, GraphPad) for live demonstrations

---

## Pre-Lecture Preparation

### For Instructor:
1. Review Boomer.org Chapters 3-8
2. Test all calculator links
3. Prepare worked solutions for practice problems
4. Create handout with key equations
5. Set up any online polling

### For Students (Pre-Reading):
- Review basic algebra and logarithms
- Read Boomer.org Chapter 3
- Come with questions about ADME

### Post-Lecture Assignment:
- Complete practice problem set (create 10-15 problems)
- Read Boomer.org Chapters 4-6
- Explore interactive calculators on Boomer.org

---

## Key Equations Reference Sheet (Handout)

```
FUNDAMENTAL EQUATIONS

Volume of Distribution:
    Vd = Dose / C₀

Clearance:
    Cl = k · Vd
    Cl = Dose / AUC

Elimination Rate Constant:
    k = Cl / Vd
    k = 0.693 / t½

Half-Life:
    t½ = 0.693 / k
    t½ = (0.693 · Vd) / Cl

Concentration After IV Bolus:
    C(t) = C₀ · e^(-k·t)
    ln(C) = ln(C₀) - k·t

Steady-State (IV Infusion):
    Css = R₀ / Cl

Loading Dose:
    LD = Vd · Ctarget

Bioavailability:
    F = (AUC_oral · Dose_IV) / (AUC_IV · Dose_oral)

Oral Dose Adjustment:
    Dose_oral = Dose_IV / F
```

---

## Appendix: Extended Examples

### Example 1: Phenobarbital Dosing
**Given:**
- Patient: 70 kg adult
- Phenobarbital Vd = 0.7 L/kg = 49 L
- t½ = 100 hours
- Target Css = 20 mg/L

**Calculate k:**
k = 0.693 / 100h = 0.00693 h⁻¹

**Calculate Cl:**
Cl = k · Vd = 0.00693 h⁻¹ · 49 L = 0.34 L/h

**Calculate infusion rate for steady-state:**
R₀ = Css · Cl = 20 mg/L · 0.34 L/h = 6.8 mg/h ≈ 163 mg/day

**Calculate loading dose:**
LD = Vd · Css = 49 L · 20 mg/L = 980 mg ≈ 1000 mg

**Clinical Decision:**
- Give 1000 mg loading dose
- Follow with 160 mg daily maintenance dose
- Takes 500 hours (≈21 days) to reach steady-state without loading!

---

### Example 2: Comparing Two Drugs
**Drug A vs Drug B (same dose: 500 mg IV bolus)**

Drug A:
- Vd = 10 L → C₀ = 50 mg/L
- Cl = 100 mL/min
- t½ = 1.2 hours

Drug B:
- Vd = 200 L → C₀ = 2.5 mg/L
- Cl = 100 mL/min
- t½ = 23 hours

**Observations:**
1. Same Cl, but very different t½ (due to different Vd)
2. Large Vd → low plasma concentration → longer t½
3. Drug A: Short-acting, frequent dosing needed
4. Drug B: Long-acting, once-daily dosing possible

**Clinical Lesson:** Can't predict dosing frequency from Cl alone; must know Vd and t½

---

## Notes on Boomer.org Navigation

**Direct Chapter Links:**
- Chapter 3: https://www.boomer.org/c/p4/c03/c03.htm
- Chapter 4: https://www.boomer.org/c/p4/c04/c04.htm
- Chapter 5: https://www.boomer.org/c/p4/c05/c05.htm
- Chapter 6: https://www.boomer.org/c/p4/c06/c06.htm

**Interactive Tools:**
- Look for calculator icons throughout chapters
- Simulation tools allow parameter manipulation
- Graph generators for concentration-time curves

---

## License & Attribution

This lecture outline is based on publicly available educational materials from:
- **Boomer.org Pharmacokinetics Resources** (www.boomer.org/c/p4)
- Created by David Bourne, Ph.D.
- Affiliated with OUHSC, SUNY Buffalo, and University of Wisconsin programs

**Recommended Citation:**
Adapted from PHAR 7632 Pharmacokinetics and Biopharmaceutics syllabus, Boomer.org

---

**Document Version:** 1.0
**Last Updated:** 2025-11-12
**Contact:** [Your contact information]

---

## Quick Start Checklist

- [ ] Review all slides
- [ ] Test Boomer.org links
- [ ] Prepare equation handout
- [ ] Create practice problem answer key
- [ ] Set up demonstration calculator
- [ ] Print student materials
- [ ] Test A/V equipment
- [ ] Prepare backup examples
- [ ] Review common student questions
- [ ] Have clinical scenarios ready

**Good luck with your lecture!**
