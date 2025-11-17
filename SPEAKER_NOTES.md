# Speaker Notes: Introduction to Pharmacokinetics
## 90-Minute Lecture Based on Boomer.org PHAR 7632 Syllabus

---

## Slide 1: Title Slide
**Title:** Introduction to Pharmacokinetics
**Subtitle:** What the Body Does to the Drug

**NOTES:**
- Welcome students
- This is an introductory lecture - no prior PK knowledge assumed
- 90 minutes total with 5 parts

---

## Slide 2: Learning Objectives

**Content:**
By the end of this lecture, you will be able to:
1. Define pharmacokinetics and explain its clinical importance
2. Describe the four ADME processes
3. Understand and calculate basic PK parameters (Vd, Cl, t½)
4. Interpret a concentration-time curve
5. Distinguish between first-order and zero-order kinetics
6. Explain the concept of bioavailability

**SPEAKER NOTES:**
- Set expectations for what students will learn
- These are foundational concepts for clinical practice
- Reference: Boomer.org Chapter 3
- Emphasize that these concepts apply to EVERY drug they'll prescribe

---

# PART 1: FUNDAMENTALS (20 minutes)

---

## Slide 3: What is Pharmacokinetics?

**Content:**
- **Definition:** Study of drug movement through the body over time
- **Clinical Importance:**
  - Dosing regimen design
  - Predicting drug concentrations
  - Individualizing therapy
  - Understanding drug interactions

**SPEAKER NOTES:**
- Contrast with pharmacodynamics (what drug does to body)
- Give example: Why does aspirin work for 4-6 hours? Because of PK!
- Why do some drugs require loading doses? Because of PK principles
- PK tells us WHEN to give a drug and HOW MUCH
- PD tells us WHAT the drug does

**DIAGRAM:** ADME flowchart showing drug journey

---

## Slide 4: ADME - The Four Fundamental Processes

**Content Table:**
| Process | Definition | Key Factors |
|---------|------------|-------------|
| **Absorption** | Drug enters bloodstream | Route, formulation, GI pH |
| **Distribution** | Drug disperses through body | Blood flow, Vd, binding |
| **Metabolism** | Drug chemically transformed | Liver function, CYP enzymes |
| **Excretion** | Drug removed from body | Renal function, biliary |

**INTERACTIVE QUESTION:**
💡 Which process is fastest for IV vs oral administration?

**SPEAKER NOTES:**
- Each process affects drug concentration over time
- These processes often occur simultaneously, not sequential
- IV bypasses absorption - that's why it acts immediately
- **Answer to question:** Absorption is BYPASSED for IV, so IV is fastest
- Image references available: ResearchGate and NCBI diagrams

---

## Slide 5: The Concentration-Time Relationship

**Content:**
- Drug effect relates to concentration at site of action
- We measure plasma concentration as surrogate
- Concentration changes over time due to ADME

**Important Parameters:**
- **Cmax:** Peak concentration
- **Tmax:** Time to peak
- **AUC:** Area under curve (total exposure)

**VISUAL:** R-generated graph showing typical oral drug curve with Tmax and Cmax labeled

**SPEAKER NOTES:**
- This curve tells the "story" of the drug in the body
- Shape varies by route of administration
- Cmax determines if we reach therapeutic level
- AUC tells us total drug exposure
- These parameters used for bioequivalence studies

**Image references:** ScienceDirect and ResearchGate curves

---

# PART 2: COMPARTMENT MODELS & IV BOLUS (25 minutes)

---

## Slide 6: Introduction to Compartment Models

**Content:**
- **Compartment:** Theoretical space where drug distributes uniformly
- **One-Compartment Model:**
  - Simplest case
  - Assumes instantaneous distribution
  - Drug behaves as if in single homogeneous space
  - Mathematical model, not anatomical

**Useful for:**
- Drugs with rapid distribution
- Initial understanding of PK principles
- Examples: Aminoglycosides

**SPEAKER NOTES:**
- This is a MATHEMATICAL model, not anatomical reality
- Simplification that works surprisingly well for many drugs
- Useful for aminoglycosides despite their rapid distribution
- Reference: Boomer.org Chapter 4 and Deranged Physiology

