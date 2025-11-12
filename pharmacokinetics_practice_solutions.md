# Pharmacokinetics Practice Problems - SOLUTIONS
## Introduction to Pharmacokinetics - Answer Key

---

## Section 1: Volume of Distribution (Vd)

### Problem 1.1 - SOLUTION
**Given:**
- Dose = 500 mg
- C₀ = 12.5 mg/L

**Formula:** Vd = Dose / C₀

**Calculation:**
Vd = 500 mg / 12.5 mg/L = **40 L**

**Interpretation:** This drug distributes beyond plasma into extracellular fluid and possibly tissues.

---

### Problem 1.2 - SOLUTION
**Given:** Digoxin Vd = 500 L (in 70 kg patient)

**a)** Yes, 500 L is MUCH larger than total body water (~42 L)

**b)** This indicates extensive tissue binding. Digoxin binds strongly to muscle tissue (especially cardiac muscle), which explains why the apparent volume is so large. The drug is not actually in 500 L of fluid; rather, much of it is bound to tissues, making it seem like a larger volume when calculating from plasma concentrations.

**Clinical Significance:**
- Loading doses must be large
- Takes long time to eliminate
- Hemodialysis ineffective (drug not in blood)

---

### Problem 1.3 - SOLUTION
**Given:**
- Same dose: 1000 mg
- Patient A: C₀ = 50 mg/L
- Patient B: C₀ = 25 mg/L

**a) Calculate Vd:**

Patient A: Vd = 1000 mg / 50 mg/L = **20 L**
Patient B: Vd = 1000 mg / 25 mg/L = **40 L**

**b) Which has greater tissue distribution?**

**Patient B** has greater tissue distribution (larger Vd). The same dose resulted in lower plasma concentration because more drug distributed out of plasma into tissues.

**Clinical Implications:**
- Patient B might need higher doses to achieve same plasma levels
- Differences could be due to body composition, disease state, or drug interactions

---

## Section 2: Half-Life (t½) and Elimination

### Problem 2.1 - SOLUTION
**Given:** k = 0.231 h⁻¹

**Formula:** t½ = 0.693 / k

**Calculation:**
t½ = 0.693 / 0.231 h⁻¹ = **3 hours**

---

### Problem 2.2 - SOLUTION
**Given:**
- C₀ = 80 mg/L
- t½ = 3 hours

**Method 1 - Using half-lives:**
After each half-life, concentration halves:
- **t = 3h (1 half-life):** C = 80 × 0.5 = **40 mg/L**
- **t = 6h (2 half-lives):** C = 80 × 0.5² = **20 mg/L**
- **t = 9h (3 half-lives):** C = 80 × 0.5³ = **10 mg/L**
- **t = 15h (5 half-lives):** C = 80 × 0.5⁵ = **2.5 mg/L**

**Method 2 - Using exponential equation:**
First find k: k = 0.693 / 3h = 0.231 h⁻¹
Then use: C(t) = C₀ × e^(-k×t)

For t = 15h:
C(15) = 80 × e^(-0.231 × 15) = 80 × e^(-3.465) = 80 × 0.031 = 2.5 mg/L ✓

---

### Problem 2.3 - SOLUTION
**Given:** t½ = 8 hours

**a) Time to steady-state:**
Time = **5 × t½ = 5 × 8h = 40 hours**

At this point, ~97% of steady-state achieved

**b) Time to eliminate 95%:**
After 5 half-lives, 3.125% remains (96.875% eliminated)
Time = **5 × t½ = 40 hours**

**Key Concept:** The "5 half-lives rule" applies to both reaching steady-state and elimination.

---

## Section 3: Clearance (Cl)

### Problem 3.1 - SOLUTION
**Given:**
- Vd = 50 L
- k = 0.139 h⁻¹

**Formula:** Cl = k × Vd

**Calculation:**
Cl = 0.139 h⁻¹ × 50 L = **6.95 L/h**

**Alternative units:**
6.95 L/h ÷ 60 min/h = 0.116 L/min = **116 mL/min**

