---
marp: true
theme: default
paginate: true
header: 'Pharmaceutical Compounding & Dispensing'
footer: 'Lesson 2: Pharmaceutical Calculations - A Conceptual Approach'
---

<!-- _class: lead -->

# Lesson 2
# Pharmaceutical Calculations
## A Conceptual Approach

**Based on:**
*Pharmaceutical Calculations: A Conceptual Approach*
by Alison Dering-Anderson

---

## Learning Objectives

After completing this lesson, you will be able to:

1. ✓ Apply dimensional analysis to pharmaceutical calculations
2. ✓ Perform dosage calculations using a conceptual approach
3. ✓ Calculate concentrations and dilutions accurately
4. ✓ Work with percentage strength and ratio strength
5. ✓ Verify calculation results using reasonableness checks
6. ✓ Convert between different units of measurement

---

<!-- _class: lead -->

# The Conceptual Approach

Why Understanding Beats Memorization

---

## Traditional vs. Conceptual Approach

**Traditional Approach:**
1. Memorize formulas
2. Plug in numbers
3. Hope for the right answer
4. ❌ Limited understanding

**Conceptual Approach:**
1. Understand the problem
2. Think through the logic
3. Use dimensional analysis
4. Verify the answer makes sense
5. ✅ Transferable knowledge

---

## Why This Matters

### Patient Safety Depends On:
- **Understanding**, not just calculation
- **Clinical judgment** (is this answer reasonable?)
- **Problem-solving skills** for new situations
- **Confidence** from solid foundation
- **Adaptability** to handle variations

### One Calculation Error Can:
- Cause serious harm to patients
- Result in 10-fold or 100-fold dosing errors
- Lead to treatment failure or toxicity

---

<!-- _class: lead -->

# Dimensional Analysis

The Universal Problem-Solving Tool

---

## What is Dimensional Analysis?

**Also called:**
- Unit factor method
- Factor-label method

**Core Principle:**
Use conversion factors to convert from one unit to another, with units canceling out systematically

**Advantage:**
- No formula memorization needed
- Works for ANY pharmaceutical calculation
- Self-checking (units must work out)
- Reduces errors

---

## Key Principles of Dimensional Analysis

### 1. Units Must Match
You can only add/subtract like units
- ✅ 5 mg + 3 mg = 8 mg
- ❌ 5 mg + 3 mL = ???

### 2. Conversion Factors
Equal quantities in different units
- 1 kg = 1000 g
- 1 L = 1000 mL
- 1 grain = 65 mg

---

## Key Principles (continued)

### 3. Units Cancel
Arrange conversion factors so unwanted units cancel

**Example:**
```
150 lb × (1 kg / 2.2 lb) = 68.2 kg
         ↑
      lb cancels
```

### 4. Final Units
The answer should have the units you need

---

## Basic Example

**Problem:** Convert 150 pounds to kilograms (1 kg = 2.2 lb)

**Setup:**
```
        (1 kg)
150 lb × ────── = ?
        (2.2 lb)
```

**Solution:**
```
150 lb × (1 kg / 2.2 lb) = 68.18 kg
```

**Check:** Pounds cancel, leaving kilograms ✓

---

<!-- _class: lead -->

# Dosage Calculations

The Foundation of Compounding

---

## Basic Dosage Calculation

**Problem:**
A patient needs 20 mg of medication. Available tablets are 10 mg each. How many tablets?

**Conceptual thinking:**
- I need 20 mg total
- Each tablet provides 10 mg
- So I need 20 ÷ 10 = 2 tablets

---

## Basic Dosage - Dimensional Analysis

**Problem:**
A patient needs 20 mg of medication. Available tablets are 10 mg each. How many tablets?

**Solution:**
```
       (1 tablet)
20 mg × ────────  = 2 tablets
        (10 mg)
```

**Notice:** mg cancels, leaving tablets ✓

---

## Weight-Based Dosing

**Problem:**
A medication is dosed at 5 mg/kg. The patient weighs 70 kg. What is the dose?

**Conceptual thinking:**
- For each kilogram, give 5 mg
- Patient weighs 70 kg
- Total dose = 5 mg/kg × 70 kg = 350 mg

---

## Weight-Based Dosing - Dimensional Analysis

**Problem:**
Medication dosed at 5 mg/kg. Patient weighs 70 kg. Calculate dose.

**Solution:**
```
       (5 mg)
70 kg × ──────  = 350 mg
       (1 kg)
```

**Check:** kg cancels, leaving mg ✓

---

## Pediatric Dosing Example