**DIAGRAM:** Mermaid flowchart showing dose → central compartment → elimination

---

## Slide 7: IV Bolus - Simplest Administration

**Content:**
- Entire dose given instantly into bloodstream
- Absorption = 100% (bypasses absorption)
- Allows focus on distribution and elimination

**First-Order Elimination Equation:**
$$C(t) = C_0 \cdot e^{-k \cdot t}$$

Where:
- C(t) = concentration at time t
- C₀ = initial concentration
- k = elimination rate constant
- t = time

**SPEAKER NOTES:**
- This exponential equation describes first-order elimination
- Most drugs follow first-order kinetics
- IV bolus is simplest scenario - helps us learn fundamentals
- The graph shows exponential decay - curved line, not straight

**VISUAL:** R-generated graph showing exponential decay with half-life markers

---

## Slide 8: KEY PARAMETER 1 - Volume of Distribution (Vd)

**Formula:** $$V_d = \frac{Dose}{C_0}$$

**Clinical Interpretation Table:**
| Vd Range | Interpretation | Example |
|----------|----------------|---------|
| 5-15 L | Confined to plasma | Warfarin (~8 L) |
| 15-50 L | Extracellular fluid | Many antibiotics |
| >50 L | Extensive tissue distribution | Digoxin (~500 L) |

**Key Point:** 💡 Vd > total body water means extensive tissue binding

**SPEAKER NOTES:**
- Vd is THEORETICAL/APPARENT volume, not a real anatomical space
- If Vd = 500 L in 70 kg person, that's way more than body water (~42 L)!
- This means drug is binding extensively to tissues
- Affects loading dose calculations
- Total body water: Plasma 3L, Blood 5L, ECF 14L, TBW 42L
- Digoxin's huge Vd (500L) is because it binds to muscle tissue

**PRACTICE PROBLEM:**
If 1000 mg gives C₀ = 20 mg/L, what is Vd?
**Answer:** Vd = 1000 mg ÷ 20 mg/L = **50 L**

**DIAGRAM:** Mermaid showing same dose, different Vd values, different C₀

---

## Slide 9: KEY PARAMETER 2 - Clearance (Cl)

**Definition:** Volume of plasma completely cleared of drug per unit time

**Formulas:**
- Cl = k × Vd
- Cl = Dose / AUC
- Cl_total = Cl_hepatic + Cl_renal + Cl_other

**Units:** mL/min or L/h

**SPEAKER NOTES:**
- Clearance is a measure of elimination EFFICIENCY
- Independent of dose for first-order kinetics
- Determines maintenance dose
- Affected by liver function (hepatic Cl) and kidney function (renal Cl)
- Renal impairment reduces Cl → need dose adjustment
- Think of it as: How much blood is being "cleaned" of drug per minute?

**VISUAL:** R-generated bar chart showing typical clearance distribution (Liver 40, Kidneys 55, Other 5 mL/min)

**CLINICAL SIGNIFICANCE:**
- If Cl decreases (kidney or liver disease), drug accumulates
- Must reduce maintenance dose proportionally

---

## Slide 10: KEY PARAMETER 3 - Half-Life (t½)

**Definition:** Time required for plasma concentration to decrease by 50%

**Formulas:**
- t½ = 0.693 / k
- t½ = (0.693 × Vd) / Cl

**Clinical Significance:**
- Determines dosing interval
- Time to steady-state ≈ 5 × t½
- Time to eliminate ≈ 5 × t½

**Half-Life Decay Table:**
| Time | Fraction Remaining | % Remaining |
|------|-------------------|-------------|
| 1 t½ | 1/2 | 50% |
| 2 t½ | 1/4 | 25% |
| 3 t½ | 1/8 | 12.5% |
| 4 t½ | 1/16 | 6.25% |
| 5 t½ | 1/32 | 3.1% |

**SPEAKER NOTES:**
- After 5 half-lives, ~97% of drug is eliminated
- This is the "5 half-lives rule" - memorize it!
- Half-life depends on BOTH Vd and Cl
- Reference: Boomer.org Chapter 5

