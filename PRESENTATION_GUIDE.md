# Complete Pharmacokinetics Presentation Package

## 🎓 Overview

You now have a **complete teaching package** for an introductory pharmacokinetics lecture, with **TWO professional presentation formats** to choose from plus comprehensive supporting materials.

---

## 📦 Package Contents

### **Presentation Files (Choose One or Both!)**

1. **Quarto/RevealJS Presentation** ⭐ *Recommended for academia*
   - `pharmacokinetics_intro_lecture.qmd`
   - `custom.css` (styling)
   - `PRESENTATION_README.md` (setup guide)

2. **Obsidian Slides Presentation** ⭐ *Recommended for simplicity*
   - `pharmacokinetics_lecture_obsidian.md`
   - `OBSIDIAN_SLIDES_README.md` (setup guide)

### **Supporting Materials**

3. **Lecture Notes & Resources**
   - `pharmacokinetics_intro_lecture_outline.md` - Detailed 90-min lecture notes
   - `pharmacokinetics_practice_problems.md` - Student worksheet (30+ problems)
   - `pharmacokinetics_practice_solutions.md` - Complete answer key
   - `pharmacokinetics_quick_reference.md` - Student study guide

4. **Image Resources**
   - `image_sources_and_links.md` - 20+ links to educational images

---

## 🎯 Quick Decision Guide

### **Which Presentation Format Should I Use?**

```
┌─────────────────────────────────────────────────────────┐
│  Do you want auto-generated R graphs?                   │
│    ├─ YES → Use Quarto Presentation                     │
│    └─ NO → Either format works                          │
│                                                          │
│  Do you use Obsidian for notes?                         │
│    ├─ YES → Use Obsidian Slides (integrates seamlessly) │
│    └─ NO → Use Quarto (more features)                   │
│                                                          │
│  Need offline presentation?                             │
│    ├─ YES → Obsidian (works without internet)           │
│    └─ NO → Either format works                          │
│                                                          │
│  Want simplest setup?                                   │
│    ├─ YES → Obsidian (just install app + plugin)        │
│    └─ NO → Quarto (but worth the setup!)                │
│                                                          │
│  Need publication-quality graphs?                       │
│    ├─ YES → Quarto (R-generated)                        │
│    └─ NO → Obsidian (ASCII art included)                │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 Quick Start Guides

### Option 1: Quarto Presentation

**Time to setup:** 15-30 minutes
**Best for:** Academic presentations, publication-quality visuals

**Steps:**
1. Install R: https://www.r-project.org/
2. Install RStudio: https://posit.co/downloads/
3. Install Quarto: https://quarto.org/docs/get-started/
4. Install R packages:
   ```r
   install.packages("ggplot2")
   install.packages("dplyr")
   ```
5. Open `pharmacokinetics_intro_lecture.qmd` in RStudio
6. Click "Render" button
7. Present in browser!

**Full guide:** See `PRESENTATION_README.md`

---

### Option 2: Obsidian Slides

**Time to setup:** 5-10 minutes
**Best for:** Simple, offline presentations

**Steps:**
1. Install Obsidian: https://obsidian.md/
2. Open Obsidian → Settings → Community plugins
3. Install "Advanced Slides" plugin
4. Copy `pharmacokinetics_lecture_obsidian.md` to your vault
5. Open file and click "Start Presentation"
6. Present!

**Full guide:** See `OBSIDIAN_SLIDES_README.md`

---

## 📊 Feature Comparison

| Feature | Quarto | Obsidian |
|---------|--------|----------|
| **Setup Complexity** | ⭐⭐⭐ (Moderate) | ⭐ (Easy) |
| **Professional Appearance** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **R-Generated Graphs** | ✅ Yes | ❌ No (ASCII art) |
| **Mermaid Diagrams** | ✅ Yes | ✅ Yes |
| **LaTeX Math** | ✅ Yes | ✅ Yes |
| **Offline Use** | ✅ Yes (after render) | ✅ Yes (always) |
| **Export to PDF** | ✅ Easy | ✅ Via print |
| **Export to PowerPoint** | ✅ Native | ⚠️ Via converter |
| **Customization** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **File Size** | Larger (~5-10 MB) | Smaller (~100 KB) |
| **Number of Slides** | 30+ | 60+ |
| **Speaker Notes** | ✅ Full support | ✅ Limited support |
| **Practice Problems** | ✅ Interactive tabs | ✅ In slides |
| **Web Sharing** | ✅ Easy (HTML) | ⚠️ Export first |

---

## 📁 File Organization

```
pharmacokinetics-lecture/
│
├── PRESENTATIONS/
│   ├── Quarto/
│   │   ├── pharmacokinetics_intro_lecture.qmd
│   │   ├── custom.css
│   │   └── PRESENTATION_README.md
│   │
│   └── Obsidian/
│       ├── pharmacokinetics_lecture_obsidian.md
│       └── OBSIDIAN_SLIDES_README.md
│
├── SUPPORTING_MATERIALS/
│   ├── pharmacokinetics_intro_lecture_outline.md
│   ├── pharmacokinetics_practice_problems.md
│   ├── pharmacokinetics_practice_solutions.md
│   ├── pharmacokinetics_quick_reference.md
│   └── image_sources_and_links.md
│
└── THIS_FILE/
    └── PRESENTATION_GUIDE.md
