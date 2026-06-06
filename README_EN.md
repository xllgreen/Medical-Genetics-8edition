# Medical Genetics 8th Edition

<div align="center">

> *"A 21st Century Medical Student's Guide"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> A clinical genetics skill handbook based on *Medical Genetics* 8th Edition — 131 core clinical skills in medical genetics
<br>
<br>
<img src="/assets/Medical-Genetics-8edition.png" width="260px">
<br>

Why slog through an entire book?<br>
Just ask a question, and let the textbook find the answer for you.

<br>

**其他语言 / Other Languages:**

[English](README_EN.md)

</div>

---

## Project Overview

This project systematically integrates core areas of medical genetics, genomics, metabolic disorders, prenatal diagnosis, gene therapy, and epigenetic regulation, covering **131 essential clinical skills**.

**Target Audience**: Clinical geneticists, medical students, genetic counselors, precision medicine researchers, prenatal care teams

**Reference Textbook**: *Medical Genetics* 8th Edition

**⚠️ Risk ⚠️**: This skill set can produce high-impact guidance on clinical, reproductive, forensic, or gene therapy matters. If used solely as professional advice, it may carry risks.
**Mitigation**: Use all output solely as educational material or for clinician review. Before making decisions on diagnosis, treatment, pregnancy, forensic analysis, paternity testing, genetic testing, or gene therapy, ensure qualified medical, genetics, or legal supervision is in place.
**⚠️ Risk ⚠️**: Genetic case analysis may involve sensitive personal or family health information.
**Mitigation**: Before sharing or processing identifiable genetic, reproductive, or family history information, appropriate consent, privacy, and local agreement controls should be applied.

## Project Structure

```
Medical-Genetics-8edition/
├── SKILL.md              # Core configuration — 131-skill registry
├── README.md             # This document — project description and usage guide
├── index.md              # Complete skill index
├── <skill-name>/         # Detailed definition for each skill
│   └── SKILL.md          #   Skill details (when to use, procedure, precautions)
└── assets/               # Image assets
```

## Skill Categories at a Glance

| Category | Skills | Description |
|----------|--------|-------------|
| 🧬 Classification & Mechanism of Genetic Diseases | 14 | Five-class classification, enzyme defects, collagenopathies, sickle cell disease, etc. |
| 🔬 Chromosomal & Genomic Structural Variation | 16 | Karyotype description, G-banding, deletions/translocations/inversions, polymorphisms, GT-AG rule, etc. |
| 📊 Inheritance Patterns & Pedigree Analysis | 10 | AD/AR/XR pedigree analysis, Lyon hypothesis, Knudson two-hit model, SRY gene, etc. |
| 🤰 Prenatal Screening & Diagnostic Techniques | 6 | NIPT, ultrasound screening, PGD, invasive/non-invasive pathway selection, etc. |
| ⚕️ Chromosomal Abnormalities & Reproductive Risk | 12 | Reciprocal translocation, Robertsonian translocation, pericentric/paracentric inversion, mosaicism, etc. |
| 🔋 Mitochondrial Genetics & Disease | 11 | mtDNA transcription/translation, maternal inheritance, threshold effect, biochemical/clinical/genetic classification |
| 🧮 Complex Diseases & Polygenic Risk | 10 | Hardy-Weinberg equilibrium, Bayesian updating, polygenic disease recurrence risk, etc. |
| 💉 Gene Therapy & Molecular Intervention | 8 | Gene repair/enhancement, viral vector selection, CRISPR safety assessment, gene silencing |
| 🧫 Tumor Genetics & Epigenetic Regulation | 9 | Tumor suppressor genes, oncogenes, Knudson theory, histone modification, DNA methylation |
| 📡 Non-coding RNA & Biomarkers | 3 | miRNA, lncRNA, circRNA cardiovascular biomarkers |
| 🏥 Diagnosis & Treatment of Specific Genetic Diseases | 11 | Thalassemia, PKU, Pompe disease, Tay-Sachs, albinism, hemophilia A, etc. |
| ⚖️ Systems Medicine & Ethical Applications | 8 | Systems medicine, 1000 Genomes Project, consanguineous marriage, ethical assessment, teratogen exposure |
| 🛡️ DNA Repair & Stability | 3 | DNA damage repair, fragile sites, NMD nonsense-mediated decay |

## Quick Start

### Installation

CLI:
```bash
openclaw skills install medical-genetics-8edition
```

Prompt:
```bash
Before installing anything, inspect the ClawHub skill metadata and setup requirements.
If the skill asks you to install a third-party package or CLI, verify its source, maintainer, and package contents before running the install command.
Install the skill "Medical Genetics 8edition" (xllgreen/medical-genetics-8edition) from ClawHub only after those checks pass.
Skill page: https://clawhub.ai/xllgreen/medical-genetics-8edition
Keep the work scoped to this skill only.
After install, help me finish setup from verified skill metadata.
Use only the metadata you can verify from ClawHub; do not invent missing requirements.
Ask before making any broader environment changes.
```