**PRACTICE PROBLEM:**
If C₀ = 100 mg/L and t½ = 4 hours:
- C at 4h? **50 mg/L** (1 half-life)
- C at 8h? **25 mg/L** (2 half-lives)
- C at 12h? **12.5 mg/L** (3 half-lives)

---

## Slide 11: Relating Vd, Cl, k, and t½

**Key Relationships:**
- k = Cl / Vd
- t½ = 0.693 / k
- t½ = (0.693 × Vd) / Cl

**CALLOUT - Key Insights:**
- k depends on both Cl and Vd
- t½ depends on both Cl and Vd
- If Cl normal but t½ long → Vd must be large
- If Vd normal but t½ short → Cl must be high

**SPEAKER NOTES:**
- These four parameters are interconnected
- Can't think about one in isolation
- If you know any two, you can calculate the others
- This is why understanding relationships is crucial

**DIAGRAM:** Mermaid showing interconnections between all four parameters

---

## Slide 12: First-Order vs Zero-Order Kinetics

**First-Order (Most Common):**
- Constant FRACTION eliminated per unit time
- Exponential decay
- t½ is constant
- Rate = k × C (concentration-dependent)
- Examples: Most drugs at therapeutic doses

**Zero-Order (Rare):**
- Constant AMOUNT eliminated per unit time
- Linear decay
- t½ changes with concentration
- Rate = constant (saturable)
- Examples: Ethanol, phenytoin, aspirin (high doses)

**SPEAKER NOTES:**
- Zero-order occurs when elimination mechanisms are saturated
- Clinical importance: Small dose changes can cause LARGE concentration changes
- Phenytoin is classic example - very dangerous
- Reference: Boomer.org Chapter 22

**VISUAL:** R-generated graph comparing first-order (curved) vs zero-order (straight line)

**Resources:** NCBI and Deranged Physiology links

---

# PART 3: IV INFUSION & STEADY STATE (15 minutes)

---

## Slide 13: Continuous IV Infusion

**Concept:**
- Drug administered at constant rate (R₀)
- Builds up to steady-state
- Input rate = Elimination rate at steady state

**Formula:** $$C_{ss} = \frac{R_0}{Cl}$$

**Time to Steady-State:**
- 50% at 1 × t½
- 75% at 2 × t½
- 87.5% at 3 × t½
- **97% at 5 × t½**

**SPEAKER NOTES:**
- Used for drugs needing constant levels (dopamine, heparin, propofol)
- Takes 5 half-lives to reach steady-state
- If t½ = 24 hours, takes 5 DAYS to reach steady-state!
- This is why loading doses are sometimes needed

**VISUAL:** R-generated graph showing rise to steady-state with half-life markers

**Image reference:** ResearchGate IV infusion curve

---

## Slide 14: Loading Dose Concept

**Problem:** Takes 5 × t½ to reach steady-state. What if we need therapeutic levels IMMEDIATELY?

**Solution:** Loading Dose

**Formula:** $$Loading\ Dose = V_d \times C_{target}$$

**Example:**
- Drug with t½ = 24 hours
- Would take 5 days to steady-state!
- Loading dose achieves therapeutic level immediately
- Maintenance dose maintains it

**SPEAKER NOTES:**
- Loading dose = "jumpstart" to therapeutic level
- Common for digoxin, phenytoin, some antibiotics
- Saves days of waiting for therapeutic effect

**WARNING:**
⚠️ Risk: Toxicity if Vd estimated incorrectly!

**VISUAL:** R-generated graph comparing with vs without loading dose - dramatic difference!

---

# PART 4: ORAL ADMINISTRATION & BIOAVAILABILITY (15 minutes)

---

## Slide 15: Oral Administration - A Different Story

**Differences from IV:**
- Must be absorbed (absorption phase)
- Cmax < C₀ for same dose
- Tmax - time to reach peak
- First-pass metabolism reduces amount reaching circulation

**ADME for Oral Drugs:**
- ✅ Absorption - CRITICAL step
- ✅ Distribution - same as IV after absorption
- ✅ Metabolism - occurs BEFORE systemic circulation (first-pass)
- ✅ Excretion - same as IV

