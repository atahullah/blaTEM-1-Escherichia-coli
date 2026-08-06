<p align="center">
  <img src="banner.png" alt="Project Banner" width="100%">
</p>

<h1 align="center">
🧬 In Silico Structural Analysis and Predicted Functional Implications of I84V and V184A Mutations in the <i>blaTEM-1</i> Gene of <i>Escherichia coli</i>
</h1>

<p align="center">

![Research](https://img.shields.io/badge/Research-Bioinformatics-blue?style=for-the-badge)
![Field](https://img.shields.io/badge/Field-Structural_Bioinformatics-success?style=for-the-badge)
![Organism](https://img.shields.io/badge/Organism-Escherichia_coli-green?style=for-the-badge)
![Protein](https://img.shields.io/badge/Protein-TEM--1-orange?style=for-the-badge)
![Mutations](https://img.shields.io/badge/Mutations-I84V_|_V184A-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

<p align="center">

**Computational Structural Bioinformatics Research Repository**

</p>

---

# 📖 Project Overview

Antimicrobial resistance (AMR) is one of the greatest threats to global public health, reducing the effectiveness of antibiotics used to treat bacterial infections. Among the numerous resistance mechanisms identified in Gram-negative bacteria, the **TEM-1 β-lactamase** enzyme is one of the most prevalent and extensively studied due to its widespread distribution and role in β-lactam antibiotic resistance.

The **blaTEM-1** gene encodes the TEM-1 β-lactamase enzyme, which hydrolyzes β-lactam antibiotics such as penicillins and early-generation cephalosporins. Naturally occurring mutations within this enzyme may alter residue interactions, local structural stability, protein folding, and potentially influence enzymatic properties. Understanding these structural changes provides valuable insight into the molecular evolution of antimicrobial resistance.

This repository presents an **in silico structural analysis** of two amino acid substitutions, **I84V** and **V184A**, identified in the TEM-1 β-lactamase protein of *Escherichia coli*. The study integrates publicly available biological data with established computational bioinformatics tools to investigate the predicted structural consequences of these mutations.

The computational workflow included sequence retrieval, mutation identification, protein translation, structural visualization, residue verification, and protein stability prediction. Wild-type and mutant nucleotide sequences were obtained from public databases, aligned using BioEdit, translated into protein sequences, and compared with the experimentally determined TEM-1 crystal structure (PDB ID: **1BTL**). Structural visualization was performed using PyMOL, while mutation-induced stability changes and residue interaction networks were evaluated using DynaMut2.

This repository contains the complete computational workflow, supporting datasets, structural models, analysis outputs, figures, and documentation generated during the study. It is intended to serve as a reproducible educational and research resource for students and researchers interested in structural bioinformatics, protein mutation analysis, and antimicrobial resistance.

---

# ⭐ Project Highlights

- 🧬 Complete computational bioinformatics workflow
- 🔬 Structural analysis of TEM-1 β-lactamase
- 🧪 Investigation of two naturally occurring amino acid substitutions
- 📊 Protein stability prediction using DynaMut2
- 🖥 Three-dimensional structural visualization using PyMOL
- 📂 Reproducible workflow using publicly available datasets
- 🎓 Undergraduate research project in Microbiology
- 📚 GitHub repository for open scientific documentation

---

# 🎯 Research Objectives

## Primary Objective

To investigate the predicted structural effects of the **I84V** and **V184A** amino acid substitutions in the TEM-1 β-lactamase protein of *Escherichia coli* using computational bioinformatics approaches.

---

## Specific Objectives

- Retrieve wild-type and mutant **blaTEM-1** nucleotide sequences from publicly available databases.
- Identify nucleotide and amino acid substitutions through sequence alignment.
- Translate nucleotide sequences into protein sequences.
- Retrieve the experimentally determined crystal structure of TEM-1 β-lactamase.
- Verify residue numbering using PyMOL.
- Predict mutation-induced protein stability changes using DynaMut2.
- Compare residue interaction networks between wild-type and mutant proteins.
- Interpret the predicted structural implications of the investigated mutations.

---

# 📑 Table of Contents

- 📖 Project Overview
- ⭐ Project Highlights
- 🎯 Research Objectives
- 🧬 Bioinformatics Workflow
- 🛠 Software and Databases
- 📂 Repository Structure
- 📊 Results
- 📈 Discussion
- ⚠ Limitations
- 🚀 Future Work
- 📚 Citation
- 👨‍💻 Author
- 📜 License

---
# 🧬 Bioinformatics Workflow

This study followed a systematic computational workflow to investigate the predicted structural effects of the **I84V** and **V184A** amino acid substitutions in the TEM-1 β-lactamase protein.

```mermaid
flowchart TD

A[Retrieve blaTEM-1 Sequences<br>NCBI & ENA]

A --> B[Multiple Sequence Alignment<br>BioEdit]

B --> C[Mutation Identification]

C --> D[Protein Translation]

D --> E[Protein Structure Retrieval<br>RCSB PDB (1BTL)]

E --> F[Residue Verification<br>PyMOL]

F --> G[Protein Stability Prediction<br>DynaMut2]

G --> H[Residue Interaction Analysis]

H --> I[Structural Interpretation]
```

---

# 🔬 Materials and Methods

## Study Design

This research was conducted as an **in silico computational structural bioinformatics study** using publicly available nucleotide sequence databases and protein structural resources. No laboratory experiments or clinical samples were involved.

---

## 1. Sequence Retrieval

Wild-type and mutant **blaTEM-1** nucleotide sequences were retrieved from publicly accessible biological databases.

### Databases

| Database | Purpose |
|----------|---------|
| NCBI GenBank | Wild-type and mutant nucleotide sequences |
| European Nucleotide Archive (ENA) | Comparative sequence retrieval |

The retrieved sequences were selected for comparative analysis based on the presence of the investigated amino acid substitutions.

---

## 2. Multiple Sequence Alignment

Nucleotide sequences were aligned using **BioEdit** to identify sequence variation between the wild-type and mutant isolates.

The alignment enabled the identification of nucleotide substitutions responsible for amino acid variation.

### Output

- Multiple sequence alignment
- Mutation identification
- Sequence comparison

---

## 3. Protein Translation

Aligned nucleotide sequences were translated into amino acid sequences using BioEdit.

Protein translation enabled identification of the corresponding amino acid substitutions and facilitated comparison with the experimentally determined TEM-1 protein structure.

---

## 4. Protein Structure Retrieval

The experimentally determined crystal structure of TEM-1 β-lactamase was downloaded from the **RCSB Protein Data Bank**.

| Property | Description |
|----------|-------------|
| Protein | TEM-1 β-lactamase |
| PDB ID | 1BTL |
| Structure Type | X-ray Crystal Structure |
| Source | RCSB Protein Data Bank |

---

## 5. Structural Visualization

Protein structures were visualized using **PyMOL**.

Residue numbering was verified before structural comparison to ensure accurate localization of the investigated amino acid substitutions.

Structural inspection included:

- Residue position
- Local structural environment
- Neighboring residues
- Protein conformation

---

## 6. Protein Stability Prediction

Mutation-induced structural stability changes were predicted using **DynaMut2**.

The following interaction types were evaluated:

- Hydrogen bonds
- Hydrophobic interactions
- Van der Waals interactions
- Polar interactions
- Ionic interactions
- Clash interactions

The predicted stability changes were interpreted alongside observed residue interaction networks.

---

## 7. Comparative Structural Analysis

Wild-type and mutant proteins were compared to evaluate predicted changes associated with the investigated substitutions.

Comparisons focused on:

- Residue interaction networks
- Local structural rearrangements
- Predicted stability changes
- Changes in molecular contacts

---

# 🛠 Software and Databases

| Software / Database | Purpose |
|---------------------|---------|
| NCBI GenBank | Retrieval of nucleotide sequences |
| European Nucleotide Archive (ENA) | Comparative sequence retrieval |
| BioEdit | Sequence alignment and protein translation |
| RCSB Protein Data Bank | Protein structure retrieval |
| PyMOL | Three-dimensional visualization and residue verification |
| DynaMut2 | Protein stability prediction |
| GitHub | Repository hosting and version control |

---

# 📂 Repository Structure

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
│   ├── Mutant/
│   ├── Protein/
│   └── FASTA/
│
├── alignments/
│   ├── Nucleotide/
│   ├── Protein/
│   └── BioEdit/
│
├── structures/
│   ├── PDB_1BTL/
│   ├── PyMOL/
│   └── Mutant_Models/
│
├── results/
│   ├── DynaMut2/
│   ├── Interaction_Analysis/
│   ├── Stability/
│   └── Figures/
│
├── documentation/
│   ├── Workflow/
│   ├── Methodology/
│   ├── Thesis/
│   └── Supplementary/
│
└── references/
    └── Literature/
```

---

# 📁 Repository Organization

The repository is organized into dedicated directories containing nucleotide sequences, translated protein sequences, structural models, alignment files, PyMOL visualization data, DynaMut2 analyses, figures, and supporting documentation.

This organization facilitates reproducibility, transparency, and efficient navigation for researchers and students interested in computational structural bioinformatics.

---

# 🧬 Investigated Mutations

| Mutation | Amino Acid Change | Structural Context |
|----------|-------------------|--------------------|
| **I84V** | Isoleucine → Valine | Evaluated for predicted changes in residue interactions and local structural stability |
| **V184A** | Valine → Alanine | Investigated for predicted effects on molecular interactions and protein stability |

---

# ⚠ Scientific Scope

This repository presents **computational predictions** based on structural bioinformatics analyses.

The study **does not** include:

- Wet-laboratory experiments
- Enzyme kinetic assays
- Antibiotic susceptibility testing
- Clinical validation
- Molecular dynamics simulations

Therefore, all conclusions are limited to the interpretation of computational analyses and should not be considered experimental confirmation of protein function.

---
# 📊 Results

Computational analyses were performed to compare the structural characteristics of the wild-type TEM-1 β-lactamase protein with two investigated amino acid substitutions (**I84V** and **V184A**).

The analyses included:

- Multiple sequence alignment
- Protein sequence translation
- Structural visualization
- Residue interaction analysis
- Protein stability prediction

The observed differences provide insight into how individual amino acid substitutions may influence the local structural environment of the TEM-1 β-lactamase protein.

---

# 🔬 Residue Interaction Analysis

## I84V Mutation

| Interaction Type | Wild Type | Mutant |
|------------------|----------:|-------:|
| Clash | 2 | 2 |
| Aromatic | 0 | 0 |
| Van der Waals | 1 | 2 |
| Hydrophobic | 6 | 4 |
| Hydrogen Bonds | 6 | 7 |
| Polar | 6 | 6 |
| Carbonyl | 0 | 0 |
| Ionic | 0 | 0 |

### Interpretation

The I84V substitution resulted in:

- Increased hydrogen bond formation
- Increased van der Waals interactions
- Reduced hydrophobic contacts
- No change in ionic or aromatic interactions

These observations suggest localized rearrangement of residue interactions while maintaining the overall structural framework of the protein.

---

## V184A Mutation

| Interaction Type | Wild Type | Mutant |
|------------------|----------:|-------:|
| Clash | 0 | 0 |
| Aromatic | 0 | 0 |
| Van der Waals | 0 | 3 |
| Hydrophobic | 6 | 1 |
| Hydrogen Bonds | 5 | 4 |
| Polar | 6 | 5 |
| Carbonyl | 0 | 0 |
| Ionic | 0 | 0 |

### Interpretation

The V184A substitution showed:

- Reduced hydrophobic interactions
- Increased van der Waals contacts
- Slight reduction in hydrogen bonding
- Slight reduction in polar interactions

These predicted changes indicate local structural alterations around the mutated residue.

---

# 📈 Comparative Summary

| Feature | I84V | V184A |
|---------|------|--------|
| Hydrogen Bonds | Increased | Decreased |
| Hydrophobic Contacts | Decreased | Markedly Decreased |
| Van der Waals | Increased | Increased |
| Polar Contacts | Unchanged | Slightly Reduced |
| Overall Prediction | Local structural rearrangement | Local structural rearrangement |

---

# 💡 Discussion

The present computational analyses suggest that both investigated amino acid substitutions influence local residue interaction networks within the TEM-1 β-lactamase structure.

The **I84V** substitution produced relatively modest changes, characterized by increased hydrogen bonding and van der Waals interactions accompanied by reduced hydrophobic contacts. These observations are consistent with a localized reorganization of molecular interactions rather than extensive structural disruption.

In contrast, the **V184A** substitution produced a greater reduction in hydrophobic interactions while increasing van der Waals contacts. Such changes may reflect altered packing around the substituted residue and localized changes in the surrounding structural environment.

Because these findings are derived from computational structural analyses, they should be interpreted as **predicted structural effects** rather than experimentally confirmed changes in enzyme activity or antibiotic resistance.

---

# 📌 Key Findings

- Two naturally occurring amino acid substitutions were investigated.
- Structural comparisons were performed using experimentally determined TEM-1 coordinates (PDB ID: 1BTL).
- Residue numbering was verified prior to structural analysis.
- DynaMut2 predicted mutation-associated changes in residue interaction networks.
- Both substitutions altered local molecular interactions.
- No evidence from this study directly confirms changes in catalytic activity or antimicrobial resistance phenotype.

---

# 📷 Figures Included

The repository contains the following figures:

- Workflow diagram
- Multiple sequence alignment
- Protein sequence alignment
- PyMOL structural visualization
- DynaMut2 interaction analysis
- Comparative residue interaction summary

```text
results/
│
├── Figures/
│   ├── Figure_1_Workflow.png
│   ├── Figure_2_SequenceAlignment.png
│   ├── Figure_3_I84V_Structure.png
│   ├── Figure_4_V184A_Structure.png
│   ├── Figure_5_DynaMut2.png
│   └── Figure_6_InteractionSummary.png
```

---

# 📊 Repository Status

| Item | Status |
|------|--------|
| Sequence Retrieval | ✅ Completed |
| Multiple Sequence Alignment | ✅ Completed |
| Protein Translation | ✅ Completed |
| Structure Retrieval | ✅ Completed |
| PyMOL Analysis | ✅ Completed |
| DynaMut2 Prediction | ✅ Completed |
| Structural Comparison | ✅ Completed |
| Documentation | ✅ Completed |
| GitHub Repository | ✅ Completed |

---

# 🔍 Scientific Significance

This repository demonstrates how publicly available biological databases and computational bioinformatics tools can be integrated into a reproducible workflow for investigating mutation-associated structural changes in proteins.

The study highlights the usefulness of structural bioinformatics in generating hypotheses regarding the possible effects of amino acid substitutions while emphasizing that computational predictions should be complemented by experimental validation whenever possible.

---
# ⚠ Limitations

Although this study provides a reproducible computational framework for investigating amino acid substitutions in the TEM-1 β-lactamase protein, several limitations should be considered.

- The study is based exclusively on publicly available nucleotide sequences and protein structures.
- Structural analyses were performed using computational prediction tools and were not validated through laboratory experiments.
- Enzyme kinetics, antimicrobial susceptibility testing, and functional assays were beyond the scope of this study.
- Only two amino acid substitutions (I84V and V184A) were investigated.
- Molecular dynamics simulations and protein-ligand docking analyses were not performed.

Consequently, the findings should be interpreted as **computational predictions** rather than experimentally validated functional outcomes.

---

# 🚀 Future Work

The computational workflow established in this project can be expanded in several directions.

Future studies may include:

- Investigation of additional TEM-1 variants
- Comparative analysis of other β-lactamase families (e.g., SHV, CTX-M, NDM)
- Molecular docking with β-lactam antibiotics
- Molecular dynamics simulations to investigate protein flexibility
- Evolutionary conservation analysis
- Phylogenetic analysis of blaTEM-1 variants
- Machine learning approaches for mutation effect prediction
- Experimental validation of computational predictions

---

# 🔄 Reproducibility

This repository has been organized to support reproducible computational analyses.

Researchers can reproduce the workflow using the following resources:

| Component | Resource |
|-----------|----------|
| Sequence Retrieval | NCBI GenBank, ENA |
| Sequence Alignment | BioEdit |
| Protein Structure | RCSB Protein Data Bank (PDB ID: 1BTL) |
| Structural Visualization | PyMOL |
| Stability Prediction | DynaMut2 |

The repository contains the datasets, structural files, analysis outputs, and documentation required to reproduce the analyses presented in this project.

---

# 📚 Citation

If you use this repository in your research or academic work, please cite it as:

### APA Style

> Atahullah. (2026). *In Silico Structural Analysis and Predicted Functional Implications of I84V and V184A Mutations in the blaTEM-1 Gene of Escherichia coli*. GitHub Repository.

---

### BibTeX

```bibtex
@misc{Atahullah2026,
  author       = {Atahullah},
  title        = {In Silico Structural Analysis and Predicted Functional Implications of I84V and V184A Mutations in the blaTEM-1 Gene of Escherichia coli},
  year         = {2026},
  publisher    = {GitHub},
  url          = {https://github.com/atahullah/blaTEM-1-Escherichia-coli}
}
```

---

# 🙏 Acknowledgements

This research was completed as part of the **Bachelor of Science (BS) in Microbiology** program.

The project utilized publicly available biological databases and established computational bioinformatics tools.

The author gratefully acknowledges the developers and maintainers of the following resources:

- National Center for Biotechnology Information (NCBI)
- European Nucleotide Archive (ENA)
- RCSB Protein Data Bank (PDB)
- BioEdit
- PyMOL
- DynaMut2

Their commitment to open scientific resources has made computational biology research more accessible to students and researchers worldwide.

---

# 👨‍💻 Author

## Atahullah

**BS Microbiology Graduate**

**Independent Bioinformatics Researcher**

### Research Interests

- Structural Bioinformatics
- Antimicrobial Resistance (AMR)
- Protein Structure Analysis
- Molecular Biology
- Comparative Genomics
- Computational Biology
- Microbial Genomics

📧 **Email**

atahullah.epd.pk@gmail.com

💻 **GitHub**

https://github.com/atahullah

🔗 **LinkedIn**

https://www.linkedin.com/in/atahullah-bioinformatics

---

# 📜 License

This project is distributed under the **MIT License**.

You are free to use, modify, and distribute the contents of this repository in accordance with the terms of the MIT License.

For additional information, please refer to the `LICENSE` file included in this repository.

---

# 📖 Suggested Repository Citation

**Repository Name**

```
blaTEM-1-Escherichia-coli
```

**Research Area**

```
Structural Bioinformatics
```

**Study Type**

```
Computational (In Silico)
```

**Organism**

```
Escherichia coli
```

**Gene**

```
blaTEM-1
```

**Protein**

```
TEM-1 β-lactamase
```

**Investigated Variants**

```
I84V
V184A
```

**Protein Structure**

```
PDB ID: 1BTL
```

---

# ⭐ Repository Support

If you found this repository useful for learning, teaching, or research, please consider:

- ⭐ Starring the repository
- 🍴 Forking the repository
- 📢 Sharing it with others
- 🧬 Citing it in academic work (where appropriate)

Constructive feedback, suggestions, and scientific discussions are always welcome.

---

<p align="center">

**Computational Structural Bioinformatics • Protein Structure Analysis • Antimicrobial Resistance Research**

---

Developed as an undergraduate research project in Microbiology.

© 2026 Atahullah. All Rights Reserved.

</p>
