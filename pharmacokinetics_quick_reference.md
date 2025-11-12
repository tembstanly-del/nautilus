# Pharmacokinetics Quick Reference Guide
## Essential Formulas, Concepts & Clinical Applications

**For:** Introduction to Pharmacokinetics Course
**Resource:** Based on Boomer.org PHAR 7632 Syllabus

---

## Core Definition

**Pharmacokinetics (PK):** What the BODY does to the DRUG
- Movement of drug through the body over time
- Determines dose, frequency, route of administration

**Pharmacodynamics (PD):** What the DRUG does to the BODY
- Drug effects and mechanisms of action

---

## ADME Framework

| Process | Definition | Factors Affecting |
|---------|-----------|-------------------|
| **A**bsorption | Drug enters bloodstream | Route, formulation, GI pH, food, first-pass |
| **D**istribution | Drug disperses through body | Blood flow, protein binding, lipophilicity, Vd |
| **M**etabolism | Drug is chemically transformed | Liver function, CYP enzymes, drug interactions |
| **E**xcretion | Drug is removed from body | Renal function, biliary excretion, pH |

---

## Essential PK Parameters

### 1. Volume of Distribution (Vd)

**Formula:**
```
Vd = Dose / C₀
```

**Units:** Liters (L) or L/kg

**Interpretation:**
- **5-15 L:** Drug confined to plasma (high protein binding)
  - Example: Warfarin (~8 L)
- **15-50 L:** Extracellular fluid distribution
  - Example: Many antibiotics
- **>50 L:** Extensive tissue distribution
  - Example: Digoxin (~500 L), Amiodarone (~5000 L)

**Clinical Use:**
- Calculate loading doses: **LD = Vd × Ctarget**
- Vd > total body water → extensive tissue binding
- Affected by: edema, obesity, age, pregnancy

---

### 2. Clearance (Cl)

**Formulas:**
```
Cl = k × Vd
Cl = Dose / AUC
Cl = Cltotal = Clrenal + Clhepatic + Clother
```

**Units:** L/h, mL/min, L/h/kg

**Interpretation:**
- Volume of plasma completely cleared of drug per unit time
- Measure of elimination efficiency
- Independent of dose for first-order kinetics

**Typical Values:**
- Renal blood flow: ~1200 mL/min
- Hepatic blood flow: ~1500 mL/min
- Glomerular filtration rate: ~125 mL/min

**Clinical Use:**
- Calculate maintenance dose/infusion rate: **R₀ = Css × Cl**
- Adjust for organ dysfunction
- Monitor in renal/hepatic disease

---

### 3. Elimination Rate Constant (k)

**Formulas:**
```
k = Cl / Vd
k = 0.693 / t½
```

**Units:** h⁻¹ (per hour) or min⁻¹

**Interpretation:**
- Fraction of drug eliminated per unit time
- First-order: constant fraction eliminated
- Zero-order: constant amount eliminated (rare)

---

### 4. Half-Life (t½)

**Formulas:**
```
t½ = 0.693 / k
t½ = (0.693 × Vd) / Cl
```

**Units:** Hours, minutes, days

**Interpretation:**
- Time for concentration to decrease by 50%
- Independent of dose (first-order kinetics)

**The "5 Half-Lives" Rule:**
- **Time to steady-state:** ~5 × t½ (97% complete)
- **Time to eliminate:** ~5 × t½ (97% eliminated)

**Clinical Examples:**
| Drug | Half-Life | Dosing Frequency |
|------|-----------|------------------|
| Gentamicin | 2-3 h | Every 8-24h (depends on regimen) |
| Digoxin | 36-48 h | Once daily |
| Amiodarone | 40-60 days | Once daily (loading phase different) |
| Warfarin | 40 h | Once daily |

**Factors Affecting t½:**
- Changes in Cl (renal/hepatic disease)
- Changes in Vd (edema, obesity)
- Drug interactions

---

### 5. Bioavailability (F)

**Formula:**
```
F = (AUC_oral × Dose_IV) / (AUC_IV × Dose_oral)

Dose_oral = Dose_IV / F
```

**Units:** Fraction (0-1) or Percentage (0-100%)

**Interpretation:**
- Fraction of dose reaching systemic circulation
- IV always F = 1.0 (100%)
- Oral F reduced by incomplete absorption + first-pass metabolism

**Clinical Examples:**
| Drug | Oral F | Reason for Low F |
|------|--------|------------------|
| Morphine | ~25% | Extensive first-pass metabolism |
| Nitroglycerin | <1% | Almost complete first-pass |
| Propranolol | ~25% | Hepatic first-pass |
| Amoxicillin | ~80% | Good absorption |
| Levothyroxine | 40-80% | Variable absorption |

