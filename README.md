# Biopython_Projects
# 🦠 Phylogenetic Tree Generation for Viral Sequences  

## 📌 Overview  
This project analyzes viral sequences from metagenomic datasets to construct and visualize **phylogenetic trees**. Using **Clustal Omega** for multiple sequence alignment and **Biopython** for tree generation, the project provides insights into evolutionary relationships between detected viral sequences.

## 🛠 Features  
- 🏗 **Multiple Sequence Alignment:** Aligns sequences using Clustal Omega.  
- 🌳 **Phylogenetic Tree Construction:** Generates trees in Newick format.  
- 📊 **Tree Visualization:** Uses Matplotlib and Biopython (Phylo module).  
- 💾 **Export Options:** Saves trees as PNG, SVG, or PDF.  
- 🔍 **Exploratory Analysis:** Identifies sequence similarities and cluster formations.  
- 🎨 **Customization:** Supports rooting, branch styling, and interactive visualization.

## 📂 Dataset  
The dataset is sourced from:  
**"Deciphering viral presences: two novel partial giant viruses detected in marine metagenome and in a mine drainage metagenome."**  
- Contains **Query Seq-IDs and Subject Seq-IDs** instead of GenBank accession numbers.  
- Provides insights into novel **giant viruses** found in different environments.  

## 🚀 Installation  
Ensure you have Python and the required libraries installed:  
```bash
pip install biopython matplotlib seaborn pandas plotly
