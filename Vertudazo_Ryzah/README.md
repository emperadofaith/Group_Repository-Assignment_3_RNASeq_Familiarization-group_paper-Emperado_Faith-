

## 
Name:Vertudazo, Maria Ryzah May I. 
Group 3

##  Title: Salmonella Typhi Colonization Provokes Extensive Transcriptional Changes Aimed at Evading Host Mucosal Immune Defense During Early Infection of Human Intestinal Tissue

## Author: K. P. Nickerson, S. Senger, Y. Zhang, R. Lima, S. Patel, L. Ingano, W. A. Flavahan, D. K. V. Kumar, C. M. Fraser, C. S. Faherty, M. B. Sztein, M. Fiorentino, A. Fasano
Journal: EBioMedicine
Year: 2018

## Assigned RNA-Seq Sample
Accession: SRR7029707

Condition: Infected tissue biopsy

Sequencing: single-end

File size: 912.1 MB

Number of reads: 24,357,703

Read length: 51 bp

GC content: 52%

## Biological Description
SRR7029707 represents an infected human intestinal tissue biopsy exposed to Salmonella Typhi. It is part of the treatment condition used to examine transcriptional changes associate with S. Typhi infection. 

## FastQC Results 
Per-based sequence quality: High-quality; Phred scores are high (Q30) 
Adapter content: No significant adapter contamination detected
Overrepresented sequences: Warning; overrepresented sequences detected
Quality warning: Yes; overrepresented sequence, GC content, and sequence duplication levels failed

## Screenshots
<img width="2360" height="1419" alt="IMG_1950" src="https://github.com/user-attachments/assets/bbd6f157-854a-4dbd-a335-5b7559b2652d" />
Fig.1 Basic Statistics. The dataset contains 24,357,703 sequences, totaling about 1.2 Gbp, with a read length of 51 bp and an average GC content of 52 percent. No sequences were flagged as poor quality. 
<img width="810" height="612" alt="att 3glFU6btsmAasxl5Q6HX8LK8UTycBXdmFBgffCJFv7w" src="https://github.com/user-attachments/assets/c123cbd6-5f7f-4fbd-bda2-1d996a5d9d3a" />
Fig.2 The reads show high and consistent quality, mostly around Q38-40, with all positions remaining in the green zone. 
<img width="806" height="594" alt="att 7RB-lMCmk6plWqVS8Y1rnslDk-IT04MmCTK8wRQOn6M" src="https://github.com/user-attachments/assets/92040061-e3bf-42dc-954e-d7be636a8603" />
Fig.3 The GC content distribution is irregular and differs from the theoretical distribution, with peaks around 40-50 percent and another around 80-85 percent. This explains the failed QC result and may indicate sequence or sample composition bias. 

<img width="801" height="597" alt="att 0NpwdTp_h2BfYiXUKUZUdDpI1x8UM5q0Oj2osoW-QiE" src="https://github.com/user-attachments/assets/4f968e46-86fc-4813-a1ad-6eda83a2e89a" />
Fig.4 Cumulative percentage of sequencing adapter contamination across base pair positions in the reads. The green checkmark and flat baseline at 0 percent indicate that the reads are clean and completlely free of common adapter contamination. 

<img width="1566" height="536" alt="att EzkwaeS3p-zkzsVbJDF6CxYZeKlsX01Qw9Fp6P7gcow" src="https://github.com/user-attachments/assets/8b8c277d-66e6-4ba3-bd2e-d82b0f0f637a" />
Fig. 5 Sequence reads occur far more frequently than expected. The orange warning icon indicates the presence of highly repetitive sequences in the dataset, which may represent biological signal, contamination, or PCR over-duplication


## Interpretation Questions
1. What biological question was the original RNA-seq study trying to answer?
The study aimed to determine how Salmonella typhi alters gene expression during its early interaction with human intestinal tissue. Specifically, the researchers wanted to understand how the pathogen responds to the intestinal environments and how it may modify the host’s mucosal immune defenses. The study therefore examined transcriptional changes associated with S. typhi colonization of human intestinal cells.

2. Why did the authors use RNA-seq instead of only examining the genome?
The genome shows which genes are present, but not which genes are active. RNA-seq allowed the researchers to identify genes that were being expressed or changing during S. typhi infection. 
 3. What is the difference between genomic DNA and the RNA molecules measured by RNA-seq?
Genomic DNA represents the organism's relatively stable genetic information and contains the complete set of genes. RNA molecules, in contrast, are produced when particular genes are expressed. Therefore, RNA provides information about which genes are actively being transcribed under specific biological conditions. In this study, RNA-seq was useful because the researchers were interested in changes in gene expression during S. typhi colonization of human intestinal tissue. The RNA data could therefore reveal changes in transcription that would not be apparent from examining the genome alone. 

4. What is a biological replicate and why is it important?
A biological replicate is a separate biological sample representing the same experimental condition. In the study, the researchers used multiple human intestinal biopsies for both the uninfected control and infected conditions, along with bacterial control samples. Biological replicates are important because they allow researchers to determine whether an observed transcriptional difference is consistently associated with the experimental condition rather than being caused by natural variation between individual samples. Having multiple biological replicates also strengthens the reliability of comparisons between control and infected conditions. 

5. What is the difference between single-end and paired-end sequencing?
Single-end sequencing reads each RNA-seq fragment from only one end, producing one sequence read for each fragment. Paired-end sequencing reads the same fragment from both ends, producing two related reads that provide additional information about the fragment. In this study, the researchers used single-end 50-bp sequencing on an Illumina HiSeq 2500. 

6. What is a FASTQ file?
A FASTQ file is a sequencing-data format that contains both the nucleotide sequences generated during sequencing and the quality information associated with those sequences. Each read is represented by four lines: a sequence identifier, the nucleotide sequence, a separator line, and quality-score. The quality scores are particularly important because they indicate the confidence of the sequencing instrument in each base call. This makes FASTQ different from formats such as FASTA, which primarily provide sequence information and identifiers. 

7. What information does FastQC provide
FastQC checks the quality of sequencing data. It provides information about base quality, GC content, adapter contamination, sequence duplication, and overrepresented sequences and marks results as pass, warning, or fail.
8. What does a high per-base quality score indicate?
A high quality score means the sequencing instrument is highly confident that the reported nucleotide is correct. It generally indicates reliable sequencing reads. 
9. Why can adapter contamination be a problem?
Adapter sequences are artificial sequences added during library preparation to allow RNA fragments to be processed and sequenced. If adapter sequences remain in the final reads, they can interfere with downstream sequence analysis because they are not part of the biological RNA being studied. 
10. Were all RNA-seq samples in your group similar in quality? Explain.
The samples were generally similar because they had good base quality and little adapter contamination. However, some samples had differences in GC content, duplication, sequence content, or overrepresented sequences. 
11. Did any sample show a possible quality problem? What was it?
The samples were generally similar because they had good base quality and little adapter contamination. However, some samples had differences in GC content, duplication, sequence content, or overrepresented sequences. 

12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?
The reads should first undergo quality control and trimming of adapters or low-quality bases when needed. They then need to be aligned to a reference genome or transcriptome and quantified. Finally, statistical analysis using the biological replicates can identify genes with significant differences in expression between the control and infected samples. 

## Conclusion
The RNA-seq showed generally good sequencing quality, particularly in terms of per base sequence quality and adapter content. However, some quality concerns were observed including overrepresented sequences, GC content, and sequence duplication levels. FastQC really helped in checking the quality of raw RNA-seq data before proceeding into further analysis. Further processing will also be needed before comparing gene expression between the control and infected samples. 

