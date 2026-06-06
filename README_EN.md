# Pediatrics-PMPH-10edition

<div align="center">

> *"A 21st Century Medical Student's Guide"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> A clinical skills handbook based on *Pediatrics*, 10th Edition, People's Medical Publishing House (PMPH) — 184 core pediatric clinical skills
<br>
<br>
<img src="/assets/Pediatrics.png" width="260px">
<br>

Why slog through a whole textbook?<br>
Just ask a question and get solutions straight from the book.

<br>

**Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## About the Project

This project systematically integrates core areas of pediatrics, neonatology, child growth and development, infectious disease prevention and control, genetic metabolic disease diagnosis and treatment, and critical emergency care, covering **184 key clinical skills** organized into **15 major categories**.

**Target Audience:** Pediatricians, medical students, neonatal care teams, public health workers, standardized residency trainees

**Reference Textbook:** *Pediatrics*, 10th Edition, People's Medical Publishing House (PMPH)

**⚠️Risk⚠️:** High-risk clinical treatments, procedures, and dosage guidance may not be suitable for unsupervised general installation or use.

**Mitigation:** Intended only for qualified pediatricians, neonatologists, pediatric intensivists, or supervised medical education settings; requires clinician review before acting on output.

**⚠️Risk⚠️:** Guidance may conflict with current local guidelines, institutional protocols, or patient-specific contraindications.

**Mitigation:** Verify that all plans, procedures, thresholds, and follow-up plans conform to local standards and institutional policy before use.

**⚠️Risk⚠️:** Emergency invasive procedures, neonatal resuscitation, pediatric medication dose calculations, and sensitive developmental/behavioral topics may pose patient safety or privacy risks if handled too casually.

**Mitigation:** Add explicit warnings for these scenarios, direct emergencies to ED/ICU care, and restrict access to qualified clinicians or those with supervised educational needs.

## Project Structure

```
Pediatrics-PMPH-10edition/
├── SKILL.md                  # Core configuration — 184 skill registry
├── README.md                 # This document — project description and usage guide
├── <skill-name>/             # Detailed definitions for each skill
│   └── SKILL.md              #   Skill details (when to use, steps, references)
├── scripts/                  # Executable utility scripts
│   └── .gitkeep
├── config/                   # Configuration files
│   └── .gitkeep
└── tests/                    # Validation and testing
    └── .gitkeep
```

## Skill Categories Overview

| Category | Skills | Description |
|----------|--------|-------------|
| 👶 Neonatology & Perinatal Medicine | 18 | Jaundice, RDS, hemolysis, hemorrhage, NEC, ROP, BPD, etc. |
| 📏 Growth, Development & Nutrition | 18 | Physical growth assessment, complementary feeding, sleep, micronutrients, etc. |
| 💉 Immunization & Infectious Disease Control | 20 | Routine immunization, measles, HFMD, tuberculosis, Kawasaki disease, etc. |
| 🫁 Respiratory System Diseases | 12 | Pneumonia, asthma, mycoplasma, bronchoscopy, blood gas analysis, etc. |
| ❤️ Cardiovascular System Diseases | 10 | CHD classification, heart failure, myocarditis, Duke criteria, etc. |
| 🫃 Digestive & Hepatobiliary Diseases | 12 | Intussusception, Hirschsprung disease, IBD, biliary atresia, GERD, etc. |
| 🫘 Urinary & Renal Diseases | 10 | Hematuria, nephritis, nephrotic syndrome, AKI, RTA, etc. |
| ⚖️ Endocrine & Metabolic Diseases | 13 | GHD, precocious puberty, hypothyroidism, diabetes, DKA, etc. |
| 🩸 Hematologic & Oncologic Diseases | 9 | ITP, AIHA, hemophilia, thalassemia, LCH, etc. |
| 🧠 Neurological, Psychiatric & Behavioral Disorders | 12 | Epilepsy, febrile seizures, ADHD, GBS, myasthenia gravis, etc. |
| 🚑 Emergency & Critical Care | 10 | CPR, trauma, drowning, respiratory failure, dehydration, etc. |
| 🧬 Genetic & Congenital Diseases | 7 | Tertiary prevention, genetic disease classification, CHARGE, DMD/BMD, etc. |
| 🔬 Laboratory & Diagnostic Tests | 11 | CSF, PKU, CAH, rickets, MRI, ultrasound, etc. |
| 📚 Textbook & Evidence-Based Medicine | 7 | Textbook authority assessment, revision principles, literature recommendations, etc. |
| 🏋️ Comprehensive Health Management | 9 | Exercise, diet, immune system, medication dosing, physical examination, etc. |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install pediatrics-pmph-10edition
```

Prompt:
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Pediatrics-PMPH-10edition" (xllgreen/pediatrics-pmph-10edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/pediatrics-pmph-10edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### Usage After Installation
Instruct the agent as follows:
```bash
Before answering each question, please look up the relevant medical skill to verify.
```

### Searching Skills

```bash
# Search by keyword
bash scripts/skill-search.sh  neonatal jaundice