**Problem:**
Child weighs 15 kg, needs amoxicillin at 40 mg/kg/day divided into 3 doses.

Calculate:
a) Total daily dose
b) Dose per administration

---

## Pediatric Dosing - Solution

**a) Total daily dose:**
```
       (40 mg)
15 kg × ────────  = 600 mg/day
       (kg·day)
```

**b) Dose per administration:**
```
   600 mg   (1 day)
   ────── × ────────  = 200 mg per dose
    1 day   (3 doses)
```

**Reasonableness check:**
- 15 kg child ≈ toddler
- 200 mg amoxicillin TID is reasonable ✓

---

<!-- _class: lead -->

# Concentration Calculations

Understanding Drug Amounts in Solutions

---

## What is Concentration?

**Concentration** expresses the amount of drug in a given quantity of product

**Common expressions:**
- mg/mL (mass per volume)
- g/L (grams per liter)
- % (percentage strength)
- Ratio (e.g., 1:1000)

---

## The Concentration Triangle

```
         Amount
          /  \
         /    \
        /      \
Concentration × Volume
```

**Relationships:**
- Amount = Concentration × Volume
- Volume = Amount ÷ Concentration
- Concentration = Amount ÷ Volume

---

## Calculating Quantity from Concentration

**Problem:**
How many mL of a 10 mg/mL solution are needed to provide 75 mg?

**Conceptual thinking:**
- Each mL contains 10 mg
- I need 75 mg
- So I need 75 ÷ 10 = 7.5 mL

---

## Calculating Quantity - Dimensional Analysis

**Problem:**
How many mL of a 10 mg/mL solution are needed to provide 75 mg?

**Solution:**
```
       (1 mL)
75 mg × ──────  = 7.5 mL
       (10 mg)
```

**Check:** mg cancels, leaving mL ✓

---

## Calculating Amount of Drug

**Problem:**
How many mg are in 5 mL of a 25 mg/mL solution?

**Conceptual thinking:**
- Each mL contains 25 mg
- I have 5 mL
- Total = 25 mg/mL × 5 mL = 125 mg

**Dimensional analysis:**
```
      (25 mg)
5 mL × ──────  = 125 mg
      (1 mL)
```

---

<!-- _class: lead -->

# Percentage Strength

A Special Type of Concentration

---

## Three Types of Percentage

### 1. % w/w (weight-in-weight)
- Grams of ingredient in 100 g of product
- Example: 5% w/w = 5 g in 100 g

### 2. % w/v (weight-in-volume)
- Grams of ingredient in 100 mL of product
- Example: 5% w/v = 5 g in 100 mL

### 3. % v/v (volume-in-volume)
- mL of ingredient in 100 mL of product
- Example: 5% v/v = 5 mL in 100 mL

---

## Default Conventions

**When no type is specified, assume:**

- **Solids in liquids:** % w/v
  - Example: 5% hydrocortisone solution = 5 g/100 mL

- **Liquids in liquids:** % v/v
  - Example: 70% alcohol = 70 mL/100 mL

- **Solids in solids:** % w/w
  - Example: 2.5% hydrocortisone cream = 2.5 g/100 g

---

## Percentage Calculation Example

**Problem:**
How many grams of hydrocortisone are in 30 g of 2.5% hydrocortisone cream?

**Conceptual thinking:**
- 2.5% means 2.5 g per 100 g
- I have 30 g of cream
- Amount = (2.5/100) × 30 = 0.75 g

---

## Percentage - Dimensional Analysis

**Problem:**
How many grams of hydrocortisone are in 30 g of 2.5% hydrocortisone cream?

**Solution:**
```
         (2.5 g hydrocortisone)
30 g cream × ─────────────────────  = 0.75 g hydrocortisone
              (100 g cream)
```

**Check:** g cream cancels, leaving g hydrocortisone ✓

---

## Creating a Percentage Solution

**Problem:**
Prepare 200 mL of a 5% w/v solution of drug X.

**Conceptual thinking:**
- 5% w/v means 5 g in 100 mL
- I need 200 mL (which is 2 × 100 mL)
- So I need 2 × 5 g = 10 g

---

## Creating Percentage Solution - Dimensional Analysis

**Problem:**
Prepare 200 mL of a 5% w/v solution.

**Solution:**
```
          (5 g drug)
200 mL × ───────────  = 10 g drug
         (100 mL solution)
```

**Procedure:**
1. Weigh 10 g of drug X
2. Dissolve in sufficient water
3. Bring to final volume of 200 mL

---

