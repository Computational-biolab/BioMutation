#  BioMutation : A portable graphical user interface for mutagenesis and Feature Analysis in proteins, nucleic acids, and their complexes


---

## Overview

Mutations in proteins and nucleic acids play a fundamental role in understanding the molecular mechanisms underlying diseases, evolutionary processes, and therapeutic targeting. Systematic mutational studies provide valuable insights into biomolecular structure, conformational dynamics, and interactions with macromolecules or small-molecule ligands. Despite their importance, computational mutagenesis is often limited by the lack of tools that combine high-throughput mutation capabilities with intuitive, user-friendly interfaces.

**BioMutation** is a multifunctional graphical user-interface (GUI)–based platform developed to address these challenges. It enables efficient, high-throughput mutagenesis of proteins, nucleic acids, and their complexes while remaining accessible to both experimental and computational researchers. The platform supports targeted as well as exhaustive mutation strategies and is designed to seamlessly integrate with downstream structural and molecular modeling workflows.

---

## Key Features

### Protein Mutagenesis
- User-defined single or multiple amino acid mutations
- Exhaustive class-wise mutations across protein sequences, including:
  - Hydrophobic amino acids
  - Aromatic amino acids
  - Acidic amino acids
  - Basic amino acids
- Applicable to:
  - Individual protein chains
  - Protein–protein complexes
  - Protein–nucleic acid complexes

### Nucleic Acid Mutagenesis
- User-specified mutations in DNA and RNA
- Systematic generation of all possible:
  - Di-nucleotide mutations
  - Tri-nucleotide mutations
  - Tetra-nucleotide mutations (DNA)
- Supported systems:
  - DNA
  - RNA
  - Nucleic acid–protein complexes

---

## Output Formats

BioMutation generates comprehensive libraries of mutant structures in widely used and interoperable formats:

- **PDB**
- **MOL2**
- **mmCIF**

These formats are directly compatible with common computational pipelines, including:
- Molecular docking
- Molecular dynamics (MD) simulations
- Binding affinity prediction
- Structural and energetic analyses

---

## BioMutation Structure Analyzer

In addition to mutation generation, BioMutation integrates a **PDB Structure Analyzer** module for post-mutation and standalone structural analysis.

### Features
- Analysis of structural, chemical, and molecular features
- Chain-wise evaluation of:
  - Proteins
  - Nucleic acids
  - Biomolecular complexes
- Comparative analysis of features before and after mutation
- Export of results in downloadable tabular formats (CSV/Excel)

### Standalone Usage
The Structure Analyzer can also be used independently to analyze any PDB structure without performing mutations, making it a versatile tool for structural bioinformatics studies.

---

## Applications

BioMutation supports a wide range of research and industrial applications, including:

- **Drug Discovery**
  - Modeling mutation-driven drug resistance
  - Exploring binding-site variability in therapeutic targets

- **Protein Engineering**
  - Design and optimization of enzymes and antibodies
  - Engineering proteins with improved stability, specificity, or activity

- **Nucleic Acid Research**
  - Investigation of protein–DNA/RNA interactions
  - Aptamer design and optimization
  - Analysis of mutations implicated in genetic diseases

- **Computational Structural Biology**
  - High-throughput mutational scanning
  - Structure–function relationship studies
  - Integration with docking and free-energy calculations

---

## Technology Stack

- Python-based backend
- Graphical user-interface for mutation and analysis workflows
- Compatible with standard molecular modeling and simulation tools
- Designed for scalability and extensibility



---

## License

This project is released under an open-source license.  
Please refer to the `LICENSE` file for details.



---

## Contributions and Support

Contributions, feature requests, and bug reports are welcome.  
Please open an issue or submit a pull request to contribute to the project.

---