---

### Problem 3.2 - SOLUTION
**Given:**
- Dose = 750 mg
- AUC = 150 mg·h/L

**Formula:** Cl = Dose / AUC

**Calculation:**
Cl = 750 mg / 150 mg·h/L = **5 L/h**

**Note:** This method doesn't require knowing Vd or k. AUC represents total drug exposure.

---

### Problem 3.3 - SOLUTION
**Given:**
- Normal total Cl = 120 mL/min
- Renal Cl = 80% of total = 96 mL/min
- Non-renal Cl = 20% of total = 24 mL/min
- Renal function drops to 10%

**Calculation:**
New renal Cl = 96 mL/min × 0.10 = 9.6 mL/min
Non-renal Cl = 24 mL/min (unchanged)
**New total Cl = 9.6 + 24 = 33.6 mL/min**

**Dose Adjustment:**
Dose should be reduced to: (33.6 / 120) × 100% = **28% of normal dose**

**Clinical Decision:** Could give:
- 25-30% of normal dose at same interval, OR
- Normal dose but extend interval to every 3-4 times normal

---

## Section 4: IV Infusion and Steady-State

### Problem 4.1 - SOLUTION
**Given:**
- R₀ = 50 mg/h
- Cl = 5 L/h

**Formula:** Css = R₀ / Cl

**Calculation:**
Css = 50 mg/h / 5 L/h = **10 mg/L**

**Concept Check:** At steady-state, infusion rate equals elimination rate (Cl × Css)

---

### Problem 4.2 - SOLUTION
**Given:**
- Target Css = 15 mg/L
- Cl = 2.5 L/h

**Formula:** R₀ = Css × Cl

**Calculation:**
R₀ = 15 mg/L × 2.5 L/h = **37.5 mg/h**

**Practical:** Could give as 900 mg/day continuous infusion

---

### Problem 4.3 - SOLUTION
**Given:**
- Target Css = 10 mg/L
- Vd = 40 L
- Cl = 4 L/h
- t½ = 6.93 hours

**a) Loading dose:**
LD = Vd × Ctarget = 40 L × 10 mg/L = **400 mg**

**b) Maintenance infusion rate:**
R₀ = Css × Cl = 10 mg/L × 4 L/h = **40 mg/h**

**c) Time to 95% Css without loading dose:**
This occurs at ~4.3 half-lives (ln(1/0.05) / ln(2) = 4.3)
Time = 4.3 × 6.93h ≈ **30 hours**

Or use the simpler "5 half-lives to ~97%" rule: **~35 hours**

**Clinical Decision:** Loading dose saves ~30 hours to achieve therapeutic levels!

---

## Section 5: Relating Vd, Cl, k, and t½

### Problem 5.1 - SOLUTION
**Given:**
- Vd = 35 L
- Cl = 3.5 L/h

**a) Elimination rate constant:**
k = Cl / Vd = 3.5 L/h / 35 L = **0.1 h⁻¹**

**b) Half-life:**
t½ = 0.693 / k = 0.693 / 0.1 h⁻¹ = **6.93 hours**

**Alternative for (b):**
t½ = (0.693 × Vd) / Cl = (0.693 × 35 L) / 3.5 L/h = 6.93 hours ✓

---

### Problem 5.2 - SOLUTION
**Given:**
- Vd = 60 L
- t½ = 12 hours

**a) Elimination rate constant:**
k = 0.693 / t½ = 0.693 / 12h = **0.05775 h⁻¹**

**b) Clearance:**
Cl = k × Vd = 0.05775 h⁻¹ × 60 L = **3.465 L/h**

**Alternative for (b):**
Cl = (0.693 × Vd) / t½ = (0.693 × 60 L) / 12h = 3.465 L/h ✓

**Key Relationships to Remember:**
- k = Cl / Vd = 0.693 / t½
- Cl = k × Vd = (0.693 × Vd) / t½
- t½ = 0.693 / k = (0.693 × Vd) / Cl