<!-- _class: lead -->

# Ratio Strength

Another Way to Express Concentration

---

## Understanding Ratio Strength

**Ratio strength** = 1 part in X parts

**Examples:**
- 1:1000 = 1 g in 1000 mL (w/v)
- 1:1000 = 1 g in 1000 g (w/w)
- 1:1000 = 1 mL in 1000 mL (v/v)

**Common uses:**
- Very dilute solutions
- Epinephrine (1:1000, 1:10,000)
- Antiseptics
- Preservatives

---

## Converting Ratio to Percentage

**Example:** Convert 1:1000 to percentage

**Solution:**
```
1:1000 = 1 g / 1000 mL
       = 0.1 g / 100 mL
       = 0.1% w/v
```

**Quick method:**
```
% = 100 / ratio number
% = 100 / 1000 = 0.1%
```

---

## Converting Percentage to Ratio

**Example:** Convert 0.5% to ratio strength

**Solution:**
```
0.5% = 0.5 g / 100 mL
     = 1 g / 200 mL
     = 1:200
```

**Quick method:**
```
Ratio = 100 / %
Ratio = 100 / 0.5 = 200
So: 1:200
```

---

## Ratio Strength Problem

**Problem:**
How many grams of active ingredient are in 500 mL of a 1:2000 w/v solution?

**Conceptual thinking:**
- 1:2000 means 1 g in 2000 mL
- I have 500 mL (which is 1/4 of 2000 mL)
- So I have 1/4 of 1 g = 0.25 g

---

## Ratio Strength - Dimensional Analysis

**Problem:**
How many grams in 500 mL of 1:2000 solution?

**Solution:**
```
          (1 g)
500 mL × ───────  = 0.25 g
         (2000 mL)
```

**Alternative check:**
```
1:2000 = 0.05% = 0.05 g/100 mL
500 mL × (0.05 g / 100 mL) = 0.25 g ✓
```

---

<!-- _class: lead -->

# Dilution Calculations

Making Solutions Less Concentrated

---

## Fundamental Principle of Dilution

### The amount of active ingredient remains constant

When you dilute:
- Amount of active ingredient = **SAME**
- Total volume = **INCREASES**
- Concentration = **DECREASES**

---

## The Dilution Equation

```
C₁ × V₁ = C₂ × V₂
```

**Where:**
- C₁ = initial concentration
- V₁ = initial volume
- C₂ = final concentration
- V₂ = final volume

**Key:** The product of concentration and volume stays constant

---

## Dilution Problem

**Problem:**
You have 50 mL of a 20% solution. Dilute it to 5%. What is the final volume?

**Using the equation:**
```
C₁ × V₁ = C₂ × V₂
20% × 50 mL = 5% × V₂
1000 = 5% × V₂
V₂ = 1000 / 5 = 200 mL
```

**Interpretation:**
Final volume = 200 mL
Add 150 mL of diluent (200 - 50 = 150)

---

## Conceptual Understanding of Dilution

**Original:**
- 10 g in 100 mL = 10% = 0.1 g/mL

**After adding 100 mL water:**
- Same 10 g, now in 200 mL
- 10 g in 200 mL = 5% = 0.05 g/mL

**Key insight:**
- Amount stayed at 10 g
- Volume doubled (100 → 200 mL)
- Concentration halved (10% → 5%)

---

<!-- _class: lead -->

# Alligation

Mixing Different Concentrations

---

## What is Alligation?

**Alligation** is a method for calculating the quantities of two different concentrations needed to prepare a desired intermediate concentration.

**Use when:**
- You have two stock concentrations
- You need something in between
- You want to avoid waste

**Example scenarios:**
- Mixing 10% and 2% ointments to make 5%
- Combining different % alcohol solutions
- Adjusting cream strengths

---

## The Alligation Grid

```
     Higher %  ────┐
                   ├──> Desired %
     Lower %   ────┘
```

**The trick:**
- Difference between Desired and Lower = Parts of Higher
- Difference between Higher and Desired = Parts of Lower

**(Cross-diagonal differences!)**

---

## Alligation Example - Setup

**Problem:**
Prepare 100 g of 5% ointment using 10% and 2% ointments.

**Step 1: Set up grid**
```
10% (higher)
             5% (desired)
2% (lower)
```

---

## Alligation Example - Calculate Parts

**Step 2: Calculate differences (cross-diagonal)**

```
10% ───── (5 - 2) = 3 parts of 10%
      ╲  ╱
       5%
      ╱  ╲
2%  ───── (10 - 5) = 5 parts of 2%
```

