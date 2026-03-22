# Scoping Review: AI-Assisted Tools in the Video Game Development Process

This repository contains the dataset, reference files, and supporting materials for the scoping literature review titled:

**“AI-Assisted Tools in the Video Game Development Process: A Scoping Literature Review”**

---

## 📊 Overview

This study systematically analyzes research published between **2020 and 2025**, identifying how artificial intelligence (AI) is applied to support different stages of the video game development process.

A total of **135 studies** were included after a rigorous multi-stage screening process based on **PRISMA-ScR guidelines**.

---

## 📁 Repository Structure

### `/data`
Structured datasets organized by **time period**:

#### `/data/2020-2024`
Original dataset used in the primary study:

- `ScopingReview.xlsx` → Master dataset (screening + coding)
- `Articulos_SCOPING_sin_duplicados.xlsx` → Deduplicated records
- `ACM_export.csv`
- `IEEE_export.csv`
- `SCOPUS_export.csv`
- `WOS_export.csv`

#### `/data/2025`
Extended dataset for the update:

- `All Articles.xlsx` → Aggregated dataset for 2025
- `ACM.xlsx`
- `IEEE.xlsx`
- `SCOPUS.xlsx`
- `WOS.xlsx`

This separation enables:

- Clear distinction between **original review (2020–2024)** and **update (2025)**
- Temporal analysis of AI trends in game development
- Full reproducibility of the data collection process

---

### `/pdfs`
Full-text articles organized by **year range and inclusion decision**:

#### `/pdfs/2020-2024`
- `/Included` → Studies included in the review
- `/Excluded` → Studies excluded after full-text screening

#### `/pdfs/2025`
- `/Included` → Studies included in the update
- `/Excluded` → Studies excluded after full-text screening

---

### `/bib`
Bibliographic data:

- `references.bib` → BibTeX file used in the manuscript

---

## 🧪 Review Scope

This scoping review maps the use of AI across the **video game development lifecycle**, including:

- Procedural Content Generation (PCG)
- Level and environment design
- Narrative generation and dialogue systems
- Non-Player Character (NPC) behavior modeling
- Automated playtesting and QA
- Human–AI co-creative design tools
- Generative AI and Large Language Models (LLMs)

---

## 📜 Inclusion Criteria

Studies were included if they:

- Focus on AI-assisted tools or methods **applied to game development**
- Present a **technical implementation, framework, or system**
- Were published between **2020 and 2025**
- Include **evaluation, validation, or practical application**

---

## ❌ Exclusion Criteria

Studies were excluded if they:

- Focus exclusively on **serious games, education, or simulation** (without development focus)
- Lack **technical or methodological contribution**
- Do not include **evaluation or validation**
- Are inaccessible or incomplete

---

## 🔍 Methodology

The review follows the **PRISMA-ScR framework**, including:

1. Identification of studies across multiple databases
2. Removal of duplicates
3. Title and abstract screening
4. Full-text eligibility assessment
5. Data extraction and coding

---

## 📈 Data Coding Dimensions

Each study was classified according to five analytical dimensions:

- **Technical Aspect (TA)**
- **Methodological Design (MD)**
- **Application Domain (AD)**
- **Validation Approach (VA)**
- **Reported Contributions (RC)**

---

## ♻️ Reproducibility

This repository ensures full reproducibility by providing:

- Raw database exports
- Deduplicated datasets
- Screening decisions (included/excluded)
- Full-text articles (when legally distributable)
- Coding schema and final dataset

---

## 📌 Notes on Dataset Expansion

The repository explicitly distinguishes between:

- **Initial dataset (2020–2024)**
- **Extended dataset (2025)**

This allows:

- Replication of the original study
- Longitudinal analysis of trends
- Future extensions of the dataset

---

## 👨‍🔬 Authors

**Dr. Cristian Vidal-Silva**  
University of Talca, Chile  
📧 cvidal@utalca.cl  

**Dr. Nicolás Barriga**  
University of Talca, Chile  
📧 nbarriga@utalca.cl  

**Dr. Felipe Besoaín**  
University of Talca, Chile  
📧 fbesoain@utalca.cl  

---

## 📄 License

This repository is intended for **academic and non-commercial use only**.

Full-text PDFs are shared only when permitted by publisher policies.  
Please contact the authors for reuse permissions.

---

## ⭐ Citation

If you use this dataset, please cite:

> Vidal-Silva, C., Barriga, N., Besoaín, F.  
> *AI-Assisted Tools in the Video Game Development Process: A Scoping Literature Review*