**SPEAKER NOTES:**
- Oral is most convenient route
- But more complex pharmacokinetics
- First-pass metabolism is KEY difference
- Reference: Boomer.org Chapters 7-8

**VISUAL:** R-generated graph comparing IV vs Oral curves - same dose, different shapes

---

## Slide 16: Bioavailability (F)

**Definition:** Fraction of administered dose that reaches systemic circulation unchanged

**Formula:** $$F = \frac{AUC_{oral} \times Dose_{IV}}{AUC_{IV} \times Dose_{oral}}$$

**Range:** 0 to 1 (or 0% to 100%)

**Factors Affecting F:**
- First-pass hepatic metabolism ⚠️ (MAJOR)
- Incomplete absorption
- Drug degradation in GI tract
- Efflux transporters (P-glycoprotein)

**Clinical Examples Table:**
| Drug | Oral F | Reason |
|------|--------|--------|
| IV drugs | 100% | Direct to circulation |
| Morphine | ~25% | Extensive first-pass |
| Nitroglycerin | <1% | Almost complete first-pass |
| Amoxicillin | ~80% | Good absorption |

**SPEAKER NOTES:**
- F always = 1.0 for IV (by definition)
- Low F means oral dose must be MUCH higher than IV
- Morphine: If need 10 mg IV, need 40 mg orally!

**Dose Adjustment Formula:** $$Dose_{oral} = \frac{Dose_{IV}}{F}$$

**DIAGRAM:** Mermaid showing first-pass metabolism flow (100% oral → 80% absorbed → 50% survives first-pass = 40% F)

**Resources:** NCBI and ResearchGate first-pass diagrams

---

## Slide 17: Bioequivalence

**Definition:** Two formulations are bioequivalent if they deliver same amount of drug to circulation at same rate

**Criteria:**
- Same AUC (extent of absorption)
- Same Cmax and Tmax (rate of absorption)

**Clinical Importance:**
- Generic vs brand-name drugs
- Changing formulations
- Ensuring therapeutic equivalence

**FDA Requirements:**
- 90% confidence interval
- 80-125% ratio for AUC and Cmax

**SPEAKER NOTES:**
- This is how generics are approved
- Must prove bioequivalence, not just same ingredients
- Graph shows two products with nearly identical curves

**VISUAL:** R-generated graph showing overlapping brand and generic curves

---

# PART 5: CLINICAL APPLICATIONS (10 minutes)

---

## Slide 18: Clinical Case - Gentamicin Dosing

**TAB 1 - Case Presentation:**

Patient: 70 kg adult with pneumonia
Drug: Gentamicin (antibiotic)

Parameters:
- Vd = 0.25 L/kg
- t½ = 2.3 hours
- Target Css = 5 mg/L

Questions:
1. What infusion rate for steady-state?
2. What loading dose if needed?
3. Time to steady-state without loading dose?

**TAB 2 - Calculations:**

Step 1: Calculate total Vd
Vd = 0.25 L/kg × 70 kg = 17.5 L

Step 2: Calculate clearance
k = 0.693 / 2.3 h = 0.301 h⁻¹
Cl = k × Vd = 0.301 × 17.5 = 5.27 L/h

Step 3: Infusion rate
R₀ = Css × Cl = 5 mg/L × 5.27 L/h = 26.4 mg/h

**TAB 3 - Results:**

**Answers:**
1. Infusion rate: 26.4 mg/h (≈ 26-27 mg/h)
2. Loading dose: LD = Vd × Ctarget = 17.5 L × 5 mg/L = 87.5 mg
3. Time to steady-state: 5 × t½ = 5 × 2.3 h = 11.5 hours

**TIP:** Loading dose saves ~11.5 hours!

**SPEAKER NOTES:**
- Walk through calculation step-by-step
- Emphasize clinical decision-making
- This is real-world application of formulas
- Point out that loading dose provides immediate therapeutic level

---

## Slide 19: Special Populations

**TAB 1 - Renal Impairment:**