**Step 3: Total parts**
```
3 + 5 = 8 total parts
```

---

## Alligation Example - Final Calculation

**Step 4: Calculate quantities**

```
10% ointment: (3 parts / 8 total parts) × 100 g = 37.5 g

2% ointment:  (5 parts / 8 total parts) × 100 g = 62.5 g
```

**Verification:**
```
(37.5 g × 10%) + (62.5 g × 2%) = 3.75 g + 1.25 g
                                = 5.0 g active in 100 g
                                = 5% ✓
```

---

<!-- _class: lead -->

# Common Conversions

Units You Must Know

---

## Weight Conversions

**Metric:**
- 1 kg = 1000 g
- 1 g = 1000 mg
- 1 mg = 1000 mcg (or μg)

**Between systems:**
- 1 kg = 2.2 lb (pounds)
- 1 grain = 65 mg

**Remember:**
- mcg and μg are the SAME
- Use "mcg" to avoid errors (μg can be misread)

---

## Volume Conversions

**Metric:**
- 1 L = 1000 mL
- 1 mL = 1 cm³ (cc) *[avoid using "cc"]*

**Household measures:**
- 1 teaspoon (tsp) = 5 mL
- 1 tablespoon (tbsp) = 15 mL
- 1 fluid ounce (fl oz) = 30 mL (approximately)

**For IV calculations:**
- 1 drop factor varies (10, 15, 20, 60 drops/mL)

---

## Temperature Conversions

**Fahrenheit to Celsius:**
```
°C = (°F - 32) × 5/9
```

**Celsius to Fahrenheit:**
```
°F = (°C × 9/5) + 32
```

**Common values:**
- Body temp: 37°C = 98.6°F
- Room temp: 20-25°C = 68-77°F
- Refrigerator: 2-8°C = 36-46°F

---

<!-- _class: lead -->

# Avoiding Calculation Errors

Safety Through Accuracy

---

## Common Errors

### 1. Decimal Point Errors (MOST DANGEROUS!)
- 10 mg vs 100 mg = 10-fold error
- 0.5 mg vs 5 mg = 10-fold error
- Can be fatal!

### 2. Unit Confusion
- mg vs g (1000-fold difference!)
- mg vs mcg (1000-fold difference!)
- mL vs L (1000-fold difference!)

### 3. Calculation Errors
- Wrong formula or approach
- Arithmetic mistakes
- Inverting fractions

---

## Common Errors (continued)

### 4. Transcription Errors
- Copying wrong number from prescription
- Misreading handwriting
- Transposing digits (25 vs 52)

### 5. Misinterpretation
- Reading prescription incorrectly
- Confusing drug names
- Wrong patient

---

## Error Prevention Strategies

### ✓ Write out all steps clearly
- Show your work
- Don't do mental math for critical calculations

### ✓ Include units in every step
- Use dimensional analysis
- Units help catch errors

### ✓ Use dimensional analysis consistently
- No need to memorize multiple formulas
- Built-in error checking

---

## Error Prevention (continued)

### ✓ Double-check your math
- Use calculator
- Check calculation twice
- Have another person verify

### ✓ Perform reasonableness check
- Does this answer make sense?
- Is it within normal range?
- Would this be safe for the patient?

### ✓ Be extra careful with high-alert medications
- Insulin, heparin, chemotherapy
- Pediatric doses
- Concentrated electrolytes

---

## The Reasonableness Check

**Always ask yourself:**

❓ Does this answer make sense?
❓ Is it within the expected range?
❓ Would this dose be safe for the patient?
❓ Are the units correct?
❓ Am I off by a factor of 10? 100? 1000?

**Example:**
If you calculate a dose of 50,000 mg for a child, that should trigger immediate review - it's likely an error!

---

<!-- _class: lead -->

# Practice Problems

Test Your Understanding

---

## Problem 1: Basic Dosage

**Question:**
A patient needs 15 mg of drug. Available: 5 mg tablets. How many tablets?

---

## Problem 1: Solution

**Answer:**
```
       (1 tablet)
15 mg × ─────────  = 3 tablets
        (5 mg)
```

**Reasonableness check:**
- 15 ÷ 5 = 3 ✓
- 3 tablets is a reasonable number ✓

---

## Problem 2: Weight-Based Dosing

**Question:**
Calculate the dose for a 65 kg adult if the medication is dosed at 10 mg/kg/day.

---

## Problem 2: Solution

**Answer:**
```
       (10 mg)
65 kg × ────────  = 650 mg/day
       (kg·day)
```