# Generate a skill report
bash scripts/skill-report.sh
```

### How to Use

Each skill consists of four parts:
1. **When to Use** — When to trigger this skill
2. **Execution Steps** — Standardized operating procedure
3. **Precautions** — Contraindications and warnings
4. **References** — Detailed supplementary materials

### Query Strategies

#### 1. **Concept**

Question:
```bash
What is neonatal physiological jaundice?
```

Answer:
```bash
## Concept of Neonatal Physiological Jaundice
**Neonatal physiological jaundice** is a transient elevation of unconjugated serum bilirubin in newborns due to bilirubin metabolism characteristics — a benign process that typically resolves without specific intervention.
### Diagnostic Criteria
| Parameter | Term Infant | Preterm Infant |
|-----------|-------------|----------------|
| Onset | 2–3 days after birth | 3–5 days after birth |
| Peak | 4–5 days after birth | 5–7 days after birth |
| Resolution | 5–7 days after birth | 7–9 days after birth |
| Peak Serum Bilirubin | < 221 μmol/L (12.9 mg/dL) | < 256 μmol/L (15 mg/dL) |
| Daily Rise | < 85 μmol/L (5 mg/dL) | < 85 μmol/L (5 mg/dL) |
### Key Differential
- **Physiological jaundice**: Meets the above time window and thresholds; infant generally well
- **Pathological jaundice**: Onset too early (<24h), degree too severe, prolonged duration, excessive daily rise, or elevated direct bilirubin
- **Breastfeeding jaundice**: Onset at 1 week, peaks at 2–3 weeks, drops significantly with 3-day breastfeeding cessation
### Management Principles
No specific treatment required; ensure adequate feeding to promote meconium passage. Initiate phototherapy evaluation if TSB approaches the intervention threshold.
```

#### 2. **Clinical Case Analysis**

Question:
```bash
A newborn, gestational age 38 weeks, vaginal delivery, birth weight 3.2 kg. Develops skin jaundice within 24 hours of birth, rapidly worsening. At 36 hours, TSB is 15 mg/dL, predominantly unconjugated bilirubin. Mother's blood type: O Rh(+); infant's blood type: A Rh(+). What is the most likely diagnosis?
```

Answer:
```bash
## Case Analysis
**Most likely diagnosis: Hemolytic disease of the newborn due to ABO incompatibility**
### Diagnostic Basis
| Clinical Feature | Indication |
|-----------------|------------|
| **Jaundice within 24 hours of birth** | Pathological jaundice — onset too early |
| **Serum total bilirubin 15 mg/dL (257 μmol/L)** | Significantly above physiological range (normal peak <12.9 mg/dL) |
| **Predominantly unconjugated bilirubin** | Consistent with hemolytic jaundice |
| **Mother O + infant A** | Most common ABO incompatibility combination (maternal anti-A IgG crosses placenta) |
| **Positive Coombs test** | Direct evidence of immune-mediated hemolysis |
### Subsequent Management
1. **Initiate phototherapy immediately** — High-intensity blue light (425–475 nm)
2. **Monitor TSB q4–6h** — Assess need for exchange transfusion
3. **CBC + reticulocyte count** — Assess degree of anemia
4. **IVIG infusion** — 0.5–1 g/kg to block hemolysis
5. **Evaluate exchange transfusion criteria** — If TSB ≥ exchange threshold or phototherapy fails
```

#### 3. **Exam Questions**

Question:
```bash
An 8-month-old infant has fever for 3 days; rash appears after defervescence. Most likely diagnosis:
A. Measles
B. Rubella
C. Roseola infantum (Exanthem subitum)
D. Scarlet fever
E. Chickenpox
```

Answer:
```bash
**Answer: C. Roseola infantum (Exanthem subitum)**
### Differential Diagnosis
| Disease | Fever-Rash Relationship | Rash Characteristics | Other Features |
|---------|------------------------|---------------------|----------------|
| A. Measles | Fever **with** rash (rash appears at fever peak) | Dark red maculopapular rash, from postauricular hairline → face → trunk → extremities | Koplik spots, coryza |
| B. Rubella | Fever **with** rash | Pink maculopapular rash, face first → rapid spread to whole body | Postauricular/occipital lymphadenopathy |
| **✅ C. Roseola infantum** | **Rash appears after fever subsides** | Rose-colored maculopapular rash, trunk first → face → extremities, resolves in 1–2 days | High fever (39–40°C), generally well-appearing |
| D. Scarlet fever | Fever **with** rash | Pinpoint erythematous rash, Pastia's lines in skin folds | Strawberry tongue, pharyngitis |
| E. Chickenpox | Fever **with** rash | Centripetal distribution: macules → papules → vesicles → crusts ("four generations") | Intense pruritus |
### Why C?
Key clues in the question:
- **8 months old** → Roseola most common in infants 6–18 months
- **Fever for 3 days, rash after defervescence** → **"Rash after fever" is the classic feature of roseola**, sharply contrasting with the "rash during fever" of other exanthematous diseases
- Rose-colored maculopapules, trunk first → consistent with roseola's rash progression
### Management Essentials
Self-limiting disease; no specific antiviral treatment required. Focus on supportive care:
- Control high fever (physical cooling, antipyretics)
- Ensure adequate fluid intake
- Monitor for febrile seizures
```

## About the Author

**Xllgreen (https://xllgreen.github.io)** — Clinical Medicine student at Jiujiang University · Tech Enthusiast

## Technical Support

PDF2App Project: https://pdf2app.cn

Microsoft Visual Studio Code: https://code.visualstudio.com/

Claude Code for VS Code: https://claude.com/
© 2026 Anthropic PBC

<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
DeepSeek API: https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. All Rights Reserved

<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
Xiaomi Mimo API: https://platform.xiaomimimo.com/
Copyright © 2010 – 2026 Xiaomi. All Rights Reserved

## License

This project's content is compiled from *Pediatrics*, 10th Edition, People's Medical Publishing House (PMPH), for study and reference purposes only.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FPediatrics-PMPH-10edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Pediatrics-PMPH-10edition&type=date&legend=top-left" />
 </picture>
</a>