**Factors Reducing F:**
- First-pass hepatic metabolism
- Incomplete absorption
- Drug degradation in GI tract
- Efflux transporters (P-glycoprotein)

---

## Key Equations Reference

### IV Bolus Administration

**Concentration vs Time (First-Order):**
```
C(t) = C₀ × e^(-k×t)
```

**Logarithmic Form:**
```
ln(C) = ln(C₀) - k×t
```

**Using Half-Lives:**
```
C(t) = C₀ × (0.5)^n

where n = number of half-lives = t / t½
```

**Fraction Remaining:**
| Time | Fraction Remaining | % Remaining |
|------|-------------------|-------------|
| 1 t½ | 1/2 | 50% |
| 2 t½ | 1/4 | 25% |
| 3 t½ | 1/8 | 12.5% |
| 4 t½ | 1/16 | 6.25% |
| 5 t½ | 1/32 | 3.125% |

---

### IV Infusion (Continuous)

**Steady-State Concentration:**
```
Css = R₀ / Cl

where R₀ = infusion rate (mass/time)
```

**Concentration vs Time (during infusion):**
```
C(t) = Css × (1 - e^(-k×t))
```

**Approach to Steady-State:**
| Time | % of Css Achieved |
|------|------------------|
| 1 t½ | 50% |
| 2 t½ | 75% |
| 3 t½ | 87.5% |
| 4 t½ | 93.75% |
| 5 t½ | 96.9% |

---

### Loading Dose

**Formula:**
```
Loading Dose (LD) = Vd × Ctarget

Maintenance Rate = Cl × Ctarget
```

**When to Use:**
- Long half-life drugs (t½ > 12-24h)
- Need rapid therapeutic effect
- Examples: Digoxin, phenytoin, some antibiotics

**Caution:**
- Risk of toxicity if Vd over-estimated
- May need to reduce if organ dysfunction

---

### Oral Administration

**Dose Adjustment for F:**
```
Dose_oral = (Dose_IV / F) × (desired AUC ratio)
```

**Peak Concentration (Cmax):**
- Occurs at Tmax
- Lower than IV C₀ for same dose
- Affected by absorption rate

---

## Kinetic Orders

### First-Order Kinetics (MOST COMMON)

**Characteristics:**
- Constant FRACTION eliminated per time
- Exponential decay
- Half-life is constant
- Linear on semi-log plot
- Rate proportional to concentration: Rate = k × C

**Equation:**
```
C(t) = C₀ × e^(-k×t)
```

**Examples:** Almost all drugs at therapeutic doses

---

### Zero-Order Kinetics (RARE)

**Characteristics:**
- Constant AMOUNT eliminated per time
- Linear decay on regular plot
- Half-life changes with concentration
- Elimination mechanism saturated
- Rate is constant: Rate = constant (Vmax)

**Equation:**
```
C(t) = C₀ - (k₀ × t)

where k₀ = elimination rate (mass/time)
```

**Clinical Examples:**
- **Ethanol** (alcohol) at moderate-high doses
- **Phenytoin** at therapeutic doses
- **Aspirin** at high doses
- **Heparin** (complex)

**Clinical Significance:**
- Small dose increase → large concentration increase
- Increased risk of toxicity
- Requires careful monitoring

---

## Compartment Models

### One-Compartment Model

**Assumptions:**
- Instantaneous distribution throughout body
- Uniform drug concentration in all tissues
- Single exponential decline

**Diagram:**
```
Dose → [Central Compartment] → Elimination
         Volume = Vd
```

**Best For:**
- IV bolus with rapid distribution
- Simplest model
- Many drugs approximate this

**Limitation:**
- Doesn't account for distribution phase

---

### Multi-Compartment Models

**Two-Compartment:**
- Central + peripheral compartment
- Bi-exponential decline (α and β phases)
- More realistic for many drugs

**Three+ Compartments:**
- Even more complex distribution
- Multiple tissue compartments

**Note:** Advanced topic - not covered in intro lecture

---

## Clinical Applications

### Therapeutic Drug Monitoring (TDM)

**When to Monitor:**
- Narrow therapeutic index
- Significant toxicity risk
- Variable pharmacokinetics
- Confirming compliance