---

## Section 6: Bioavailability

### Problem 6.1 - SOLUTION
**Given:**
- IV: Dose = 100 mg, AUC = 50 mg·h/L
- Oral: Dose = 200 mg, AUC = 60 mg·h/L

**Formula:** F = (AUC_oral × Dose_IV) / (AUC_IV × Dose_oral)

**Calculation:**
F = (60 mg·h/L × 100 mg) / (50 mg·h/L × 200 mg)
F = 6000 / 10000 = **0.6 or 60%**

**Interpretation:** Only 60% of oral dose reaches systemic circulation. 40% is lost to first-pass metabolism and/or incomplete absorption.

---

### Problem 6.2 - SOLUTION
**Given:**
- F = 0.25 (25%)
- Amount needed systemically = 10 mg

**Formula:** Dose_oral = Amount needed / F

**Calculation:**
Dose_oral = 10 mg / 0.25 = **40 mg**

**Clinical Context:** This is why oral morphine doses are much higher than IV doses. If a patient needs 10 mg IV morphine, they would need approximately 40 mg orally.

---

### Problem 6.3 - SOLUTION
**Given:**
- IV dose: 50 mg twice daily (F = 1.0)
- Oral F = 0.4 (40%)

**Formula:** Dose_oral = Dose_IV / F

**Calculation:**
Dose_oral = 50 mg / 0.4 = **125 mg twice daily**

**Verification:**
- IV: 50 mg × 1.0 = 50 mg reaches circulation
- Oral: 125 mg × 0.4 = 50 mg reaches circulation ✓

**Clinical Note:** Must give 2.5 times the IV dose when switching to oral route.

---

## Section 7: Integrated Problems

### Problem 7.1 - SOLUTION (Gentamicin)
**Given:**
- Weight = 70 kg
- Vd = 0.25 L/kg
- t½ = 2 hours
- Target Cmax = 8 mg/L

**a) Total Vd:**
Vd = 0.25 L/kg × 70 kg = **17.5 L**

**b) Elimination rate constant:**
k = 0.693 / t½ = 0.693 / 2h = **0.347 h⁻¹**

**c) Clearance:**
Cl = k × Vd = 0.347 h⁻¹ × 17.5 L = **6.07 L/h** or **101 mL/min**

**d) Dose for Cmax = 8 mg/L:**
Dose = Vd × Ctarget = 17.5 L × 8 mg/L = **140 mg**

**e) Time to drop to 2 mg/L:**
C(t) = C₀ × e^(-k×t)
2 = 8 × e^(-0.347×t)
0.25 = e^(-0.347×t)
ln(0.25) = -0.347×t
-1.386 = -0.347×t
t = **4 hours**

**Alternative method:** From 8 to 2 mg/L is 2 half-lives (8→4→2)
Time = 2 × 2h = **4 hours** ✓

**Clinical Application:** Could dose 140 mg every 8 hours (concentration cycles between 8 and 1 mg/L)

---

### Problem 7.2 - SOLUTION (Theophylline)
**Given:**
- Vd = 30 L
- Cl = 2.8 L/h
- Target Css = 12 mg/L

**a) Loading dose:**
LD = Vd × Ctarget = 30 L × 12 mg/L = **360 mg**

**b) Infusion rate:**
R₀ = Css × Cl = 12 mg/L × 2.8 L/h = **33.6 mg/h**

Could give as **~806 mg/day** continuous infusion

**c) Half-life:**
First find k: k = Cl / Vd = 2.8 L/h / 30 L = 0.0933 h⁻¹
Then: t½ = 0.693 / 0.0933 h⁻¹ = **7.43 hours**

**d) Time to reach 10 mg/L without loading dose:**
C(t) = Css × (1 - e^(-k×t))
10 = 12 × (1 - e^(-0.0933×t))
10/12 = 1 - e^(-0.0933×t)
0.833 = 1 - e^(-0.0933×t)
e^(-0.0933×t) = 0.167
-0.0933×t = ln(0.167) = -1.79
t = **19.2 hours**

