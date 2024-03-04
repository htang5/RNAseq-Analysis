# Analyzing Gene Expression During Phosphate Starvation in Yeasts

## Introduction
Yeasts display an acquired stress resistance (ASR) response where a mild dose of primary stress.

To understand transcriptional changes that occured during the phosphate starvation primary stress, RNA-seq experiments were done and phosphate starvation time course data was gathered for multiple species.

In this part of the bioinformatics analysis, I aim to analyze the gene expression pattern changes in K. lactis before and after 45min phosphate starvation. I specifically focused on OSR genes and transcription factors. 

I aim to also analyze expression patterns of alternative carbohydrate metabolism genes in C. glabrata. My previous experiment showed that phosphate starvation provides ASR protection against an alcohol stress. The mechanism of the protection is unknow. Alcohol stress is a membrane stress and yeast cell membrane has storage of alternative carbon sources such as trehalose. I hypothesize that changes in the trehalose synthesis pathways underlies the observed ASR. The goal of this project is to analyze the RNAseq data and survey transcritional levels of alternative carbohydrate metabolism genes after phosphate starvation.

## Analysis Methods
**Data**
The RNA-seq raw or processed data will not be uploaded. This repository only contains my analysis scripts, and output from analysis.

**Methods**
*RNA-seq Results Quality Control* The quality control step is done using fastQC in R. 

*Alignment and Reads Counting* Alignment was done using Bowtie2 and reads count was done by Rsubreads.

*Plotting and Analysis* Normalization was done by DESeq pakcage in R and plotting was done by ggplot2.

