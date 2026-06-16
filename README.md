# RNAseq-DE-Pipeline

## Overview

This project demonstrates the core steps of an RNA-seq differential expression workflow using a small educational reference genome.

The purpose of the project is to understand how raw sequencing reads are transformed into gene-level expression measurements through quality control, alignment, BAM processing, annotation, and gene quantification.

This repository focuses on learning the mechanics of RNA-seq analysis rather than performing biological discovery.

---

## Workflow

FASTQ Files

↓

FastQC

↓

MultiQC

↓

Reference Genome

↓

HISAT2 Indexing

↓

Read Alignment

↓

SAM

↓

BAM

↓

Sorted BAM

↓

BAM Index (.bai)

↓

Gene Annotation (GTF)

↓

featureCounts

↓

Count Matrix

---

## Concepts Covered

* FASTQ files
* Sequencing quality control
* FastQC
* MultiQC
* Genome indexing
* Read alignment
* SAM format
* BAM format
* BAM sorting
* BAM indexing
* GTF annotation files
* Gene-level quantification
* Count matrices
* featureCounts

---

## Project Structure

```text
RNAseq-DE-Pipeline/

data/raw/
results/
reference/
index/
alignments/
counts/

README.md
rnaseq_environment.yml
```

## Key Learning Outcomes

This project demonstrates:

* Understanding of RNA-seq workflow structure
* Familiarity with common bioinformatics file formats
* Experience using FastQC, MultiQC, HISAT2, Samtools, and featureCounts
* Understanding of how BAM and GTF files generate count matrices
* Preparation for full transcriptomics projects using real biological datasets

## Future Work

A future companion project will perform a complete RNA-seq differential expression analysis using:

* Human reference genome (GRCh38)
* Multiple biological replicates
* DESeq2
* Volcano plots
* Heatmaps
* Pathway analysis
* Biological interpretation