**Common Drugs Monitored:**
| Drug | Therapeutic Range | Sample Timing |
|------|------------------|---------------|
| Gentamicin | Peak: 5-10 mg/L, Trough: <2 mg/L | Peak: 30 min post, Trough: pre-dose |
| Vancomycin | Trough: 10-20 mg/L | Pre-4th or 5th dose |
| Digoxin | 0.5-2 ng/mL | >6h post-dose |
| Phenytoin | 10-20 mg/L | Trough (pre-dose) |
| Lithium | 0.6-1.2 mEq/L | 12h post-dose |
| Theophylline | 10-20 mg/L | Trough or mid-interval |

---

### Dose Adjustments

#### Renal Impairment

**For renally eliminated drugs:**
```
Dose_new = Dose_normal × (CrCl_patient / CrCl_normal)

Or extend interval proportionally
```

**Creatinine Clearance (CrCl) Estimation:**
```
Cockcroft-Gault:
CrCl (mL/min) = [(140 - age) × Weight (kg) × (0.85 if female)] / (72 × SCr)
```

**Examples Needing Adjustment:**
- Aminoglycosides (gentamicin, tobramycin)
- Vancomycin
- Many beta-lactams
- Gabapentin
- Enoxaparin

---

#### Hepatic Impairment

**For hepatically metabolized drugs:**
- No simple formula like renal
- Use Child-Pugh score
- Generally reduce dose by 25-50%
- Monitor closely

**Examples Needing Adjustment:**
- Warfarin
- Most benzodiazepines
- Opioids
- Propranolol

---

#### Obesity

**Dosing Weight Considerations:**
| Parameter | Weight to Use |
|-----------|--------------|
| Hydrophilic drugs (small Vd) | Ideal Body Weight (IBW) |
| Lipophilic drugs (large Vd) | Total Body Weight (TBW) |
| Compromise | Adjusted Body Weight (ABW) |

```
IBW (male) = 50 kg + 2.3 kg per inch over 5 feet
IBW (female) = 45.5 kg + 2.3 kg per inch over 5 feet

ABW = IBW + 0.4 × (TBW - IBW)
```

---

#### Elderly

**Changes with Aging:**
- ↓ Renal function (even with normal SCr)
- ↓ Lean body mass
- ↓ Hepatic blood flow
- ↑ Body fat percentage
- ↓ Albumin (affects protein binding)

