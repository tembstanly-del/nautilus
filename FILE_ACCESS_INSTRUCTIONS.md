# How to Access Your Pharmacokinetics Presentation Files

All files are located in: `/home/user/nautilus/`

## Quick Access Commands

### View the Master Guide (Start Here!)
```bash
cat PRESENTATION_GUIDE.md
```

### View Obsidian Presentation
```bash
cat pharmacokinetics_lecture_obsidian.md
```

### View Quarto Presentation
```bash
cat pharmacokinetics_intro_lecture.qmd
```

## Copy Files to Your Workspace

### Copy All Files to a Specific Location
```bash
# Create a new directory
mkdir -p ~/pharmacokinetics-lecture

# Copy all presentation files
cp *.md *.qmd *.css ~/pharmacokinetics-lecture/

# Navigate to the directory
cd ~/pharmacokinetics-lecture
```

### Create a Zip Archive
```bash
# Create a zip file with all materials
zip -r pharmacokinetics-complete-package.zip \
  *.md *.qmd *.css \
  -x README.md

# This creates: pharmacokinetics-complete-package.zip
```

### Create a Tar Archive
```bash
# Create a tar.gz archive
tar -czf pharmacokinetics-complete-package.tar.gz \
  pharmacokinetics_*.md \
  pharmacokinetics_*.qmd \
  PRESENTATION_*.md \
  OBSIDIAN_*.md \
  custom.css \
  image_sources_and_links.md

# This creates: pharmacokinetics-complete-package.tar.gz
```

## File Descriptions

### PRESENTATIONS
- **pharmacokinetics_intro_lecture.qmd** - Quarto/RevealJS presentation (30+ slides, R graphs)
- **pharmacokinetics_lecture_obsidian.md** - Obsidian Advanced Slides presentation (60+ slides)

### GUIDES
- **PRESENTATION_GUIDE.md** - START HERE! Compares both formats and provides overview
- **PRESENTATION_README.md** - Complete Quarto setup and usage guide
- **OBSIDIAN_SLIDES_README.md** - Complete Obsidian setup and usage guide

### LECTURE MATERIALS
- **pharmacokinetics_intro_lecture_outline.md** - Slide-by-slide lecture notes with speaker notes
- **pharmacokinetics_practice_problems.md** - 30+ practice problems for students
- **pharmacokinetics_practice_solutions.md** - Detailed solutions with explanations
- **pharmacokinetics_quick_reference.md** - Student study guide with formulas

### RESOURCES
- **image_sources_and_links.md** - Links to 20+ educational images online
- **custom.css** - Custom styling for Quarto presentation

## Recommended Reading Order

1. **PRESENTATION_GUIDE.md** - Overview and comparison
2. Choose your format:
   - Simple/Quick: **OBSIDIAN_SLIDES_README.md**
   - Professional: **PRESENTATION_README.md**
3. Open the presentation file:
   - **pharmacokinetics_lecture_obsidian.md** (Obsidian)
   - **pharmacokinetics_intro_lecture.qmd** (Quarto)
4. Review **pharmacokinetics_intro_lecture_outline.md** for speaker notes
5. Print **pharmacokinetics_quick_reference.md** as student handout

## Quick Start

### For Obsidian Users
```bash
# 1. Copy to your Obsidian vault
cp pharmacokinetics_lecture_obsidian.md /path/to/your/vault/

# 2. Open Obsidian and install "Advanced Slides" plugin
# 3. Open the file and click "Start Presentation"
```

### For Quarto Users
```bash
# 1. Ensure you have R, RStudio, and Quarto installed
# 2. Install ggplot2 in R:
#    install.packages("ggplot2")
# 3. Open in RStudio
rstudio pharmacokinetics_intro_lecture.qmd

# Or render from command line:
quarto render pharmacokinetics_intro_lecture.qmd
```

## Total Package Size
- 12 files
- ~250 pages of content
- ~180 KB total size

## Need Help?
- Read PRESENTATION_GUIDE.md for complete overview
- Read specific README for your chosen format
- All materials based on Boomer.org PHAR 7632 syllabus
