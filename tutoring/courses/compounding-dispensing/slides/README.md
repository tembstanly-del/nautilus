# Pharmaceutical Compounding & Dispensing - Slide Decks

This directory contains presentation slide decks for the Pharmaceutical Compounding and Dispensing course.

## Available Slide Decks

### Course Overview
- **File:** `course-overview-slides.md`
- **Purpose:** Course introduction and orientation
- **Use:** First day of class, course overview sessions
- **Duration:** ~60 minutes
- **Topics:** Course structure, requirements, expectations, resources

### Lesson 1: Introduction to Pharmaceutical Compounding
- **File:** `lesson-01-introduction-slides.md`
- **Duration:** ~90 minutes
- **Topics:**
  - What is pharmaceutical compounding
  - Regulatory framework (USP chapters)
  - Professional responsibilities
  - Equipment and facilities
  - Types of compounding
  - Safety considerations

### Lesson 2: Pharmaceutical Calculations - A Conceptual Approach
- **File:** `lesson-02-calculations-slides.md`
- **Duration:** ~120 minutes
- **Topics:**
  - Dimensional analysis
  - Dosage calculations
  - Concentration and dilution
  - Percentage strength
  - Ratio strength
  - Alligation
  - Error prevention

### Lesson 3: Liquid Dosage Forms - Solutions and Suspensions
- **File:** `lesson-03-liquid-dosage-forms-slides.md`
- **Duration:** ~120 minutes
- **Topics:**
  - Solutions (types, preparation, additives)
  - Suspensions (theory, techniques)
  - Levigation method
  - Quality control
  - Beyond-use dating
  - Practical examples

## File Format

All slides are created using **Markdown** with **Marp** formatting.

### Marp Features Used:
- `---` separates individual slides
- `<!-- _class: lead -->` creates centered title slides
- Front matter includes theme, pagination, header, and footer settings
- Tables, code blocks, and lists for content organization

## How to Use These Slides

### Option 1: Marp CLI (Recommended)

1. **Install Marp CLI:**
   ```bash
   npm install -g @marp-team/marp-cli
   ```

2. **Convert to HTML:**
   ```bash
   marp lesson-01-introduction-slides.md -o lesson-01-introduction-slides.html
   ```

3. **Convert to PDF:**
   ```bash
   marp lesson-01-introduction-slides.md -o lesson-01-introduction-slides.pdf --allow-local-files
   ```

4. **Preview in browser:**
   ```bash
   marp -s .
   ```
   Then navigate to http://localhost:8080

### Option 2: Marp for VS Code

1. **Install Extension:**
   - Open VS Code
   - Search for "Marp for VS Code" in extensions
   - Install the extension

2. **Preview:**
   - Open any `.md` slide file
   - Click "Open Preview to the Side" button
   - Or use shortcut: `Ctrl+K V` (Windows/Linux) or `Cmd+K V` (Mac)

3. **Export:**
   - Right-click on the preview
   - Select "Export Slide Deck..."
   - Choose format (HTML, PDF, PPTX)

### Option 3: Marp Web

1. Visit https://web.marp.app/
2. Copy and paste the markdown content
3. Export to desired format

### Option 4: Convert to Other Formats

**Using Pandoc (for PowerPoint):**
```bash
pandoc lesson-01-introduction-slides.md -o lesson-01-introduction-slides.pptx
```

**Using reveal.js:**
```bash
pandoc -t revealjs -s lesson-01-introduction-slides.md -o lesson-01-introduction-slides-reveal.html
```

## Customization

### Changing Theme

Edit the front matter in each file:
```yaml
---
theme: default  # Options: default, gaia, uncover
---
```

### Custom CSS

Create a custom CSS file and reference it:
```yaml
---
theme: custom
style: |
  @import 'custom.css';
---
```

### Adding Images

Place images in an `images/` subdirectory and reference:
```markdown
![Description](images/diagram.png)
```

## Presentation Tips

### For Instructors

1. **Review slides before class**
   - Ensure all content is accurate
   - Practice transitions
   - Prepare additional examples

2. **Customize as needed**
   - Add institution-specific information
   - Include local regulations
   - Adjust timing to your schedule

3. **Interactive elements**
   - Pause at practice problems for student work
   - Use review questions for class discussion
   - Incorporate polling tools if available

4. **Supplement with:**
   - Live demonstrations
   - Video clips
   - Physical samples
   - Calculation practice on whiteboard