**General Approach:**
- "Start low, go slow"
- Use lower end of dosing range
- Monitor for adverse effects
- Calculate CrCl (don't rely on SCr alone)

---

#### Pediatrics

**Age-Related Changes:**
- Neonates: Immature metabolism and excretion
- Infants: Rapidly changing body composition
- Children: Different body proportions

**Dosing:**
- Usually weight-based (mg/kg)
- Sometimes BSA-based (mg/m²)
- Never simply scale adult doses!

---

## Problem-Solving Approach

### Step-by-Step for PK Problems:

**1. Identify What's Given:**
- List all parameters provided
- Note units

**2. Identify What's Asked:**
- What do you need to calculate?

**3. Select Appropriate Formula:**
- Match the scenario to the right equation

**4. Check Units:**
- Convert if necessary
- Common conversions:
  - 1 L = 1000 mL
  - 1 h = 60 min
  - ln(2) = 0.693

**5. Calculate:**
- Show your work
- Keep track of units

**6. Check Reasonableness:**
- Does the answer make sense clinically?
- Is Vd reasonable (usually 5-500 L)?
- Is t½ reasonable (minutes to days)?
- Is clearance reasonable (<1500 mL/min)?

---

## Common Conversions & Constants

**Mathematical Constants:**
- ln(2) = 0.693
- e = 2.718

**Time:**
- 1 hour = 60 minutes
- 1 day = 24 hours = 1440 minutes

**Volume:**
- 1 L = 1000 mL
- 1 dL = 100 mL = 0.1 L

**Concentration:**
- 1 mg/L = 1 mcg/mL = 1 μg/mL
- 1 g/dL = 10 g/L = 10,000 mg/L

**Body Water Compartments (70 kg adult):**
- Total body water: ~42 L (60% of weight)
- Extracellular fluid: ~14 L (20%)
- Plasma volume: ~3 L (4%)
- Blood volume: ~5 L (7%)

---

## Important Clinical Pearls

### General Principles:
1. **Most drugs follow first-order kinetics**
2. **Steady-state takes ~5 half-lives to achieve**
3. **Clearance determines maintenance dose**
4. **Vd determines loading dose**
5. **Half-life determines dosing interval**

### Red Flags:
⚠️ **Narrow Therapeutic Index Drugs** - Small difference between therapeutic and toxic levels:
- Warfarin, digoxin, lithium, phenytoin, theophylline, aminoglycosides

⚠️ **Saturable Kinetics** - Can switch to zero-order:
- Phenytoin, aspirin, ethanol

⚠️ **Highly Protein Bound** - Interactions affect free drug:
- Warfarin (99%), phenytoin (90%), valproic acid (90%)

⚠️ **Renally Eliminated** - Adjust in renal impairment:
- Aminoglycosides, vancomycin, gabapentin, lithium

⚠️ **Hepatically Eliminated** - Adjust in liver disease:
- Most benzodiazepines, warfarin, phenytoin

### Tips for Success:
✓ Always include units in calculations
✓ Draw concentration-time curves to visualize
✓ Check if assumptions of one-compartment model are reasonable
✓ Consider patient-specific factors (age, organ function, weight)
✓ Remember: PK tells you the CONCENTRATION, PD tells you the EFFECT
✓ When in doubt, consult drug references and clinical pharmacist

---

## Practice Problem Template

**Given Information:**
- [List parameters]

**Find:**
- [What you're solving for]

**Relevant Formula:**
- [Write equation]

**Calculation:**
- [Show work step-by-step]

**Answer:**
- [Final answer with units]

**Clinical Interpretation:**
- [What does this mean for the patient?]

---

## Additional Resources

### Boomer.org Chapters (www.boomer.org/c/p4):
- **Chapter 3:** Pharmacokinetic Fundamentals - Essential reading
- **Chapter 4:** One-Compartment IV Bolus - Core concepts
- **Chapter 5:** Derived Parameters (Vd, Cl, t½) - Important
- **Chapter 6:** IV Infusion - Clinical applications
- **Chapter 7-8:** Oral Administration & Bioavailability
- **Full Syllabus:** https://www.boomer.org/c/p4/syllabus.html

### Interactive Tools:
- Boomer.org calculators (throughout chapters)
- PK/PD simulation software
- Concentration-time curve generators

### Reference Texts:
- Rowland & Tozer: "Clinical Pharmacokinetics and Pharmacodynamics"
- Winter: "Basic Clinical Pharmacokinetics"
- Shargel & Yu: "Applied Biopharmaceutics & Pharmacokinetics"

### Online Resources:
- FDA drug labels (DailyMed)
- Clinical pharmacology databases (Lexicomp, Micromedex)
- PubMed for primary literature

---

## Study Checklist

Before the exam, make sure you can:

□ Define pharmacokinetics and explain ADME
□ Calculate Vd from dose and C₀
□ Calculate clearance from k and Vd, or from Dose/AUC
□ Calculate half-life from k
□ Interconvert between k, Cl, Vd, and t½
□ Use C(t) = C₀ × e^(-k×t) or half-life method
□ Calculate steady-state concentration from infusion rate
□ Calculate loading dose from Vd and target concentration
□ Calculate maintenance infusion rate from Cl and target Css
□ Determine bioavailability from AUC data
□ Adjust doses for renal impairment
□ Distinguish between first-order and zero-order kinetics
□ Interpret concentration-time curves
□ Apply the "5 half-lives rule"
□ Solve integrated clinical cases

---

## Quick Formula Summary Card

**Cut out and keep this section as a study card:**

```
┌─────────────────────────────────────────────────────────┐
│         PHARMACOKINETICS FORMULA CARD                   │
├─────────────────────────────────────────────────────────┤
│ Vd = Dose / C₀                                         │
│                                                         │
│ Cl = k × Vd = Dose / AUC                              │
│                                                         │
│ k = Cl / Vd = 0.693 / t½                              │
│                                                         │
│ t½ = 0.693 / k = (0.693 × Vd) / Cl                   │
│                                                         │
│ C(t) = C₀ × e^(-k×t) = C₀ × (0.5)^(t/t½)            │
│                                                         │
│ Css = R₀ / Cl                                          │
│                                                         │
│ Loading Dose = Vd × Ctarget                            │
│                                                         │
│ F = (AUC_oral × Dose_IV) / (AUC_IV × Dose_oral)       │
│                                                         │
│ Time to Steady-State ≈ 5 × t½                         │
│                                                         │
│ ADME: Absorption, Distribution, Metabolism, Excretion  │
└─────────────────────────────────────────────────────────┘
```

---

**Document Version:** 1.0
**Last Updated:** 2025-11-12

**Good luck with your studies!**

*Remember: Pharmacokinetics is the foundation for rational drug therapy. Understanding these principles will make you a better clinician!*