Changes:
- ↓ Clearance (for renally eliminated drugs)
- ↑ Half-life
- Need dose reduction

Dose Adjustment Formula:
$$Dose_{new} = Dose_{normal} \times \frac{CrCl_{patient}}{CrCl_{normal}}$$

Examples:
- Aminoglycosides (gentamicin, tobramycin) - CRITICAL
- Vancomycin - CRITICAL
- Many beta-lactams
- Gabapentin

**TAB 2 - Hepatic Impairment:**

Changes:
- ↓ Metabolism
- ↓ Clearance
- ↑ Half-life

Approach:
- No simple formula (use Child-Pugh score)
- Generally reduce dose by 25-50%
- Monitor closely

Examples:
- Warfarin
- Most benzodiazepines
- Opioids
- Propranolol

**TAB 3 - Elderly:**

Changes with Aging:
- ↓ Renal function (even with normal SCr)
- ↓ Lean body mass
- ↑ Body fat percentage
- ↓ Hepatic blood flow
- ↓ Albumin (affects protein binding)

Approach:
- "Start low, go slow"
- Use lower end of dosing range
- Monitor for adverse effects
- Calculate CrCl (don't rely on SCr alone)

**TAB 4 - Obesity:**

Dosing Weight Considerations:
| Drug Type | Weight to Use |
|-----------|---------------|
| Hydrophilic (small Vd) | Ideal Body Weight (IBW) |
| Lipophilic (large Vd) | Total Body Weight (TBW) |
| Compromise | Adjusted Body Weight (ABW) |

Formulas:
- IBW_male = 50 kg + 2.3 kg per inch over 5 feet
- IBW_female = 45.5 kg + 2.3 kg per inch over 5 feet
- ABW = IBW + 0.4 × (TBW - IBW)

**SPEAKER NOTES:**
- Always consider patient-specific factors
- One size does NOT fit all in pharmacokinetics
- These adjustments prevent toxicity and ensure efficacy

---

# SUMMARY & KEY CONCEPTS (5 minutes)

---

## Slide 20: Key Concepts Summary

**What We Covered:**

✅ Pharmacokinetics = what body does to drug
✅ ADME processes
✅ Three critical parameters:
  - Vd - Volume of distribution → determines loading dose
  - Cl - Clearance → determines maintenance dose
  - t½ - Half-life → determines dosing interval

✅ First-order kinetics (exponential decay) - most common
✅ IV infusion and steady-state (5 × t½ rule)
✅ Bioavailability for oral drugs (F)

**SPEAKER NOTES:**
- The foundation: These basic principles underlie ALL PK calculations
- Every dose you calculate uses these principles
- Understanding these makes you a better clinician

**DIAGRAM:** Mermaid showing PK Fundamentals → Dosing, TDM, Interactions, Special Populations → Optimal Patient Care

---

## Slide 21: Essential Formulas - Quick Reference

**Basic Parameters:**
- Vd = Dose / C₀
- Cl = k × Vd = Dose / AUC
- k = Cl / Vd = 0.693 / t½
- t½ = 0.693 / k = (0.693 × Vd) / Cl

**Clinical Applications:**
- C(t) = C₀ × e^(-k×t)
- Css = R₀ / Cl
- Loading Dose = Vd × Ctarget
- F = (AUC_oral × Dose_IV) / (AUC_IV × Dose_oral)

**REMEMBER:**
- Always include UNITS in calculations
- 5 half-lives rule for steady-state and elimination
- Clearance determines maintenance dose
- Vd determines loading dose

**SPEAKER NOTES:**
- Give students time to copy these down
- Or provide as handout
- These are the formulas they'll use repeatedly

---

## Slide 22: What's Next? Advanced Topics

**Build on this foundation:**
1. Multiple compartment models (2-compartment, 3-compartment)
2. Multiple dosing and accumulation (dosing intervals, fluctuation)
3. Non-linear kinetics (Michaelis-Menten, saturable elimination)
4. Therapeutic drug monitoring (peak/trough, target levels)
5. Population pharmacokinetics (variability, covariates)
6. Pharmacokinetic/pharmacodynamic modeling (linking PK to effects)

**SPEAKER NOTES:**
- This is just the beginning!
- These fundamentals apply to all advanced topics
- Encourage continued learning

---

## Slide 23: Practice Problems

**TAB 1 - Problem 1:**
A 1000 mg IV bolus dose yields C₀ = 25 mg/L. The half-life is 6 hours.
Calculate: a) Vd, b) k, c) Concentration at 12 hours