```

---

## 🎨 Content Overview

### Both Presentations Cover:

**Part 1: Fundamentals (20 min)**
- What is pharmacokinetics?
- ADME processes (Absorption, Distribution, Metabolism, Excretion)
- Concentration-time relationships

**Part 2: Compartment Models & IV Bolus (25 min)**
- One-compartment model
- Volume of distribution (Vd)
- Clearance (Cl)
- Elimination rate constant (k)
- Half-life (t½)
- First-order vs zero-order kinetics

**Part 3: IV Infusion & Steady State (15 min)**
- Continuous IV infusion
- Steady-state principles
- Loading dose concept
- 5 half-lives rule

**Part 4: Oral Administration & Bioavailability (15 min)**
- Oral vs IV differences
- Bioavailability (F)
- First-pass metabolism
- Bioequivalence

**Part 5: Clinical Applications (10 min)**
- Gentamicin case study (complete calculation)
- Special populations (renal, hepatic, elderly, obesity)
- Dose adjustments

**Summary & Practice (5 min)**
- Key concepts review
- Essential formulas
- Practice problems
- Resources

---

## 📈 Visual Content

### Quarto Presentation Includes:

✅ **Auto-generated R graphs:**
- IV bolus exponential decay curves
- Oral concentration-time curves
- IV vs Oral comparison
- Infusion rise to steady-state
- Loading dose comparison
- First-order vs zero-order kinetics
- Bioequivalence curves
- Clearance bar charts

✅ **Mermaid diagrams:**
- ADME flowcharts
- One-compartment model
- Bioavailability/first-pass flow
- Clinical decision trees
- Parameter relationships

✅ **Interactive elements:**
- Incremental reveals
- Tabbed content (case studies)
- Practice problems with hidden solutions
- Clickable resources

### Obsidian Presentation Includes:

✅ **Mermaid diagrams:**
- ADME detailed flow
- Compartment models
- Clearance mechanisms
- First-pass metabolism
- Parameter relationships
- Clinical decision trees

✅ **ASCII art graphs:**
- Concentration-time curves
- IV bolus decay patterns
- First-order vs zero-order comparison
- Half-life step diagrams
- Steady-state rise

✅ **Layout features:**
- Split-screen comparisons
- Color-coded sections
- Formula cards
- Tables and comparisons

---

## 🎓 Teaching Resources Included

### 1. Detailed Lecture Outline
**File:** `pharmacokinetics_intro_lecture_outline.md`

- Slide-by-slide speaker notes
- Learning objectives for each section
- Interactive activity suggestions
- Clinical examples
- Common student misconceptions
- Assessment suggestions
- Equipment needs

### 2. Practice Problems
**File:** `pharmacokinetics_practice_problems.md`

- 30+ problems organized by topic
- Vd, Cl, k, t½ calculations
- IV infusion problems
- Bioavailability calculations
- Integrated clinical cases
- Challenge problems
- Formula reference sheet

### 3. Complete Solutions
**File:** `pharmacokinetics_practice_solutions.md`

- Step-by-step solutions for all problems
- Multiple solution methods shown
- Clinical interpretations
- Common mistakes highlighted
- Verification checks
- Clinical pearls

### 4. Student Study Guide
**File:** `pharmacokinetics_quick_reference.md`

- All essential formulas
- Parameter interpretations
- Clinical applications
- TDM guidelines
- Dose adjustment protocols
- Common drug examples
- Conversion tables
- Study checklist
- Cut-out formula card

### 5. Image Resource Guide
**File:** `image_sources_and_links.md`

- 20+ links to educational images
- ADME diagrams (ResearchGate, NCBI)
- Concentration-time curves (ScienceDirect)
- Compartment models (Boomer.org)
- First-pass metabolism illustrations
- Kinetics comparisons
- DIY image creation instructions
- R code for custom graphs
- Copyright and attribution info

---

## 🔗 Resources Referenced

### Primary Source
**Boomer.org PHAR 7632 Pharmacokinetics Syllabus**
- Website: https://www.boomer.org/c/p4/
- Full Syllabus: https://www.boomer.org/c/p4/syllabus.html
- Created by Dr. David Bourne
- Affiliated with OUHSC, SUNY Buffalo, University of Wisconsin

### Chapter Links Included
- Chapter 3: Pharmacokinetic Fundamentals
- Chapter 4: One-Compartment IV Bolus
- Chapter 5: Derived Parameters (Vd, Cl, t½)
- Chapter 6: IV Infusion
- Chapters 7-8: Oral Administration & Bioavailability

### Additional References
- NCBI StatPearls (pharmacokinetics topics)
- Deranged Physiology (compartment models, kinetics)
- ResearchGate (scientific diagrams)
- Open Education Alberta (PK/PD textbook)

---

## 💡 Usage Recommendations

### For First-Time Presenters

**Start with:**
1. Read the detailed lecture outline first
2. Choose Obsidian (simpler setup)
3. Practice navigating slides
4. Review speaker notes
5. Prepare handouts (quick reference guide)

### For Experienced Presenters

**Consider:**
1. Quarto for more professional appearance
2. Customize graphs with R
3. Add institution-specific content
4. Create supplementary clinical cases
5. Integrate with LMS (export HTML)

### For Online Teaching

**Best approach:**
1. Use Quarto (better web sharing)
2. Render to HTML
3. Host on course website
4. Students can review at own pace
5. Share PDF backup for downloads

### For In-Person Lectures

**Recommended:**
1. Either format works well
2. Test on presentation equipment first
3. Have PDF backup ready
4. Print formula reference cards
5. Bring practice problems worksheet

---

## ⚙️ Customization Guide

### Modifying Content

**Both formats use Markdown:**
- Easy to edit text
- Add/remove slides simply
- Modify practice problems
- Update formulas
- Change examples

**Quarto-specific:**
- Edit R code chunks for different graphs
- Modify CSS for styling
- Change RevealJS theme
- Adjust slide transitions

**Obsidian-specific:**
- Change theme in YAML frontmatter
- Modify Mermaid diagrams
- Adjust ASCII art graphs
- Change fragment timing

### Adding Your Content

**Suggested additions:**
1. **Institution logo:** Add to title slide
2. **Local examples:** Replace with familiar drugs
3. **Case studies:** Add institution-specific cases
4. **Clinical guidelines:** Reference local protocols
5. **Assessment questions:** Add quiz slides

### Styling Customization

**Colors:**
- Quarto: Edit `custom.css`
- Obsidian: Choose different theme

**Fonts:**
- Quarto: Modify CSS font-family
- Obsidian: Use theme settings

**Layout:**
- Both: Use Markdown formatting
- Both: Adjust column widths
- Quarto: More control via CSS

---

## 📤 Sharing Your Presentation

### With Students

**Recommended sharing methods:**

1. **PDF (Universal):**
   - Quarto: Render to PDF
   - Obsidian: Print to PDF
   - Works on all devices
   - No special software needed

2. **HTML (Interactive):**
   - Quarto: Render to HTML
   - Upload to course website
   - Students can navigate slides
   - Links remain clickable

3. **PowerPoint:**
   - Quarto: Native PPTX export
   - Obsidian: Convert via Pandoc
   - Editable by students
   - Familiar format

4. **Source Files:**
   - Share .qmd or .md files
   - Students can render themselves
   - Great for Obsidian users
   - Encourages engagement

### On Learning Management Systems (LMS)

**Upload options:**
- PDF - Most compatible
- HTML - Best interactivity (zip with support files)
- SCORM package - For tracking (advanced)

### Open Educational Resources (OER)

**If sharing publicly:**
1. Include attribution to Boomer.org
2. Maintain resource links
3. Use Creative Commons license
4. Share on GitHub or OER repositories

---

## 🔧 Troubleshooting

### General Issues

**Problem:** Can't decide which format to use
**Solution:** Try Obsidian first (simpler), then Quarto if you want R graphs

**Problem:** Don't have time to setup either
**Solution:** Use the detailed lecture outline as speaking notes

**Problem:** Need presentation in 1 hour
**Solution:** Obsidian → 10 min setup, or use PDF from pre-rendered Quarto

### Quarto-Specific

**Problem:** R packages won't install
**Solution:** Check internet connection, update R, try RStudio package manager

**Problem:** Graphs not rendering
**Solution:** Ensure ggplot2 installed, check R code chunks, verify R accessible

**Problem:** Can't render to PDF
**Solution:** Install tinytex: `quarto install tinytex`

**Full troubleshooting:** See `PRESENTATION_README.md`

### Obsidian-Specific

**Problem:** Can't find Advanced Slides plugin
**Solution:** Enable Community Plugins first, then search

**Problem:** Mermaid diagrams not showing
**Solution:** Update Obsidian, check settings for Mermaid support

**Problem:** Math formulas not rendering
**Solution:** Enable LaTeX in Settings → Editor

**Full troubleshooting:** See `OBSIDIAN_SLIDES_README.md`

---

## 📚 Complete File Inventory

### Ready to Present (2 options)

1. ✅ `pharmacokinetics_intro_lecture.qmd` - Quarto presentation
2. ✅ `pharmacokinetics_lecture_obsidian.md` - Obsidian presentation

### Setup Guides (2 detailed READMEs)

3. ✅ `PRESENTATION_README.md` - Quarto setup (13 pages)
4. ✅ `OBSIDIAN_SLIDES_README.md` - Obsidian setup (15 pages)

### Supporting Materials (4 comprehensive docs)

5. ✅ `pharmacokinetics_intro_lecture_outline.md` - Lecture notes (70 pages)
6. ✅ `pharmacokinetics_practice_problems.md` - Student worksheet (25 pages)
7. ✅ `pharmacokinetics_practice_solutions.md` - Answer key (45 pages)
8. ✅ `pharmacokinetics_quick_reference.md` - Study guide (30 pages)

### Visual Resources (1 image guide)

9. ✅ `image_sources_and_links.md` - Image sources and DIY guide (25 pages)

### Styling (1 CSS file)

10. ✅ `custom.css` - Quarto custom styling

### This Guide

11. ✅ `PRESENTATION_GUIDE.md` - **YOU ARE HERE**

**Total: 11 files, ~250 pages of content**

---

## ⏱️ Time Investment

### Initial Setup

| Task | Quarto | Obsidian |
|------|--------|----------|
| Software installation | 20-30 min | 5 min |
| Plugin/package setup | 10 min | 2 min |
| Test presentation | 5 min | 2 min |
| **Total first time** | **35-45 min** | **10-15 min** |

### Subsequent Uses

| Task | Quarto | Obsidian |
|------|--------|----------|
| Open & present | <1 min | <1 min |
| Minor edits | 5-10 min | 5-10 min |
| Re-render | 1-2 min | Instant |

### Customization

| Task | Time Required |
|------|--------------|
| Change theme/colors | 5-15 min |
| Add new slides | 10-30 min |
| Modify graphs (Quarto) | 15-30 min |
| Add local examples | 20-40 min |
| Create custom diagrams | 30-60 min |

---

## 🎯 Next Steps

### Immediate Actions (Choose Your Path)

**Path A - Quarto (Recommended for academic use):**
1. [ ] Install R, RStudio, Quarto (30 min)
2. [ ] Install ggplot2 package (5 min)
3. [ ] Open .qmd file in RStudio
4. [ ] Click "Render" button
5. [ ] Review presentation in browser
6. [ ] Practice navigation (arrow keys, S for speaker mode)

**Path B - Obsidian (Recommended for quick start):**
1. [ ] Install Obsidian (5 min)
2. [ ] Enable Community Plugins
3. [ ] Install Advanced Slides plugin
4. [ ] Copy .md file to vault
5. [ ] Click "Start Presentation"
6. [ ] Practice navigation (arrow keys)

**Path C - Both (Maximum flexibility):**
1. [ ] Setup Obsidian first (quick)
2. [ ] Present with Obsidian
3. [ ] Setup Quarto later for better graphs
4. [ ] Choose which you prefer for future

### Preparation for Lecture

1. [ ] Choose presentation format
2. [ ] Review all slides thoroughly
3. [ ] Read detailed lecture outline
4. [ ] Practice calculations
5. [ ] Test on presentation equipment
6. [ ] Prepare handouts:
   - [ ] Print quick reference guide
   - [ ] Print practice problems
   - [ ] Print formula card
7. [ ] Create backup PDF
8. [ ] Review Boomer.org chapters
9. [ ] Prepare real-world examples
10. [ ] Time yourself (aim for 85-90 min)

### After First Use

1. [ ] Collect student feedback
2. [ ] Note unclear slides
3. [ ] Identify timing issues
4. [ ] Consider customizations
5. [ ] Share materials with students
6. [ ] Refine for next time

---

## ✨ Pro Tips

### For Maximum Impact

1. **Use Both Formats:**
   - Present with Quarto (better visuals)
   - Share Obsidian version with students (easier to navigate)

2. **Enhance Engagement:**
   - Pause at practice problems
   - Ask prediction questions
   - Use clinical scenarios
   - Draw on slides (use chalkboard mode)

3. **Support Learning:**
   - Print formula cards for students
   - Share PDF before class for preview
   - Post solutions after class
   - Create quiz using practice problems

4. **Time Management:**
   - Use speaker mode timer
   - Set milestones (Part 1 by :20, Part 2 by :45, etc.)
   - Have "can skip" slides marked
   - Save Q&A for end

5. **Technical Backup:**
   - Always have PDF backup
   - Test everything day before
   - Arrive early to setup
   - Have phone with slides as ultimate backup

---

## 🌟 Success Metrics

After presenting, students should be able to:

✅ Define pharmacokinetics and ADME
✅ Calculate Vd from dose and C₀
✅ Calculate clearance from given parameters
✅ Calculate half-life and use for predictions
✅ Distinguish first-order from zero-order kinetics
✅ Interpret concentration-time curves
✅ Calculate loading and maintenance doses
✅ Understand bioavailability concept
✅ Apply concepts to clinical scenarios
✅ Adjust doses for special populations

---

## 📞 Support & Community

### Getting Help

**For Quarto issues:**
- Quarto documentation: https://quarto.org/docs/
- RStudio community: https://community.rstudio.com/
- Stack Overflow: Tag [quarto]

**For Obsidian issues:**
- Obsidian help: https://help.obsidian.md/
- Community forum: https://forum.obsidian.md/
- Advanced Slides GitHub: https://github.com/MSzturc/obsidian-advanced-slides

**For content questions:**
- Review Boomer.org resources
- Consult pharmacology textbooks
- NCBI pharmacokinetics resources

### Sharing Improvements

If you create enhancements:
- Share with teaching community
- Post on OER repositories
- Contribute to educational forums
- Help other instructors

---

## 📜 License & Attribution

**Content based on:**
- Boomer.org PHAR 7632 Syllabus (Dr. David Bourne)
- Website: https://www.boomer.org/c/p4/

**Educational use permitted for:**
- Academic teaching
- Student education
- Clinical training
- Personal study

**Please maintain:**
- Attribution to Boomer.org
- Resource links intact
- Educational purpose focus

---

## 🎓 Final Checklist

Before your lecture:

- [ ] Presentation format chosen and tested
- [ ] All software installed and working
- [ ] Presentation reviewed completely
- [ ] Practice problems solved
- [ ] Handouts prepared and printed
- [ ] Backup PDF created
- [ ] Equipment tested (projector, laptop, clicker)
- [ ] Internet connection checked (for online images)
- [ ] Speaker notes reviewed
- [ ] Timing practiced
- [ ] Student materials ready to distribute
- [ ] Confident and excited to teach!

---

## 🚀 You're Ready!

You now have **everything you need** for an excellent pharmacokinetics lecture:

✅ Two complete presentation formats
✅ Detailed speaker notes
✅ Practice problems and solutions
✅ Student study guides
✅ Image resources
✅ Setup instructions
✅ Troubleshooting help

**Choose your format, practice once, and you're ready to teach!**

**Good luck with your lecture!** 🎉

---

**Document:** Complete Presentation Package Guide
**Version:** 1.0
**Last Updated:** 2025-11-14
**Total Package Size:** 11 files, ~250 pages
**Presentation Options:** 2 (Quarto + Obsidian)
**Setup Time:** 10-45 minutes (depending on choice)
**Lecture Duration:** 90 minutes

**Questions?** Review the specific README for your chosen format!

- Quarto: `PRESENTATION_README.md`
- Obsidian: `OBSIDIAN_SLIDES_README.md`