### For Students

1. **Use for review**
   - Study slides before and after class
   - Practice calculations from examples
   - Answer review questions

2. **Take additional notes**
   - Slides are outlines, not complete notes
   - Add details from lecture
   - Include personal insights

3. **Practice actively**
   - Work through all practice problems
   - Don't just read solutions
   - Try different approaches

## Printing

### For Handouts

**Marp CLI - 6 slides per page:**
```bash
marp lesson-01-introduction-slides.md -o lesson-01-handout.pdf --pdf-notes
```

**Compress for printing:**
```bash
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/printer \
   -dNOPAUSE -dQUIET -dBATCH \
   -sOutputFile=lesson-01-compressed.pdf lesson-01-introduction-slides.pdf
```

### Print Settings

- **For projection:** Export as PDF, full size
- **For handouts:** 6 slides per page, black & white
- **For notes:** Include notes pages (if available)

## Slide Deck Features

### Visual Elements

- **Tables:** Comparison charts and data
- **Code blocks:** Calculation examples
- **Lists:** Bullet points and numbered items
- **Quotes:** Key definitions and principles
- **Emojis:** Visual indicators (✓, ✗, ❓, etc.)

### Organization

Each slide deck includes:
- **Title slide** - Lesson identification
- **Learning objectives** - Clear goals
- **Content slides** - Organized by topic
- **Examples** - Worked problems
- **Practice problems** - Student exercises
- **Review questions** - Knowledge checks
- **Summary slides** - Key takeaways
- **Homework/Next steps** - Preparation for next lesson
- **Resources** - References and readings
- **Q&A slide** - Wrap-up

## Accessibility

### Making Presentations Accessible

1. **High contrast**
   - Use default theme for good contrast
   - Avoid low-contrast color combinations

2. **Large text**
   - Default sizes are appropriate
   - Avoid very small text

3. **Alt text for images**
   - Include descriptive text
   - Explain complex diagrams

4. **Simple language**
   - Clear, concise explanations
   - Define technical terms

5. **Provide handouts**
   - Export to PDF for students
   - Include notes if available

## License and Attribution

These slides are part of the Nautilus Pharmaceutical Compounding & Dispensing Tutoring Schema.

**Based on:**
- "Pharmaceutical Compounding and Dispensing" by John F. Marriott
- "Pharmaceutical Calculations: A Conceptual Approach" by Alison Dering-Anderson
- USP Chapters <795>, <797>, and <800>

**Attribution:**
When using or modifying these slides, please maintain attribution to:
- Original textbook authors
- Nautilus project
- USP standards

## Updates and Contributions

### Keeping Slides Current

Slides should be reviewed and updated:
- **Annually** - Check for regulation changes
- **Per semester** - Update examples and cases
- **As needed** - Fix errors, improve clarity

### Contributing Improvements

If you make improvements:
1. Note the changes in comments
2. Update the version/date
3. Share back with the project
4. Document significant changes

## Technical Support

### Common Issues

**Problem:** Slides don't render properly
- **Solution:** Ensure using Marp-compatible viewer

**Problem:** Images don't show
- **Solution:** Check file paths are relative, images exist

**Problem:** Formatting looks wrong
- **Solution:** Check Marp version, update if needed

**Problem:** Export fails
- **Solution:** Check file permissions, disk space

### Getting Help

- Marp documentation: https://marp.app/
- Marp GitHub: https://github.com/marp-team/marp
- Markdown guide: https://www.markdownguide.org/

## Best Practices

### For Creating New Slides

1. **Consistent formatting**
   - Use same front matter
   - Follow established patterns
   - Maintain visual consistency

2. **One concept per slide**
   - Don't overcrowd slides
   - Use multiple slides if needed

3. **Clear headings**
   - Descriptive titles
   - Logical organization

4. **Visual hierarchy**
   - Use heading levels appropriately
   - Bullets for lists
   - Bold for emphasis

5. **Practice problems**
   - Include worked examples
   - Show step-by-step solutions
   - Provide practice opportunities

## Version History

- **v1.0** (2025-11-04) - Initial release
  - Course overview
  - Lessons 1-3
  - Based on Marriott and Dering-Anderson textbooks

---

**Questions or suggestions?**
Contact the course coordinator or open an issue in the project repository.

**Happy Teaching and Learning!**
