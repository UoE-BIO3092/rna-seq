---
layout: page
title: Introduction
order: 2
---

## Instructor

Ryan Ames <mailto:r.ames@exeter.ac.uk>

## Objectives

During the course of this workshop you will:

* Align raw sequencing reads to a reference genome
* Count reads that align to known genes
* Quantify expression and identify differentially expressed genes
* Perform functional pathway analysis using the Gene Ontology

## Introduction

### *Cryptococcus gattii*

*Cryptococcus gattii* is a fungus that can cause a disease called cryptococcosis. Cryptococcosis usually affects the lungs or the central nervous system (the brain and spinal cord), but it can also affect other parts of the body. Brain infections caused by *C. gattii* and other types of *Cryptococcus* are called cryptococcal meningitis. *C. gattii* lives in soil and on certain trees, primarily in tropical and subtropical regions across the world. People can become infected with *C. gattii* after breathing in the microscopic fungus from the environment.

### RNA-Seq

RNA sequencing (RNA-Seq) is a powerful method for discovering, profiling, and quantifying RNA transcripts using massively parallel sequencing technologies. These sequencing technologies are capable of generating hundreds of millions of reads, enabling quantification of transcripts, discovery of new transcripts and discovery of novel isoforms. Most sequencing technologies do not permit direct sequencing of RNA molecules. Instead RNA molecules are extracted from cells of an organism, the RNA is purified and converted into cDNA via reverse transcription and then sequenced.  From the derived sequences it is possible to perform several types of analyses; RNA-seq data can be used to validate gene predictions, find novel splice variants or detect gene fusions. Perhaps the most common type of experiment, and the one we will be looking at here, is identifying genes which are differently expressed under different conditions.

A typical sequencing run would begin with the user supplying 1-10 µg of RNA, extracted from a population of cells, to a sequencing facility along with quality control information. For a typical RNA-seq experiment, mRNA is isolated and reverse-transcribed (RT) into cDNA libraries with homogeneous lengths. This is achieved by either RNA or cDNA fragmentation. Adaptors at one or both ends of the RNA are added prior to cDNA amplification and library construction. For the Illumina platform, cDNA molecules are anchored onto a flow cell surface, which are then subjected to PCR amplification. Images are taken after each cycle for base calling and sequence generation. For the Illumina HiSeq platform, ∼2 billion single or paired-end reads of 50-150nt are generated on a single flow cell (8 lanes/flow cell) which is then processed further depending on the research goals. As technologies advance we have new sequencing methods capable of sequencing extremely long DNA/RNA molecules (~10,000nt) and sequencing DNA/RNA from single cells.

One important feature of RNA-seq is that the data sets are quantitative - the more highly expressed a gene is, the more frequently it will occur in the data. This can then be compared to other samples to look for significant differences in the abundance of mRNA, known as Differential Gene Expression (DGE) analysis.

## In this workshop

In this workshop we will look at the analysis of an RNA-seq dataset for *C. gattii*. Specifically, looking at transcriptomic data from 5 lineages (strains) of *C. gattii* at 1hr and 6hr post- incubation with mouse bone-marrow derived macrophages (BMDM) that simulates infection and the immune response to the fungus. In addition, we have a 0hr *in vitro* control of the fungi growing in the absence of BMDMs. We can use these data to conduct a differential gene expression experiment, where we attempt to find a set of genes that are expressed at different levels between different timepoints (i.e. 0hr and 1hr) and between the 5 strains.  Following on from DGE analysis we will identify enriched GO terms in the set of differentially expressed genes. This will allow us to assign specific functions to these genes.