**TAB 2 - Solution 1:**
a) Vd = 1000 mg / 25 mg/L = 40 L
b) k = 0.693 / 6 h = 0.116 h⁻¹
c) C₁₂ₕ = 25 × (0.5)² = 6.25 mg/L (or use exponential equation)

**TAB 3 - Problem 2:**
A drug has Cl = 50 mL/min. What infusion rate achieves Css = 10 mg/L?

**TAB 4 - Solution 2:**
Convert units: Cl = 50 mL/min × 60 min/h ÷ 1000 mL/L = 3 L/h
R₀ = Css × Cl = 10 mg/L × 3 L/h = 30 mg/h

**TAB 5 - Problem 3:**
If F = 0.5 and you need 200 mg to reach circulation, what oral dose?

**TAB 6 - Solution 3:**
Dose_oral = 200 mg / 0.5 = 400 mg
Verification: 400 mg × 0.5 = 200 mg ✓

---

## Slide 24: Resources & Further Learning

**Boomer.org Chapters:**
- Chapter 3: PK Fundamentals - START HERE
- Chapter 4: One-Compartment IV Bolus
- Chapter 5: Derived Parameters
- Chapter 6: IV Infusion
- Chapters 7-8: Oral Administration
- Full Syllabus: https://www.boomer.org/c/p4/syllabus.html

**Additional Resources:**
- Interactive calculators on Boomer.org
- NCBI Pharmacokinetics
- StatPearls: Drug Bioavailability
- Deranged Physiology

**Reference Texts:**
- Rowland & Tozer: "Clinical PK & PD"
- Winter: "Basic Clinical PK"
- Shargel & Yu: "Applied Biopharm & PK"

---

## Slide 25: Questions? / Thank You

**SPEAKER NOTES:**
- Open for questions
- Remind students: "Pharmacokinetics is the foundation for rational drug therapy. Understanding these principles will make you a better clinician!"
- Provide contact information
- Remind about office hours
- Point to additional resources

---

## BONUS SLIDES (Optional - If Time Permits)

---

## Slide 26: Clinical Pearls

**Narrow Therapeutic Index Drugs - Monitor Carefully!**
- Warfarin, Digoxin, Lithium, Phenytoin, Theophylline, Aminoglycosides
- Small difference between therapeutic and toxic levels

**Red Flags:**
⚠️ Saturable kinetics: Phenytoin, aspirin, ethanol - can switch to zero-order
⚠️ Highly protein bound: Warfarin (99%), phenytoin (90%) - drug interactions affect free drug
⚠️ Renally eliminated: Adjust in renal impairment
⚠️ Hepatically eliminated: Adjust in liver disease

---

## Slide 27: Useful Conversions

**Mathematical Constants:**
- ln(2) = 0.693
- e = 2.718

**Time:** 1 hour = 60 minutes, 1 day = 24 hours = 1440 minutes

**Volume:** 1 L = 1000 mL, 1 dL = 100 mL = 0.1 L

**Concentration:** 1 mg/L = 1 mcg/mL = 1 μg/mL

**Body Water (70 kg adult):**
- Total body water: ~42 L (60%)
- Extracellular fluid: ~14 L (20%)
- Plasma volume: ~3 L (4%)
- Blood volume: ~5 L (7%)

---

## END OF SPEAKER NOTES

**Total Time:** ~90 minutes
- Part 1: 20 min
- Part 2: 25 min
- Part 3: 15 min
- Part 4: 15 min
- Part 5: 10 min
- Summary: 5 min

**Preparation Tips:**
- Review all R graphs before lecture
- Test Mermaid diagrams render correctly
- Have backup PDF ready
- Print formula sheet for students
- Prepare whiteboard for calculations
- Have calculator ready
