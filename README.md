<p align="center">
  <img src="banner.png" alt="Project Banner" width="100%">
</p>

<h1 align="center">
🧬 In Silico Structural and Functional Analysis of V184A and I84V Mutations in the <i>blaTEM-1</i> Gene of <i>Escherichia coli</i>
</h1>

<p align="center">
Computational Bioinformatics Research Repository
</p>

<p align="center">

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Bioinformatics](https://img.shields.io/badge/Field-Bioinformatics-blue)
![Organism](https://img.shields.io/badge/Organism-Escherichia_coli-success)
![Protein](https://img.shields.io/badge/Protein-TEM--1-orange)
![Mutations](https://img.shields.io/badge/Mutations-I84V%20%7C%20V184A-red)

</p>

---

**Repository Name:** `blaTEM-1-Escherichia-coli`

**Protein:** TEM-1 β-lactamase

**PDB Structure:** 1BTL

**Mutations:** I84V • V184A

---

## 📑 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Research Objectives](#-research-objectives)
- [🛠 Software & Databases](#-software--databases)
- [🧬 Bioinformatics Workflow](#-bioinformatics-workflow)
- [📂 Repository Structure](#-repository-structure)
- [🧬 Mutations Investigated](#-mutations-investigated)
- [📊 Results](#-results)
- [📈 Key Findings](#-key-findings)
- [📚 Citation](#-citation)
- [👤 Author](#-author)
- [📜 License](#-license)

---

## 📖 Project Overview

The rapid emergence of antimicrobial resistance (AMR) has become one of the most significant global public health challenges. Among the mechanisms responsible for bacterial resistance to β-lactam antibiotics, the **blaTEM-1** gene is one of the most extensively studied due to its widespread occurrence in *Escherichia coli* and other Gram-negative bacteria. Mutations within the TEM-1 β-lactamase protein can alter its structural stability, residue interactions, and enzymatic activity, ultimately influencing antibiotic resistance.

This repository presents a comprehensive **in silico structural and functional analysis** of two amino acid substitutions, **I84V** and **V184A**, identified in the TEM-1 β-lactamase protein. The computational workflow integrates sequence analysis, structural biology, and protein stability prediction to evaluate the potential effects of these mutations on protein architecture and molecular interactions.

The study was performed using publicly available biological databases together with widely accepted bioinformatics software. Wild-type and mutant nucleotide sequences were retrieved from **NCBI** and the **European Nucleotide Archive (ENA)**, followed by multiple sequence alignment and protein translation using **BioEdit**. The experimentally determined crystal structure of TEM-1 β-lactamase (**PDB ID: 1BTL**) was obtained from the **RCSB Protein Data Bank** for structural comparison.

Three-dimensional visualization and residue verification were performed using **PyMOL**, while mutation-induced stability changes and residue interaction networks were analyzed using **DynaMut2**. Comparative analyses of wild-type and mutant proteins were conducted to investigate alterations in hydrogen bonds, hydrophobic interactions, van der Waals interactions, polar contacts, and overall structural stability.

This repository contains the complete computational workflow, supporting datasets, structural files, analysis results, figures, and documentation generated throughout the study, providing a reproducible resource for researchers and students interested in antimicrobial resistance, protein structural bioinformatics, and mutation analysis.

---

## 🎯 Research Objectives

### Primary Objective

To investigate the structural and functional effects of the **I84V** and **V184A** mutations in the **blaTEM-1 β-lactamase** protein of *Escherichia coli* using computational bioinformatics approaches.

### Specific Objectives

- Retrieve wild-type and mutant **blaTEM-1** nucleotide sequences from public databases.
- Identify nucleotide and amino acid substitutions through sequence alignment.
- Translate nucleotide sequences into protein sequences using BioEdit.
- Retrieve the crystal structure of TEM-1 β-lactamase (PDB ID: **1BTL**).
- Visualize protein structures and verify residue numbering using PyMOL.
- Predict mutation-induced stability changes using DynaMut2.
- Compare residue interaction networks between wild-type and mutant proteins.
- Interpret the structural and functional consequences of the I84V and V184A mutations.

---

## 🧬 Bioinformatics Workflow

The study followed a systematic computational pipeline to investigate the structural and functional effects of the **I84V** and **V184A** mutations in the **blaTEM-1 β-lactamase** protein.

```text
NCBI & ENA
     │
     ▼
Sequence Retrieval
     │
     ▼
Multiple Sequence Alignment (BioEdit)
     │
     ▼
Mutation Identification
     │
     ▼
Protein Translation
     │
     ▼
Protein Structure Retrieval (PDB: 1BTL)
     │
     ▼
Structural Visualization (PyMOL)
     │
     ▼
Protein Stability Analysis (DynaMut2)
     │
     ▼
Interaction Analysis
     │
     ▼
Results & Interpretation
```

### Workflow Steps

1. Retrieved wild-type and mutant **blaTEM-1** nucleotide sequences from **NCBI** and the **European Nucleotide Archive (ENA)**.
2. Performed multiple sequence alignment using **BioEdit** to identify nucleotide substitutions.
3. Translated nucleotide sequences into protein sequences.
4. Retrieved the crystal structure of TEM-1 β-lactamase (**PDB ID: 1BTL**) from the **RCSB Protein Data Bank**.
5. Verified amino acid residue numbering and visualized protein structures using **PyMOL**.
6. Predicted mutation-induced stability changes using **DynaMut2**.
7. Compared residue interaction networks between wild-type and mutant proteins.
8. Interpreted the structural and functional impact of the **I84V** and **V184A** mutations.

---

## 🛠 Software & Databases

| Software / Database | Purpose |
|---------------------|---------|
| **NCBI** | Retrieval of wild-type and mutant nucleotide sequences |
| **European Nucleotide Archive (ENA)** | Sequence database used for comparative analysis |
| **BioEdit** | Multiple sequence alignment and protein translation |
| **RCSB Protein Data Bank (PDB)** | Retrieval of TEM-1 β-lactamase crystal structure (1BTL) |
| **PyMOL** | Protein structure visualization and residue verification |
| **DynaMut2** | Protein stability prediction and residue interaction analysis |
| **GitHub** | Repository hosting, documentation, and version control |

---

## 📂 Repository Structure

```text
blaTEM-1-Escherichia-coli/
│
├── README.md
├── LICENSE
├── .gitignore
├── banner.png
│
├── sequences/
│   ├── Wild_Type/
│   └── Mutant/
│
├── alignments/
│   ├── Nucleotide/
│   └── Protein/
│
├── structures/
│   ├── PDB_1BTL/
│   ├── PyMOL_Sessions/
│   └── Mutant_Models/
│
├── results/
│   ├── DynaMut2/
│   ├── Figures/
│   └── Interaction_Analysis/
│
└── documentation/
    ├── Workflow/
    ├── Methodology/
    └── Thesis_Figures/
```

### Repository Organization

The repository is organized into dedicated directories containing nucleotide and protein sequences, structural models, PyMOL session files, DynaMut2 analyses, figures, and supporting documentation. This organization ensures that all computational analyses can be easily accessed, reproduced, and verified.

---

## 🧬 Mutations Investigated

| Mutation | Amino Acid Change | Structural Significance |
|----------|-------------------|-------------------------|
| **I84V** | Isoleucine → Valine | Evaluated for changes in residue interactions and protein stability. |
| **V184A** | Valine → Alanine | Investigated for its effect on local structural stability and molecular interactions. |

---
## 📊 Results

The computational analyses identified structural differences between the wild-type TEM-1 β-lactamase protein and the two investigated mutants (I84V and V184A).

The analyses included:

- Multiple sequence alignment
- Protein sequence comparison
- Three-dimensional structural visualization
- Protein stability prediction
- Residue interaction analysis

The observed differences in residue interactions provide insight into the potential structural consequences of the investigated mutations.

###  Results Summary

| Interaction Type | I84V Wild Type | I84V Mutant | V184A Wild Type | V184A Mutant |
|-----------------|---------------:|------------:|----------------:|-------------:|
| Clash | 2 | 2 | 0 | 0 |
| Aromatic | 0 | 0 | 0 | 0 |
| Van der Waals | 1 | 2 | 0 | 3 |
| Hydrophobic | 6 | 4 | 6 | 1 |
| Hydrogen Bonds | 6 | 7 | 5 | 4 |
| Polar | 6 | 6 | 6 | 5 |
| Carbonyl | 0 | 0 | 0 | 0 |
| Ionic | 0 | 0 | 0 | 0 |

### Interpretation

The **I84V** mutation increased hydrogen bonding and van der Waals interactions while reducing hydrophobic contacts, indicating moderate changes in the local interaction network.

The **V184A** mutation reduced hydrophobic interactions and increased van der Waals contacts, suggesting localized structural rearrangements within the TEM-1 β-lactamase protein.

Overall, both mutations altered residue interaction networks and may influence the structural stability and functional properties of the TEM-1 β-lactamase enzyme.

## 📊 Repository Status

**Project Status:** ✅ Completed

This repository contains the complete computational analyses performed for the undergraduate research project entitled **"In Silico Structural and Functional Analysis of V184A and I84V Mutations in the *blaTEM-1* Gene of *Escherichia coli*"**.

### Repository Contents

- ✅ Wild-type and mutant nucleotide sequences
- ✅ Protein sequence alignments
- ✅ TEM-1 β-lactamase crystal structure (PDB ID: 1BTL)
- ✅ PyMOL visualization files
- ✅ DynaMut2 stability analyses
- ✅ Residue interaction analyses
- ✅ Research figures
- ✅ Computational workflow documentation
- ✅ Supporting project files

This repository is organized to provide a reproducible computational workflow for investigating mutation-induced structural and functional changes in the TEM-1 β-lactamase protein.

---

## 📈 Key Findings

- The **I84V** and **V184A** mutations altered residue interaction networks within the TEM-1 β-lactamase protein.
- Comparative structural analyses identified differences in hydrogen bonding, hydrophobic interactions, and van der Waals contacts between the wild-type and mutant proteins.
- DynaMut2 analysis provided insights into mutation-induced stability changes and local structural rearrangements.
- PyMOL visualization confirmed residue positions and supported detailed structural comparison of the investigated mutations.
- The integrated computational workflow demonstrates the value of bioinformatics approaches for studying protein mutations associated with antimicrobial resistance.

---

## 📚 Citation

If you use this repository in your research or academic work, please cite it as:

> Atahullah. (2026). *In Silico Structural and Functional Analysis of V184A and I84V Mutations in the blaTEM-1 Gene of Escherichia coli*. GitHub repository. https://github.com/atahullah/blaTEM-1-Escherichia-coli

---

## 🙏 Acknowledgements

This research was conducted as part of the **Bachelor of Science (BS) in Microbiology** program.

The study utilized publicly available biological databases and computational bioinformatics tools, including:

- National Center for Biotechnology Information (NCBI)
- European Nucleotide Archive (ENA)
- RCSB Protein Data Bank (PDB)
- BioEdit
- PyMOL
- DynaMut2

The authors gratefully acknowledge the developers and maintainers of these scientific resources for providing open access to biological data and computational tools.

---

## 👤 Author

**Atahullah**

Bachelor of Science (BS) in Microbiology

Undergraduate Research Project

GitHub: https://github.com/atahullah

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this work in accordance with the terms of the MIT License.

For complete license information, see the [LICENSE](LICENSE) file.

---

<p align="center">

**Developed as part of a Bachelor of Science (BS) in Microbiology research project.**

*Computational Bioinformatics • Protein Structure Analysis • Antimicrobial Resistance Research*

© 2026 Atahullah

</p>
