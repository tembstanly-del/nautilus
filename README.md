# Nautilus - Pharmaceutical Compounding & Dispensing Tutoring Schema

[![Status](https://img.shields.io/badge/Status-Active%20Development-green)]()
[![License](https://img.shields.io/badge/License-MIT-blue)]()

## Overview

**Nautilus** is a comprehensive educational framework for pharmaceutical compounding and dispensing, focusing on the pharmacy and pharmaceutics domain. This project provides structured schemas, tutoring materials, and practical examples to support pharmacy education and professional development.

### Primary Focus Areas

- **Pharmaceutical Compounding** - Based on principles from "Pharmaceutical Compounding and Dispensing" by John F. Marriott
- **Pharmaceutical Calculations** - Using conceptual approaches from "Pharmaceutical Calculations: A Conceptual Approach"
- **Practical Application** - Real-world formulations, procedures, and quality control

## Project Structure

```
nautilus/
├── schemas/                    # JSON Schema definitions
│   ├── pharmacy/
│   │   └── compounding/       # Compounding-specific schemas
│   │       ├── compounding.schema.json
│   │       └── calculations.schema.json
│   └── shared/                # Shared/common schemas
│
├── tutoring/                  # Educational course materials
│   └── courses/
│       └── compounding-dispensing/
│           ├── course-overview.md
│           ├── lesson-01-introduction.md
│           ├── lesson-02-calculations.md
│           └── lesson-03-liquid-dosage-forms.md
│
├── examples/                  # Practical compounding recipes
│   └── compounding-recipes/
│       ├── 01-simple-suspension.json
│       ├── 02-topical-cream.json
│       └── 03-alligation-solution.json
│
├── references/               # Book references and bibliography
│   ├── bibliography.json
│   └── books/
│       ├── marriott-compounding-dispensing.md
│       └── pharmaceutical-calculations-conceptual.md
│
├── docs/                    # Documentation
│   └── pharmacy/
│
└── tests/                   # Testing and validation
    └── schemas/
```

## Key Features

### 1. Comprehensive JSON Schemas

Structured schemas for pharmaceutical compounding that cover:
- Complete compounding process documentation
- Formulation specifications
- Quality control procedures
- Safety considerations
- Labeling requirements
- Pharmaceutical calculations

### 2. Educational Course Materials

A full tutoring course covering:
- **Module 1**: Introduction to Pharmaceutical Compounding
- **Module 2**: Pharmaceutical Calculations (Conceptual Approach)
- **Module 3**: Liquid Dosage Forms (Solutions & Suspensions)
- **Module 4**: Semi-solid Dosage Forms (Ointments, Creams, Gels)
- **Module 5**: Solid Dosage Forms (Powders, Capsules)
- **Module 6**: Sterile Compounding
- **Module 7**: Quality Assurance
- **Module 8**: Dispensing and Patient Care

### 3. Practical Examples

Real-world compounding recipes with:
- Step-by-step procedures
- Detailed calculations
- Quality control measures
- Safety considerations
- Patient counseling points

**Current Examples:**
- Amoxicillin 50 mg/mL Oral Suspension
- Hydrocortisone 2.5% Cream
- Dextrose 7.5% Solution (using Alligation)

### 4. Evidence-Based References

Complete bibliography and detailed book references:
- **Primary:** "Pharmaceutical Compounding and Dispensing" by John F. Marriott
- **Secondary:** "Pharmaceutical Calculations: A Conceptual Approach" by Alison Dering-Anderson
- **Standards:** USP Chapters <795>, <797>, <800>
- **Professional:** PCCA, IACP, ASHP resources

## Educational Approach

### Conceptual Learning

Rather than rote memorization, Nautilus emphasizes:
- Understanding the "why" behind procedures
- Dimensional analysis for calculations
- Critical thinking and problem-solving
- Patient safety through understanding
- Clinical relevance and application

### Skills Development

The framework supports development of:
- **Calculation skills** - Accurate pharmaceutical calculations
- **Technical skills** - Proper compounding techniques
- **Critical thinking** - Problem-solving and troubleshooting
- **Professional judgment** - Decision-making in practice
- **Quality assurance** - Documentation and control

## Target Audience

- **Pharmacy Students** - Undergraduate and graduate pharmacy programs
- **Practicing Pharmacists** - Continuing education and skill enhancement
- **Pharmacy Technicians** - Advanced compounding training
- **Educators** - Curriculum development and teaching resources
- **Researchers** - Structured data for pharmaceutical education research

## Getting Started

### Prerequisites

To use the Nautilus framework, you should have:
- Basic pharmaceutical knowledge
- Understanding of chemistry and mathematics
- Familiarity with pharmacy practice
- Access to compounding facilities (for practical work)

### Using the Materials

1. **For Self-Study:**
   - Start with the course overview in `tutoring/courses/compounding-dispensing/`
   - Work through lessons sequentially
   - Practice with example recipes
   - Review reference materials as needed

2. **For Course Development:**
   - Adapt lesson materials to your curriculum
   - Use schemas for structured documentation
   - Incorporate example recipes into lab sessions
   - Reference bibliography for additional resources

3. **For Compounding Practice:**
   - Review schemas to understand documentation requirements
   - Follow example recipes for practical guidance
   - Apply quality control procedures
   - Use calculations schemas for accuracy

## Core Principles

### Quality Assurance

All materials emphasize:
- Accurate calculations (double-checked)
- Proper techniques (evidence-based)
- Quality control (systematic testing)
- Documentation (complete records)
- Patient safety (primary concern)

### Regulatory Compliance

Content aligned with:
- **USP <795>** - Nonsterile Compounding
- **USP <797>** - Sterile Compounding
- **USP <800>** - Hazardous Drugs
- **FDA Guidance** - Compounding regulations
- **State Board Requirements** - Professional standards

### Patient-Centered Care

Focus on:
- Individualized medication therapy
- Patient safety and counseling
- Appropriate dosage forms
- Clear labeling and instructions
- Adverse event monitoring

## Key Concepts Covered

### Pharmaceutical Calculations
- Dimensional analysis
- Dosage calculations
- Concentration and dilution
- Percentage strength
- Ratio strength
- Alligation methods
- Beyond-use dating
- Error prevention

### Compounding Techniques
- Levigation and trituration
- Geometric dilution
- Reconstitution
- Emulsification
- Aseptic technique
- Quality control testing

### Dosage Forms
- Solutions and syrups
- Suspensions
- Emulsions
- Ointments and creams
- Gels and pastes
- Powders and capsules
- Suppositories
- Sterile preparations

## Schema Format

All schemas follow JSON Schema Draft-07 standard:
```json
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "type": "object",
  "required": [...],
  "properties": {...}
}
```

Schemas can be used for:
- Data validation
- Documentation generation
- Database design
- API development
- Educational tools

## Examples Usage

Each example recipe includes:
- **Complete formulation** - All ingredients with quantities
- **Step-by-step procedure** - Detailed compounding instructions
- **Calculations** - All mathematical work shown
- **Quality control** - Testing and verification steps
- **Labeling** - Complete label information
- **Counseling points** - Patient education
- **References** - Supporting literature

## Contributing

We welcome contributions to the Nautilus project:

### How to Contribute

1. **Content Additions:**
   - New lesson materials
   - Additional compounding recipes
   - Reference materials
   - Practice problems

2. **Schema Enhancements:**
   - Additional properties
   - Improved validation
   - New schema types
   - Documentation improvements

3. **Error Corrections:**
   - Calculation errors
   - Procedure corrections
   - Reference updates
   - Typo fixes

### Contribution Guidelines

- Ensure accuracy of all pharmaceutical information
- Include proper citations and references
- Follow existing formatting standards
- Validate JSON schemas
- Test procedures for feasibility
- Consider patient safety implications

## Roadmap

### Current Phase (v1.0)
- ✅ Core schemas for compounding and calculations
- ✅ Foundation lessons (Introduction, Calculations, Liquids)
- ✅ Example recipes (Suspension, Cream, Solution)
- ✅ Bibliography and book references

### Upcoming Features (v1.1)
- Additional lesson modules (Semi-solids, Solids, Sterile)
- More example recipes (various dosage forms)
- Quality control test procedures
- Equipment specifications
- Video demonstrations (planned)

### Future Enhancements (v2.0)
- Interactive calculation tools
- Virtual lab simulations
- Competency assessments
- Mobile app integration
- Multi-language support

## Resources

### Official Standards
- [USP Official Website](https://www.usp.org)
- [FDA Compounding Guidance](https://www.fda.gov/drugs/guidance-compliance-regulatory-information/human-drug-compounding)

### Professional Organizations
- [Professional Compounding Centers of America (PCCA)](https://www.pccarx.com)
- [International Academy of Compounding Pharmacists (IACP)](https://www.iacprx.org)
- [American Society of Health-System Pharmacists (ASHP)](https://www.ashp.org)

### Educational Resources
- [Pharmaceutical Press](https://www.pharmpress.com)
- [Springer Publishing (Pharmacy)](https://www.springerpub.com)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Citation

If you use Nautilus in your research or education, please cite:

```
Nautilus Pharmaceutical Compounding & Dispensing Tutoring Schema. (2025).
GitHub repository. https://github.com/[username]/nautilus
```

## Acknowledgments

### Primary References
- **John F. Marriott** - "Pharmaceutical Compounding and Dispensing"
- **Alison Dering-Anderson** - "Pharmaceutical Calculations: A Conceptual Approach"

### Standards Organizations
- United States Pharmacopeial Convention (USP)
- U.S. Food and Drug Administration (FDA)
- Professional pharmacy organizations (PCCA, IACP, ASHP)

## Contact and Support

For questions, suggestions, or contributions:
- **GitHub Issues**: For bug reports and feature requests
- **Discussions**: For general questions and community interaction
- **Email**: [Project maintainer email]

## Disclaimer

**Important Notice:**

This educational framework is provided for instructional purposes only. All pharmaceutical compounding must:
- Comply with applicable laws and regulations
- Be performed by licensed professionals
- Follow current USP standards and guidance
- Prioritize patient safety above all else
- Be supervised appropriately in educational settings

The materials provided are meant to supplement, not replace, professional pharmaceutical education and judgment. Always consult current references, regulations, and experienced practitioners.

---

**Status:** Active Development | **Version:** 1.0.0 | **Last Updated:** 2025-11-04

**Built for pharmacy education. Focused on patient safety. Committed to excellence.**
