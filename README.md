# 🧬 Genome Assembly with Velvet

> **De novo genome assembly of Illumina short-read sequencing data using the Velvet assembler on the Galaxy platform.**

---

## 📖 Overview

This project demonstrates the complete workflow for performing **de novo genome assembly** using the **Velvet** assembler. The tutorial reconstructs a bacterial genome from Illumina short-read sequencing data without relying on a reference genome.

Velvet is a widely used genome assembler designed for **short-read sequencing datasets**. It constructs **de Bruijn graphs** from sequencing reads and improves assembly quality by removing sequencing errors and simplifying repetitive regions.

In this project, an **imaginary _Staphylococcus aureus_ mutant strain** with a miniature genome (~197 kb) is assembled from whole-genome shotgun sequencing reads generated on an Illumina sequencing platform.

A reference genome is also provided for downstream comparison and evaluation.

---

## 🎯 Objectives

The goals of this project are to:

- Perform **de novo genome assembly** using Velvet
- Assemble Illumina paired-end sequencing reads
- Evaluate sequencing read quality before assembly
- Generate assembled contigs
- Assess assembly statistics
- Understand the fundamentals of graph-based genome assembly

---

## 🧬 Dataset

**Organism**
- *Staphylococcus aureus* (Imaginary mutant strain)

**Genome Size**
- ~197,394 bp

**Sequencing Platform**
- Illumina

**Sequencing Method**
- Whole Genome Shotgun (WGS)

**Assembly Type**
- De novo Assembly

---

## 🛠️ Workflow

```text
Input Reads
      │
      ▼
Quality Assessment
      │
      ▼
Velvet Assembly
      │
      ▼
Generate Contigs
      │
      ▼
Assembly Statistics
      │
      ▼
Reference Genome Comparison
```

---

## 📚 Tutorial Sections

- 📖 Introduction to Velvet
- 📥 Obtain the sequencing data
- 🔍 Evaluate input read quality
- 🧩 Perform genome assembly using Velvet
- 📊 Collect assembly statistics
- 🧬 Compare with the reference genome

---

## 🔬 Tools Used

| Tool | Purpose |
|------|---------|
| Galaxy Platform | Workflow execution |
| Velvet | De novo genome assembly |
| FASTQ | Input sequencing reads |
| Reference Genome | Assembly evaluation |

---

## 📈 Expected Outputs

- Assembled contigs
- Assembly statistics
- Contig length distribution
- Number of contigs
- Total assembled genome size
- Reference genome for comparison

---

## 📂 Repository Structure

```text
Genome-assembly-with-Velvet/
│
├── README.md
├── images/
│   ├── workflow.png
│   ├── velvet-results.png
│   └── assembly-stats.png
├── datasets/
├── results/
└── workflow/
```

---

## 🎓 Learning Outcomes

After completing this project, you will understand:

- De novo genome assembly
- De Bruijn graph assembly algorithms
- Velvet assembly workflow
- Quality assessment before assembly
- Interpretation of assembly statistics
- Basic bacterial genome assembly concepts

---

## 📚 References

- Zerbino DR, Birney E. **Velvet: Algorithms for de novo short read assembly using de Bruijn graphs.** *Genome Research.* 2008.

- Galaxy Training Network (GTN)

---

## 👨‍💻 Author

**Shunanda Sharkar**

B.Tech Biotechnology Undergraduate  
Bioinformatics Learner | Galaxy Platform | Genomics

---

⭐ If you found this repository helpful, consider giving it a star!