**Alternative:** 10 mg/L is 83.3% of Css, which occurs at about 2.5 half-lives
Time ≈ 2.5 × 7.43h ≈ **18.6 hours** ✓

**Clinical Decision:** Loading dose saves ~19 hours!

---

### Problem 7.3 - SOLUTION (Renal Impairment)
**Given:**
- Normal: Vd = 50 L, Cl = 5 L/h, t½ = 6.93h
- Standard dose: 500 mg IV q12h
- Patient CrCl: 25% of normal
- Drug primarily renally eliminated

**a) New clearance:**
If 75% reduction in renal function and drug primarily renal:
New Cl = 5 L/h × 0.25 = **1.25 L/h**

**b) New half-life:**
Vd unchanged = 50 L
k_new = Cl_new / Vd = 1.25 L/h / 50 L = 0.025 h⁻¹
t½_new = 0.693 / 0.025 h⁻¹ = **27.7 hours**

(Note: t½ increased 4-fold, which makes sense if Cl decreased 4-fold)

**c) Dose recommendation:**

**Option 1 - Reduce dose, keep interval:**
Reduce dose by 75%: **125 mg every 12 hours**

**Option 2 - Keep dose, extend interval:**
Extend interval by 4-fold: **500 mg every 48 hours**

**Option 3 - Compromise:**
**250 mg every 24 hours**

**Preferred approach:** Usually Option 3 for convenience and maintains more stable levels.

**Verification using Css:**
- Normal: Css_avg ≈ (Dose × F) / (Cl × τ) = 500 mg / (5 L/h × 12h) = 8.33 mg/L
- Option 3: Css_avg = 250 mg / (1.25 L/h × 24h) = 8.33 mg/L ✓

---

## Section 8: First-Order vs Zero-Order

### Problem 8.1 - SOLUTION

**Drug A (First-Order):**
Notice concentration halves every 2 hours
- 0h: 20 mg/L
- 2h: 10 mg/L (halved)
- 4h: 5 mg/L (halved again)

**a) Half-life of Drug A:** **2 hours**

**Drug B (Zero-Order):**
Notice constant amount decrease: 5 mg/L every 2 hours
- 0h: 20 mg/L
- 2h: 15 mg/L (decreased by 5)
- 4h: 10 mg/L (decreased by 5)

**b) Elimination rate:**
Rate = 5 mg/L per 2 hours = **2.5 mg/L per hour**

If Vd = 5 L (from dose/C₀ = 100mg/20mg/L), then:
Absolute rate = 2.5 mg/L/h × 5 L = **12.5 mg/h**

**c) Time to reach 0:**
Starting at 20 mg/L, decreasing by 2.5 mg/L/h:
Time = 20 / 2.5 = **8 hours**

**Key Difference:**
- First-order: Never reaches zero (asymptotic approach)
- Zero-order: Reaches zero in finite time

---

## Challenge Problems - SOLUTIONS

### Challenge 1 - SOLUTION
**Given:**
- t½ = 6 hours
- Dosing every 6 hours (every t½)
- After 1st dose: Cmax = 10 mg/L, Cmin = 5 mg/L

**Analysis:**
After 1 half-life, 50% remains = 5 mg/L (matches given Cmin)
When 2nd dose given, add to remaining concentration

**After 2nd dose:**
- **Cmax = 5 mg/L (remaining) + 10 mg/L (new dose) = 15 mg/L**
- After another 6h: **Cmin = 15 mg/L × 0.5 = 7.5 mg/L**

**Pattern:**
With continued dosing every half-life, concentration accumulates until:
Css_max = Dose / (1 - 0.5) × Vd = 2 × (single dose Cmax) = 20 mg/L
Css_min = Css_max × 0.5 = 10 mg/L

**Note:** Reaches steady-state after ~5 doses (5 half-lives)

---

### Challenge 2 - SOLUTION
**Given:**
- Initial: Cl = 4 L/h, R₀ = 60 mg/h, Css = 15 mg/L
- Clearance drops 50% to 2 L/h
- Infusion rate unchanged

