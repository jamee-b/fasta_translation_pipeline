# fasta_translation_pipeline
# FASTA Translation & Motif Detection Pipeline

## Overview
This project implements an end-to-end bioinformatics pipeline that processes DNA FASTA files, translates sequences into proteins across multiple reading frames using BioJava, and detects biologically relevant motifs in the resulting protein sequences.

## Problem Statement
Translating raw genomic sequence data into biologically meaningful protein insights is a core task in genomics and drug discovery. This pipeline automates translation and motif detection to support downstream biological analysis.

## Dataset
- Input: DNA FASTA files
- Source: Public genomic datasets (e.g., NCBI / course-provided data)
- Output: Protein FASTA files and motif summary tables

## Tools & Technologies
- Java
- BioJava
- FASTA format
- Jupyter Notebook (analysis)
- GitHub

## Methodology
1. Parse DNA FASTA files
2. Perform six-frame translation
3. Identify motifs using pattern matching
4. Export structured results
5. Analyze motif frequency and protein length distributions

## Results
- Successfully translated sequences into protein products
- Identified motif presence across multiple sequences
- Generated summary statistics for downstream analysis

## Future Improvements
- Integration with BLAST
- Support for additional motif databases
- Performance optimization for large FASTA files

