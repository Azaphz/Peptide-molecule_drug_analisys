# Sequence Analysis Toolkit

Bioinformatics/CADD sandbox: peptide sequence analysis, PDB structure parsing, and drug-likeness scoring with RDKit and MDAnalysis.

## What it does

- **Peptide sequence report** — molecular weight, amino acid composition, isoelectric point (via Biopython), Kyte-Doolittle hydropathy plot
- **FASTA → RDKit** — builds a peptide `Mol` object directly from a one-letter sequence, extracts SMILES, cross-validates manual MW against RDKit's computed MW, draws the structure
- **PDB structure analysis** — parses a real PDB file with MDAnalysis, extracts the sequence directly from structure, computes a CA-CA contact map
- **Molecular Property Calculator** — calculates molecular descriptors and reports Lipinski Rule of Five criterion compliance for small molecules and peptides

## Stack

Python, RDKit, MDAnalysis, Biopython, pandas, NumPy, Matplotlib

## Run it

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Azaphz/Peptide-molecule_drug_analisys/blob/main/Peptide-molecule_drug_analisys.ipynb)

Or locally:
\`\`\`
pip install -r requirements.txt
\`\`\`