**Reasonableness check:**
- Adult patient, 650 mg/day seems reasonable ✓
- Not too high, not too low ✓

---

## Problem 3: Concentration

**Question:**
How many mL of a 40 mg/mL solution are needed to provide 180 mg?

---

## Problem 3: Solution

**Answer:**
```
        (1 mL)
180 mg × ──────  = 4.5 mL
        (40 mg)
```

**Reasonableness check:**
- 180 ÷ 40 = 4.5 ✓
- 4.5 mL is a measurable volume ✓

---

## Problem 4: Percentage Strength

**Question:**
How many grams of drug are needed to prepare 250 g of 3% ointment?

---

## Problem 4: Solution

**Answer:**
```
           (3 g drug)
250 g ointment × ─────────────  = 7.5 g drug
                (100 g ointment)
```

**Reasonableness check:**
- 3% of 250 = 7.5 ✓
- Will need 242.5 g of base ✓

---

## Problem 5: Dilution

**Question:**
You have 20 mL of 50% solution. What is the final volume if diluted to 10%?

---

## Problem 5: Solution

**Answer:**
Using C₁V₁ = C₂V₂:
```
50% × 20 mL = 10% × V₂
1000 = 10% × V₂
V₂ = 100 mL
```

**Amount to add:** 100 - 20 = 80 mL diluent

**Reasonableness check:**
- Concentration drops 5-fold (50% → 10%)
- Volume increases 5-fold (20 → 100 mL) ✓

---

<!-- _class: lead -->

# Key Takeaways

What You Must Remember

---

## Summary Points

1. **Understanding > Memorization**
   - Conceptual approach beats rote formulas

2. **Dimensional Analysis is Your Friend**
   - Works for all calculations
   - Built-in error checking

3. **Always Include Units**
   - In every step of calculation
   - Units help catch errors

---

## Summary Points (continued)

4. **Double-Check Everything**
   - Critical calculations verified twice
   - Have someone else check

5. **Reasonableness Checks Save Lives**
   - Does this answer make sense?
   - Is it safe for this patient?

6. **Decimal Points are Dangerous**
   - Most common source of serious errors
   - Be extra careful!

---

## Clinical Pearls

💡 **When in doubt, write it out**
- Don't do complex mental math
- Show your work

💡 **If it doesn't make sense, it's probably wrong**
- Trust your clinical judgment
- Investigate discrepancies

💡 **Slow down with calculations**
- Speed causes errors
- Accuracy is more important than speed

💡 **Use technology appropriately**
- Calculator for arithmetic
- But understand the concepts!

---

<!-- _class: lead -->

# Next Steps

---

## Homework Assignment

**Practice Calculations:**
1. Complete 20 practice problems (provided handout)
2. Show all work using dimensional analysis
3. Include reasonableness checks
4. Bring questions to next class

**Prepare for Lesson 3:**
- Review solubility concepts
- Think about liquid medications you've encountered
- Consider challenges in making solutions/suspensions

---

## Resources

**Primary Reference:**
- Dering-Anderson AM. *Pharmaceutical Calculations: A Conceptual Approach*. Chapters 1-10

**Additional Practice:**
- Shargel L, Yu ABC. *Applied Biopharmaceutics & Pharmacokinetics*
- Ansel HC. *Pharmaceutical Calculations Workbook*

**Online Resources:**
- Pharmacy calculation practice websites
- Mobile apps for practice

---

## Coming Up Next

**Lesson 3: Liquid Dosage Forms - Solutions and Suspensions**

Topics:
- Solutions (syrups, elixirs)
- Suspensions
- Levigation techniques
- Quality control for liquids
- Hands-on compounding!

**Bring:**
- Calculator
- Lab coat
- Questions about calculations

---

<!-- _class: lead -->

# Questions?

**Remember:**
*Accuracy in calculations = Safety for patients*

*When in doubt, check it out!*

---

<!-- _class: lead -->

# Practice Makes Perfect!

**Keep calculating, keep checking, keep learning**

See you in Lesson 3!

---

## Quick Reference Card

**Common Conversions:**
- 1 kg = 2.2 lb
- 1 g = 1000 mg
- 1 mg = 1000 mcg
- 1 L = 1000 mL
- 1 tsp = 5 mL
- 1 tbsp = 15 mL

**Key Formulas:**
- C₁V₁ = C₂V₂ (dilution)
- % = (parts / 100 total parts)
- Ratio % = 100 / ratio number

**Remember:** Use dimensional analysis for everything!