### Usage

Each skill consists of three parts:
1. **When to Use** — Trigger conditions for the skill
2. **Procedure** — Standardized operational workflow
3. **Precautions** — Contraindications and warnings

### Question Strategies

#### 1. Concept Understanding
Question:
```bash
What is the Hardy-Weinberg equilibrium?
```
Answer:
```bash
## Hardy-Weinberg Equilibrium

The Hardy-Weinberg equilibrium is a fundamental principle of population genetics. It describes that under ideal conditions (random mating, no mutation, no selection, no migration, infinite population size), allele and genotype frequencies remain constant from generation to generation.

### Core Formula
For a biallelic autosomal locus (A and a):
- p = frequency of A, q = frequency of a
- p + q = 1
- Genotype frequencies: p²(AA) + 2pq(Aa) + q²(aa) = 1

### Clinical Applications
- **Carrier frequency estimation**: For AR diseases where incidence q² is known, carrier frequency 2pq ≈ 2q
- **Quality control**: Check whether genotyping data conforms to HWE
- **Population stratification detection**: Deviation from HWE may indicate population stratification or selective pressure
```

#### 2. Clinical Case Analysis
Question:
```bash
A phenotypically normal couple has already had a child with an autosomal recessive disorder. What is the recurrence risk for their next child? If they have had two unaffected children, how does the risk change?
```
Answer:
```bash
## Genetic Counseling Analysis

### Basic Facts
- Both parents phenotypically normal → Both are **carriers** (Aa × Aa)
- Already had one affected child → Inheritance pattern confirmed

### Recurrence Risk Assessment

| Scenario | Recurrence Risk | Explanation |
|----------|---------------|-------------|
| Per-pregnancy baseline risk | 25% (1/4) | Mendelian ratio |
| After one affected child | 25% (1/4) | Independent event; risk per pregnancy unchanged |
| After two unaffected children | 25% (1/4) | Independent event; does not alter subsequent risk |
| Individual risk after Bayesian update | Reduced | This revises the *probability that the couple are carriers* |

### Key Counseling Points
1. **Each pregnancy is independent**: Prior outcomes do not affect subsequent risk
2. **Carrier confirmation**: Genetic testing for both parents is recommended
3. **Prenatal diagnosis**: Prenatal genetic diagnosis is available for future pregnancies
4. **Preimplantation genetic diagnosis (PGD)** : An available option

> ⚠️ Distinguish between "revised carrier probability after unaffected children" (Bayesian) and "per-pregnancy recurrence risk" (independent events) — these are different concepts.
```

#### 3. Exam Questions
Question:
```bash
What is the most common karyotype in Down syndrome?
A. 47,XX,+21
B. 46,XX,der(14;21)(q10;q10),+21
C. 47,XX,+21/46,XX
D. 46,XX,inv(21)
```
Answer:
```bash
**Answer: A. 47,XX,+21**

**Rationale:**
- **Free trisomy (standard type)** : 47,XX,+21 or 47,XY,+21 — accounts for **92-95%** of Down syndrome cases
- **Translocation type**: e.g., 46,XX,der(14;21)(q10;q10),+21 — accounts for **2-4%**
- **Mosaic type**: e.g., 47,XX,+21/46,XX — accounts for **2-3%**

**Clinical Points:**
| Karyotype Type | Proportion | Recurrence Risk |
|---------------|-----------|-----------------|
| Free trisomy | 92-95% | Correlated with maternal age |
| Translocation | 2-4% | Correlated with carrier parent (if mother is a balanced translocation carrier, risk ~10-15%) |
| Mosaic | 2-3% | Depends on proportion of abnormal cells; recurrence risk is generally low |

> Note: Free trisomy is the most common karyotype in Down syndrome and is positively correlated with maternal age.
```

## About the Author

**Xiaolü Lü (xllgreen)** (https://xllgreen.github.io) — Medical Student at Jiujiang University, Tech Enthusiast

## Technical Support
<br>
PDF2App: https://pdf2app.cn
<br>
Microsoft Visual Studio Code: https://code.visualstudio.com/
<br>
Claude Code for VS Code: https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>DeepSeek API: https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. All Rights Reserved
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>Xiaomi Mimo API: https://platform.xiaomimimo.com/
Copyright © 2010 - 2026 Xiaomi. All Rights Reserved
<br>

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FMedical-Genetics-8edition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Medical-Genetics-8edition&type=date&legend=top-left" />
 </picture>
</a>