**Calculation:**
New Css = R₀ / Cl_new = 60 mg/h / 2 L/h = **30 mg/L**

**Time Course:**
Concentration will rise from 15 to 30 mg/L over approximately 5 new half-lives

**Clinical Danger:** Concentration doubles! Risk of toxicity. Must reduce infusion rate to 30 mg/h to maintain Css = 15 mg/L.

**Key Concept:** Css is inversely proportional to clearance when infusion rate is constant.

---

### Challenge 3 - SOLUTION
**Given:**
- F = 0.6
- Vd = 50 L
- Cl = 5 L/h
- Target Css = 10 mg/L
- Dosing interval τ = 8 hours

**Formula for multiple oral dosing at steady-state:**
Css_avg = (F × Dose) / (Cl × τ)

**Rearrange:**
Dose = (Css × Cl × τ) / F

**Calculation:**
Dose = (10 mg/L × 5 L/h × 8h) / 0.6
Dose = 400 / 0.6 = **667 mg every 8 hours**

**Practical:** Might round to **650 mg or 700 mg** depending on available formulations

**Verification:**
(0.6 × 667 mg) / (5 L/h × 8h) = 400 / 40 = 10 mg/L ✓

**Note:** If this were IV (F=1.0), dose would only be 400 mg every 8 hours

---

## Quick Checks - SOLUTIONS

**1. A drug with Vd = 500 L in a 70 kg patient indicates:**
**Answer: B) The drug extensively distributes to tissues**

Explanation: 500 L >> body water (~42 L), indicating significant tissue binding

**2. After 4 half-lives, approximately what percentage of drug remains?**
**Answer: C) 6.25%**

Calculation: (0.5)⁴ = 0.0625 = 6.25%
- After 1 t½: 50%
- After 2 t½: 25%
- After 3 t½: 12.5%
- After 4 t½: 6.25%
- After 5 t½: 3.125%

**3. Which parameter determines the maintenance dose in continuous infusion?**
**Answer: B) Clearance**

Formula: R₀ = Css × Cl
Clearance determines the rate at which drug must be replaced to maintain steady-state.

**4. A drug with long half-life but normal clearance must have:**
**Answer: A) Large Vd**

Explanation: Since t½ = (0.693 × Vd) / Cl, if Cl is normal but t½ is long, then Vd must be large.

**5. First-pass metabolism affects:**
**Answer: B) Oral bioavailability**

Explanation: First-pass metabolism occurs after oral absorption (drug passes through liver before reaching systemic circulation). IV drugs bypass first-pass metabolism.

---

## Summary of Key Concepts

### Critical Relationships:
1. **Vd = Dose / C₀** - Larger Vd means more tissue distribution
2. **Cl = k × Vd** - Clearance relates elimination rate to distribution
3. **t½ = 0.693 / k** - Half-life inversely related to elimination rate
4. **Css = R₀ / Cl** - Steady-state proportional to infusion rate, inversely to clearance
5. **LD = Vd × Ctarget** - Loading dose depends on distribution
6. **Time to SS ≈ 5 × t½** - Universal rule for accumulation/elimination

### Clinical Pearls:
- **Large Vd** → Need higher loading doses, longer time to eliminate
- **Low Cl** → Need lower maintenance doses, longer t½
- **Long t½** → Convenient dosing (once daily), but slow onset/offset
- **Low F** → Need much higher oral vs IV doses
- **Renal impairment** → Reduce doses for renally cleared drugs

### Common Mistakes to Avoid:
1. Confusing Vd with actual physiological volume
2. Forgetting units in calculations
3. Not adjusting oral doses for bioavailability
4. Assuming clearance is constant in disease states
5. Thinking half-life determines drug effect (that's pharmacodynamics!)

---

**End of Solutions**

For the lecture outline and additional problems, see:
- pharmacokinetics_intro_lecture_outline.md
- pharmacokinetics_practice_problems.md
